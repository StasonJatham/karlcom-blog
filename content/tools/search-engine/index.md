---
title: "Search Engine"
subtitle: "Use these tools to quickly get up and running with search engine OSINT."
date: 2023-04-17T20:11:53+02:00
description: ""
keywords: ""
comment: false
---

<style> 
input[type=submit] {
  background-color: #5dd9ef;
  border: none;
  border-radius: 6px;
  color: black;
  padding: 4px 8px;
  text-decoration: none;
  margin: 1px 1px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #90e9f9;
  border: none;
  border-radius: 6px;
  color: black;
  padding: 4px 8px;
  text-decoration: none;
  margin: 1px 1px;
  cursor: pointer;
  box-shadow: 0.2rem 0.2rem black;
  transform: translate(-1px, -1px);
  transition-duration: 0.2s;
}
</style>

<div class="searchengine-body">
    <h4 class="card-title">Search Engines Tool</h4>
    <hr>
    <p class="card-text">
        <script type="text/javascript">
            function doPopAll(PopAll) {
                var pop = document.getElementById("PopAll");
                for (j = 1; j <= 100; j++) {
                    if (j < 10) {
                        j = "0" + j.toString();
                    } else {
                        j = j.toString();
                    }
                    console.log(j)
                    item = document.getElementById("Search" + j);
                    if (item != null) {
                        item.value = pop.value;
                    }
                }
            }
        </script>
    </p>
    <form onsubmit="doPopAll(this.PopAll.value); return false;">
        <input type="text" id="PopAll" name="PopAll" size="30" placeholder="Search Terms">
        <input type="submit"  value="Populate All"><br></form><br>
    <script type="text/javascript">
        function doSearch01(Search01) {
            window.open('http://google.com/search?q=' + Search01, 'Search01window');
        }
    </script>
    <form onsubmit="doSearch01(this.Search01.value); return false;">
        <input type="text" id="Search01" name="Search01" size="30" placeholder="Search Terms">
        <input type="submit"  value="Google"><br></form>
    <script type="text/javascript">
        function doSearch02(Search02) {
            window.open('http://google.com/search?q=' + Search02 + '&tbs=cdr:1,cd_min:1/1/0,sbd:1', 'Search02window');
        }
    </script>
    <form onsubmit="doSearch02(this.Search02.value); return false;">
        <input type="text" id="Search02" name="Search02" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google Date"><br></form>
    <script type="text/javascript">
        function doSearch03(Search03) {
            window.open('http://www.google.com/search?tbm=nws&q=' + Search03, 'Search03window');
        }
    </script>
    <form onsubmit="doSearch03(this.Search03.value); return false;">
        <input type="text" id="Search03" name="Search03" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google News"><br></form>
    <script type="text/javascript">
        function doSearch04(Search04) {
            window.open('https://www.google.com/search?q=' + Search04 + '&tbm=nws&tbs=nrt:b', 'Search04window');
        }
    </script>
    <form onsubmit="doSearch04(this.Search04.value); return false;">
        <input type="text" id="Search04" name="Search04" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google Blogs"><br></form>
    <script type="text/javascript">
        function doSearch05(Search05) {
            window.open('https://www.google.com/search?q=inurl%3Aftp%20-inurl%3A(http|https)%20' + Search05,
                'Search05window');
        }
    </script>
    <form onsubmit="doSearch05(this.Search05.value); return false;">
        <input type="text" id="Search05" name="Search05" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google FTP"><br></form>
    <script type="text/javascript">
        function doSearch06(Search06) {
            window.open('https://www.google.com/search?q=intitle%3Aindex.of+' + Search06, 'Search06window');
        }
    </script>
    <form onsubmit="doSearch06(this.Search06.value); return false;">
        <input type="text" id="Search06" name="Search06" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google Index"><br></form>
    <script type="text/javascript">
        function doSearch07(Search07) {
            window.open('http://scholar.google.com/scholar?&q=' + Search07, 'Search07window');
        }
    </script>
    <form onsubmit="doSearch07(this.Search07.value); return false;">
        <input type="text" id="Search07" name="Search07" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google Scholar"><br></form>
    <script type="text/javascript">
        function doSearch08(Search08) {
            window.open('https://patents.google.com/?q=' + Search08, 'Search08window');
        }
    </script>
    <form onsubmit="doSearch08(this.Search08.value); return false;">
        <input type="text" id="Search08" name="Search08" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Google Patents"><br></form>
    <script type="text/javascript">
        function doSearch09(Search09) {
            window.open('http://bing.com/search?q="' + Search09 + '"', 'Search09window');
        }
    </script>
    <form onsubmit="doSearch09(this.Search09.value); return false;">
        <input type="text" id="Search09" name="Search09" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Bing"><br></form>
    <script type="text/javascript">
        function doSearch10(Search10) {
            window.open('http://bing.com/news/search?q="' + Search10 + '"', 'Search10window');
        }
    </script>
    <form onsubmit="doSearch10(this.Search10.value); return false;">
        <input type="text" id="Search10" name="Search10" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Bing News"><br></form>
    <script type="text/javascript">
        function doSearch11(Search11) {
            window.open('http://search.yahoo.com/search?p=' + Search11, 'Search11window');
        }
    </script>
    <form onsubmit="doSearch11(this.Search11.value); return false;">
        <input type="text" id="Search11" name="Search11" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Yahoo"><br></form>
    <script type="text/javascript">
        function doSearch12(Search12) {
            window.open('http://www.yandex.com/yandsearch?text=' + Search12, 'Search12window');
        }
    </script>
    <form onsubmit="doSearch12(this.Search12.value); return false;">
        <input type="text" id="Search12" name="Search12" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Yandex"><br></form>
    <script type="text/javascript">
        function doSearch13(Search13) {
            window.open('http://baidu.com/s?wd=' + Search13, 'Search13window');
        }
    </script>
    <form onsubmit="doSearch13(this.Search13.value); return false;">
        <input type="text" id="Search13" name="Search13" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Baidu"><br></form>
    <script type="text/javascript">
        function doSearch14(Search14) {
            window.open('https://searx.be/?q=' + Search14, 'Search14window');
        }
    </script>
    <form onsubmit="doSearch14(this.Search14.value); return false;">
        <input type="text" id="Search14" name="Search14" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Searx"><br></form>
    <script type="text/javascript">
        function doSearch15(Search15) {
            window.open('http://www.exalead.com/search/web/results/?q=' + Search15, 'Search15window');
        }
    </script>
    <form onsubmit="doSearch15(this.Search15.value); return false;">
        <input type="text" id="Search15" name="Search15" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Exalead"><br></form>
    <script type="text/javascript">
        function doSearch16(Search16) {
            window.open('https://duckduckgo.com/?q=' + Search16, 'Search16window');
        }
    </script>
    <form onsubmit="doSearch16(this.Search16.value); return false;">
        <input type="text" id="Search16" name="Search16" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="DuckDuckGo"><br></form>
    <script type="text/javascript">
        function doSearch17(Search17) {
            window.open('https://startpage.com/do/search?q=' + Search17, 'Search17window');
        }
    </script>
    <form onsubmit="doSearch17(this.Search17.value); return false;">
        <input type="text" id="Search17" name="Search17" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="StartPage"><br></form>
    <script type="text/javascript">
        function doSearch18(Search18) {
            window.open('https://www.qwant.com/?q=' + Search18, 'Search18window');
        }
    </script>
    <form onsubmit="doSearch18(this.Search18.value); return false;">
        <input type="text" id="Search18" name="Search18" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Qwant"><br></form>
    <script type="text/javascript">
        function doSearch19(Search19) {
            window.open('https://search.brave.com/search?q=' + Search19, 'Search19window');
        }
    </script>
    <form onsubmit="doSearch19(this.Search19.value); return false;">
        <input type="text" id="Search19" name="Search19" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Brave"><br></form>
    <script type="text/javascript">
        function doSearch20(Search20) {
            window.open('https://web.archive.org/web/*/' + Search20, 'Search20window');
        }
    </script>
    <form onsubmit="doSearch20(this.Search20.value); return false;">
        <input type="text" id="Search20" name="Search20" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Wayback"><br></form>
    <script type="text/javascript">
        function doSearch21(Search21) {
            window.open('https://ahmia.fi/search/?q=' + Search21, 'Search21window');
        }
    </script>
    <form onsubmit="doSearch21(this.Search21.value); return false;">
        <input type="text" id="Search21" name="Search21" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Ahmia"><br></form>
    <script type="text/javascript">
        function doSearch22(Search22) {
            window.open('https://onionlandsearchengine.com/search?q=' + Search22, 'Search22window');
        }
    </script>
    <form onsubmit="doSearch22(this.Search22.value); return false;">
        <input type="text" id="Search22" name="Search22" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Onionland"><br></form>
    <br>
    <script type="text/javascript">
        function doall(all) {
            window.open('http://google.com/search?q=' + all, 'Search01window');
            window.open('http://google.com/search?q=' + all + '&tbs=cdr:1,cd_min:1/1/0,sbd:1', 'Search02window');
            window.open('http://www.google.com/search?tbm=nws&q=' + all, 'Search03window');
            window.open('https://www.google.com/search?q=' + all + '&tbm=nws&tbs=nrt:b', 'Search04window');
            window.open('https://www.google.com/search?q=inurl%3Aftp%20-inurl%3A(http|https)%20' + all,
                'Search05window');
            window.open('https://www.google.com/search?q=intitle%3Aindex.of+' + all, 'Search06window');
            window.open('http://scholar.google.com/scholar?&q=' + all, 'Search07window');
            window.open('https://patents.google.com/?q=' + all, 'Search08window');
            window.open('http://bing.com/search?q="' + all + '"', 'Search09window');
            window.open('http://bing.com/news/search?q="' + all + '"', 'Search10window');
            window.open('http://search.yahoo.com/search?p=' + all, 'Search11window');
            window.open('http://www.yandex.com/yandsearch?text=' + all, 'Search12window');
            window.open('http://baidu.com/s?wd=' + all, 'Search13window');
            window.open('https://searx.be/?q=' + all, 'Search14window');
            window.open('http://www.exalead.com/search/web/results/?q=' + all, 'Search15window');
            window.open('https://duckduckgo.com/?q=' + all, 'Search16window');
            window.open('https://startpage.com/do/search?q=' + all, 'Search17window');
            window.open('https://www.qwant.com/?q=' + all, 'Search18window');
            window.open('https://search.brave.com/search?q=' + all, 'Search19window');
            window.open('https://web.archive.org/web/*/' + all, 'Search20window');
            window.open('https://ahmia.fi/search/?q=' + all, 'Search21window');
            window.open('https://onionlandsearchengine.com/search?q=' + all, 'Search22window');
        }
    </script>
    <form onsubmit="doall(this.all.value); return false;">
        <input type="text" id="Search99" name="all" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Submit All">
    </form>
    <br>
    Tor Required:
    <br>
    <script type="text/javascript">
        function doSearch23(Search23) {
            window.open('http://torch4st4l57l2u2vr5wqwvwyueucvnrao4xajqr2klmcmicrv7ccaad.onion/search?query=' +
                Search23 + '&action=search', 'Search23window');
        }
    </script>
    <form onsubmit="doSearch23(this.Search23.value); return false;">
        <input type="text" id="Search23" name="Search23" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Torch"><br></form>
    <script type="text/javascript">
        function doSearch24(Search24) {
            window.open('http://www.tor66sewebgixwhcqfnp5inzp5x5uohhdy3kvtnyfxc2e5mxiuh34iid.onion/search?q=' +
                Search24, 'Search24window');
        }
    </script>
    <form onsubmit="doSearch24(this.Search24.value); return false;">
        <input type="text" id="Search24" name="Search24" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Tor66"><br></form>
    <script type="text/javascript">
        function doSearch25(Search25) {
            window.open('http://haystak5njsmn2hqkewecpaxetahtwhsbsa64jom2k22z5afxhnpxfid.onion/?q=' + Search25,
                'Search25window');
        }
    </script>
    <form onsubmit="doSearch25(this.Search25.value); return false;">
        <input type="text" id="Search25" name="Search25" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Haystack"><br></form>
    <script type="text/javascript">
        function doSearch26(Search26) {
            window.open('http://juhanurmihxlp77nkq76byazcldy2hlmovfu2epvl5ankdibsot4csyd.onion/search/?q=' + Search26,
                'Search26window');
        }
    </script>
    <form onsubmit="doSearch26(this.Search26.value); return false;">
        <input type="text" id="Search26" name="Search26" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Ahmia"><br></form>
    <script type="text/javascript">
        function doSearch27(Search27) {
            window.open('http://srcdemonm74icqjvejew6fprssuolyoc2usjdwflevbdpqoetw4x3ead.onion/search?q=' + Search27,
                'Search27window');
        }
    </script>
    <form onsubmit="doSearch27(this.Search27.value); return false;">
        <input type="text" id="Search27" name="Search27" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="SearchDemon"><br></form>
    <script type="text/javascript">
        function doSearch28(Search28) {
            window.open('http://2fd6cemt4gmccflhm6imvdfvli3nf7zn6rfrwpsy7uhxrgbypvwf5fad.onion/search/' + Search28,
                'Search28window');
        }
    </script>
    <form onsubmit="doSearch28(this.Search28.value); return false;">
        <input type="text" id="Search28" name="Search28" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Excavator"><br></form>
    <script type="text/javascript">
        function doSearch29(Search29) {
            window.open(
                'http://zb2jtkhnbvhkya3d46twv3g7lkobi4s62tjffqmafjibixk6pmq75did.onion/gdark/search.php?query=' +
                Search29, 'Search29window');
        }
    </script>
    <form onsubmit="doSearch29(this.Search29.value); return false;">
        <input type="text" id="Search29" name="Search29" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="GDark"><br></form>
    <script type="text/javascript">
        function doSearch30(Search30) {
            window.open('http://u5lyidiw4lpkonoctpqzxgyk6xop7w7w3oho4dzzsi272rwnjhyx7ayd.onion/?s=' + Search30,
                'Search30window');
        }
    </script>
    <form onsubmit="doSearch30(this.Search30.value); return false;">
        <input type="text" id="Search30" name="Search30" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Hidden Reviews"><br></form>
    <script type="text/javascript">
        function doSearch31(Search31) {
            window.open('http://3bbad7fauom4d6sgppalyqddsqbf5u5p56b5k5uk2zxsy3d6ey2jobad.onion/search?q=' + Search31,
                'Search31window');
        }
    </script>
    <form onsubmit="doSearch31(this.Search31.value); return false;">
        <input type="text" id="Search31" name="Search31" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="OnionLand"><br></form>
    <script type="text/javascript">
        function doSearch32(Search32) {
            window.open('http://phobosxilamwcg75xt22id7aywkzol6q6rfl2flipcqoc4e4ahima5id.onion/search?query=' +
                Search32, 'Search32window');
        }
    </script>
    <form onsubmit="doSearch32(this.Search32.value); return false;">
        <input type="text" id="Search32" name="Search32" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Phobos"><br></form>
    <script type="text/javascript">
        function doSearch33(Search33) {
            window.open('http://no6m4wzdexe3auiupv2zwif7rm6qwxcyhslkcnzisxgeiw6pvjsgafad.onion/search.php?term=' +
                Search33, 'Search33window');
        }
    </script>
    <form onsubmit="doSearch33(this.Search33.value); return false;">
        <input type="text" id="Search33" name="Search33" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="Submarine"><br></form>
    <script type="text/javascript">
        function doSearch34(Search34) {
            window.open('http://searchgf7gdtauh7bhnbyed4ivxqmuoat3nm6zfrg3ymkq6mtnpye3ad.onion/search?q=' + Search34,
                'Search34window');
        }
    </script>
    <form onsubmit="doSearch34(this.Search34.value); return false;">
        <input type="text" id="Search34" name="Search34" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="DeepSearch"><br></form>
    <script type="text/javascript">
        function doSearch35(Search35) {
            window.open('http://5qqrlc7hw3tsgokkqifb33p3mrlpnleka2bjg7n46vih2synghb6ycid.onion/index.php?a=search&q=' +
                Search35, 'Search35window');
        }
    </script>
    <form onsubmit="doSearch35(this.Search35.value); return false;">
        <input type="text" id="Search35" name="Search35" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="OnionCenter"><br></form>
    <script type="text/javascript">
        function doSearch36(Search36) {
            window.open('http://freshonifyfe4rmuh6qwpsexfhdrww7wnt5qmkoertwxmcuvm4woo4ad.onion/?query=' + Search36,
                'Search36window');
        }
    </script>
    <form onsubmit="doSearch36(this.Search36.value); return false;">
        <input type="text" id="Search36" name="Search36" size="30" placeholder="Search Terms" value="">
        <input type="submit"  value="FreshOnion"><br></form>
    <p></p>
</div>
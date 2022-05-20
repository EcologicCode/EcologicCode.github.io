# Ecologic Code

<center style="background-color:green"><b>Nouveau ! </b>Nouveau site disponible <a href="App/Web/EcologicCodeWebSite.html">ici</a></center><br>

<button onclick="location.href='lang.html'">Langs</button><br>
<a href="Root/OpenCreators/OpenCreators.exe">Télécharger OpenCreators</a><br>
<a href="Web/" target="about:">Outils du site...</a>

<script type="module" src="/JQuery/js.cookie.min.mjs"></script>
<script type="module">
  import Cookies from '/JQuery/js.cookie.min.mjs'

  if(!Cookies.get('lang') == "undefined"){
  Cookies.set('lang', navigator.language, { expires: 365 });
  }else {
    var lang = Cookies.get('lang');
    if(lang=""){}
  }
</script>

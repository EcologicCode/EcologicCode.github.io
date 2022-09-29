<h1>Redirection...</h1>
<noscript>Please active Javascript</noscript>
<script type="text/javascript">
  var link = window.location.href;
  var str = link.split("#")[1];
  var links = ["/", "/tools", "/informatique", "/WebEdit", "https://github.com/ecologiccode/", "/Linux", "/Linux/KDE", "/Linux/Linix", "/Store-center/app#FirePage", "/EcoWeb", "/informatique/ecoweb/Preloader-system.html"];
  if(str.indexOf("undefined")){
    location.href="/share/";
  }else {
   location.href=links[parseInt( str, 0 )];
   }</script>

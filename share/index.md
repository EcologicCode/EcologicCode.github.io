# Share System

Le Share System est un système de partage de créations, facile à utiliser.<br>
Attention : Il faut un système de cloud (Wetransfer, pour les fichiers temporaires...) pour certains partages.<br>
<hr>

[A propos de Share System](about.html) | [Partager...](#Share)<br>

<div id="Share"><h1>Partager</h1></div>

[Depuis une section du site la section](#Share-section)<br>[Un fichier](#Share-file)<br>[Une Url](#Share-Url)<br>[Une page Web](#Share-web)<br>[Une idée](#Share-idea)<br>[Du texte](#Share-text)

<h1 id="Share-section">Partager... Depuis une section du site la section
</h1>
<ol><li>Sur la section choisie, chercher le bouton "Partager..." en bas de page.</li><br>
<li>Sur la page suivante, sélectionnez "Obtenir une adresse de partage ShareSystem...".</li>
<li>Patientez la création d'Url.</li>
<li>Copiez votre URL, et partagez-la !</li>
</ol>

<h1 id="Share-file">Partager... Un fichier</h1><center>
<video controls="" preload="metadata"><source src="https://ecologiccode.github.io/share/Wetransfert.mp4"></video>
<br><i>Avoir une adresse de transfert avec WeTransfert</i>
</center>
Ensuite, allez ci-dessous et insérez l'url.<br>

Url : <input type="text" id="qrurl"><button onClick="qr()">
<br>

<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
<script type="text/javascript">
    function qr(){
    location.href=$("#qrurl").val();
    }
</script>

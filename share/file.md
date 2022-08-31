<script src="https://cdnjs.cloudflare.com/ajax/libs/qrious/4.0.2/qrious.min.js"></script>
<div id="qrcode"></div>
<script type="text/javascript">
    var text;
    const str = window.location.href;

        const words = str.split('#');
        $("#text").val(decodeURI(words[1]));
        text = decodeURI(words[1]);
new QRCode(document.getElementById("qrcode"), text);
</script>
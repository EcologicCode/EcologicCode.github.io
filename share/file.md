<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.qrcode/1.0/jquery.qrcode.min.js" integrity="sha512-NFUcDlm4V+a2sjPX7gREIXgCSFja9cHtKPOL1zj6QhnE0vcY695MODehqkaGYTLyL2wxe/wtr4Z49SvqXq12UQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
<div id="qrcode"></div>

<script>
jQuery(function(){
    var text;
    const str = window.location.href;

        const words = str.split('#');
        $("#text").val(decodeURI(words[1]));
        text = decodeURI(words[1]);
	jQuery('#qrcode').qrcode(text);
})
</script>

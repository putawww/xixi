<html>
<head>
<title> Hai Maniezz </title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("cius nih? mi apa? xixi mmq terbank")
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1> Hai Nyonya <h1>
<img src="https://c.tenor.com/3wof3XBMBTAAAAAM/blackpink-rosesarerosie.gif" height="200" />
<h1 style="#">Apakah engkau ingin menjadi istri ak?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YA " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" TIDAK " onMouseOver="f()" />
</div>

</body>
</html>

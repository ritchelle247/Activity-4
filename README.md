<style>
body{

background-color:purple;
background-size: cover;
background-repeat: no-repeat;
font-size: 20px;
color:silver;
text-align: center;

font-style:oblique;
}
button{
border-color: purple;
padding:6px 22px;
border-radius: 7px;
margin-bottom: 70px;
color:black;
font-size: 25px;
letter-spacing: 2px;
text-decoration:none;
font-style:noir;
}
</style> 
<script>
function zodiac() {
document.getElementById("my").innerHTML= "<b>CANCER</b>";
document.getElementById("photo").innerHTML= "<img src='Screenshot_20201219-102702~2.png'width=20%>";
document.getElementById("per").innerHTML = "<b>Characteristic</b><br><br>June 23rd birthday personality says you are very generous and warm-hearted which makes you capable of helping the needy people.";
}
</script>
<body>  
<br>
<br>
<p><b> Birthday: June 23</b></p>
<br>
<button type="button" onclick="zodiac()"><b>My Zodiac Sign</b></button>
<p id="my">
<p id="photo">
<p id="per">



# TeaMCyber



<html><head>
<br>
<p align="center"> <img src="http://dc126.4shared.com/img/ImIRAZe0/s3/bendera_indonesia.gif"> </p>
</br>
<title> ( The-X-Cyber ) </title>
<link rel="icon" href="none" type="image/x-icon" />
<link rel="shortcut icon" href="none" type="image/x-icon" />
<style type="text/css">
<!--
.ahgcrewstyle {
        color: #F00;
}
.ahg {
        color: #0F0;
}
#message font strong {
        font-family: Tahoma, Geneva, sans-serif;
        font-size: 18px;
}
.gre
        color: #9F3;
        font-size: 36px;
}
#message font {
        font-size: 16px;
}
-->
</style>
</head><body alink="gray" bgcolor="black" vlink="gray" link="gray" text="gray">
<p></p><center>
<center></center>
<script type="text/javascript">
TypingText = function(element, interval, cursor, finishedCallback) {
  if((typeof document.getElementById == "undefined") || (typeof element.innerHTML == "undefined")) {
    this.running = true;
    return;
  }
  this.element = element;
  this.finishedCallback = (finishedCallback ? finishedCallback : function() { return; });
  this.interval = (typeof interval == "undefined" ? 100 : interval);
  this.origText = this.element.innerHTML;
  this.unparsedOrigText = this.origText;
  this.cursor = (cursor ? cursor : "");
  this.currentText = "";
  this.currentChar = 0;
  this.element.typingText = this;
  if(this.element.id == "") this.element.id = "typingtext" + TypingText.currentIndex++;
  TypingText.all.push(this);
  this.running = false;
  this.inTag = false;
  this.tagBuffer = "";
  this.inHTMLEntity = false;
  this.HTMLEntityBuffer = "";
}
TypingText.all = new Array();
TypingText.currentIndex = 0;
TypingText.runAll = function() {
  for(var i = 0; i < TypingText.all.length; i++) TypingText.all[i].run();
}
TypingText.prototype.run = function() {
 if(this.running) return;
 if(typeof this.origText == "undefined") {
   setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);
   return;
 }
 if(this.currentText == "") this.element.innerHTML = "";
 if(this.currentChar < this.origText.length) {
   if(this.origText.charAt(this.currentChar) == "<" && !this.inTag) {
     this.tagBuffer = "<";
     this.inTag = true;
     this.currentChar++;
     this.run();
     return;
   } else if(this.origText.charAt(this.currentChar) == ">" && this.inTag) {
     this.tagBuffer += ">";
      this.inTag = false;
      this.currentText += this.tagBuffer;
      this.currentChar++;
      this.run();
      return;
    } else if(this.inTag) {
      this.tagBuffer += this.origText.charAt(this.currentChar);
      this.currentChar++;
      this.run();
      return;
    } else if(this.origText.charAt(this.currentChar) == "&" && !this.inHTMLEntity) {
     this.HTMLEntityBuffer = "&";
      this.inHTMLEntity = true;
      this.currentChar++;
      this.run();
      return;
    } else if(this.origText.charAt(this.currentChar) == ";" && this.inHTMLEntity) {
     this.HTMLEntityBuffer += ";";
      this.inHTMLEntity = false;
      this.currentText += this.HTMLEntityBuffer;
      this.currentChar++;
      this.run();
      return;
    } else if(this.inHTMLEntity) {
      this.HTMLEntityBuffer += this.origText.charAt(this.currentChar);
      this.currentChar++;
      this.run();
      return;
    } else {
      this.currentText += this.origText.charAt(this.currentChar);
    }
    this.element.innerHTML = this.currentText;
    this.element.innerHTML += (this.currentChar < this.origText.length - 1 ? (typeof this.cursor == "function" ? this.cursor(this.currentText) : this.cursor) : "");
   this.currentChar++;
   setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);
 } else {
        this.currentText = "";
        this.currentChar = 0;
       this.running = false;
       this.finishedCallback();
 }
}
</script>
<center>
  <b class="Gre">The-X-Cyber INDONESIA</b>
  <br>
  <font>
</font><p id="message"><font> <strong><br> Selamat datang anjirr awkow :v<br>
bantu subscribe nya njirr -_- <br>
nama channel Thex-X-Cyber :)<br>
<br>nama Tim gue <br>
( The-X-TeaM  : The-X-APMZ : The-X-Cyber )<br>
 <br>
 [ arefm425@gmail.com ]</strong><br>
<br>
[ Author : <span class="ahgcrewstyle"><strong><strong>  M_aref </strong></strong></span><strong> ] <br>
</font></p>
<p align="center"><em>Welcome</em>: <b><font size="3"><span class="ahgcrewstyle">Indonesian The-X-Cyber </span></font></b></p>
<p><font><br>
 <br>
 <p align="center"><font color="red" size="+1" face="Times New Roman"> <br>Terimakasih<br>anjirr<br>sudah subscribe<br>channel<br>The-X-Cyber<br></p>
<div class="fb-like-box" data-href="https://www.facebook.com/IndonesiaFighterCyber" data-width="292" data-show-faces="false" data-stream="false" data-header="false"></div>
<div id="fb-root"></div>
<script>(function(d, s, id) {
 var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/all.js#xfbml=1&appId=384191914936497";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
<p align="center"><font size="+8" face="Times New Roman"><font color="green"> Welcome<font color="white"> The-X-Cyber <font color="red"> INDONESIA</p>
<script>alert('NoFace  Script  html - Click disini');</script>
<p align="center"> <img src="http://www.ashiyane.org/forums/image.php?u=268&dateline=1267790210&type=profile"> </p>
  <script type="text/javascript">
new TypingText(document.getElementById("message"), 50, function(i){ var ar = new Array("\\", "|", "/", "-"); return " " + ar[i.length % ar.length]; });
//Type out examples:
TypingText.runAll();
  </script>
</font></p>
</center></center>
<br>
<div align="center"><img src="http://sarbaz-faz.persiangig.com/Hack/hacked.gif"></div>
</br>
</body></html>
<!-- aghaze larzeshe safhe-->
<meta http-equiv="Content-Language" content="en-us">
<SCRIPT language=JavaScript>
<!-- Begin
function shake(n) {
if (parent.moveBy) {
for (i = 10; i > 0; i--) {
for (j = n; j > 0; j--) {
parent.moveBy(-i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,-i);
parent.moveBy(i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,i);
        }
     }
  }
}
//  End -->
<!--
shake(1);
//-->
</SCRIPT>
<!-- p align="center"><font size="7" color="#FF0000">chi?</font></p> -->
<!--payan--></SCRIPT>
</body>
</html>
</body>
</html>
<P align=center></P>
<body bgcolor="#333366" background="http://iasstes-team.com/p_0001.jpg" text="#FFFFFF" link="#0066CC" vlink="#999999" alink="#993300" style="background-image: url('http://sarbaz-faz.persiangig.com/Hack/meshki.JPG')"><style>
body {
    padding:0;
    margin:0;
    background-image:url(http://iasstes-team.com/p_0001.jpg);
    background-repeat: no-repeat;
    background-position:top;
background-color: black;
color: white;
font: normal 80% Verdana;
margin-top: 0px;
margin-left: 0px;
padding: 0;
margin-right: 0px;
}
td{font-family: verdana; font-size: 20pt; color: green}
a{font-family: verdana; font-size: 20pt; color: silver}
</style>
<center><img src="https://i.ibb.co/JrKfGbr/IMG-20200412-030759.jpg"></center>
<style>
#navbar-iframe {
display: none;
}
<style>
<style type="text/css">
body{
background:url( https://lh3.googleusercontent.com/-bf_x-yTTHjQ/Ts32HIlpUJI/AAAAAAAAAgQ/WctrlVSdVXI/s800/bluematrix.gif ) repeat center center fixed black;
}
</style>

link deface gue :)
http://wx.light2meet.com/uploadfiles/file/20200414/20200414185951_19022.html

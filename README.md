<html class="gr__ShinyGrenade_github_io"><head>
	<link href="https://fonts.googleapis.com/css?family=Chakra+Petch" rel="stylesheet">
	<style>
		.navigation {
			list-style: none;
			margin:0;
			background:#18227c;
			display: -webkit-box;
			display: -moz-box;
			display: -ms-flexbox;
			display: -webkit-flex;
			display: flex;
			-webkit-flex-flow:row wrap;
			justify-content:center;
			
		}
		.navigation a {
			text-decoration: none;
			display: block;
			padding: 1em;
			color:black;
			font-family: 'Chakra Petch', sans-serif;
			font-size:24px;
		}
		.navigation a:hover {
			background:red; 
		}
		@media all and(max-width: 800px){
			.navigation {
				justify-content: space-around;
			}
		}
		@media all and (max-width: 600px){
			.navigation {
				-webkit-flex-flow: column wrap;
				padding: 0;
			}
			.navigation a{
				text-align: center;
				padding: 10px;
				border-top:1px solid rgba(255,255,255,0.3);
				border-bottom: 1px solid rgba(0,0,0,0.1);
			}
			}
		}
					
		}
		
		.picture {
			display:block;
		}
		.container {
			position:relative;
			height:700px;

		}
		.textblock {
			position: absolute;
			background-color:yellow;
			color: white;
			bottom:300px;
			width:100%;
			text-align: center;
			font-size:24pt;
			font-family: 'Chakra Petch', sans-serif;
		}
		.relativee {
			position:relative;
		}
		#content {
			position:relative;
			/*left:50%;*/
			height:200px;


		}

		#egg {
			position:relative;
			display:block;
			left: 50%;
		}

		@media screen and (min-width: 800px) {
			#content {
				position:relative;
		
				height:200px;
				margin:left: 400px;
			}
		}
		.egg_count {
			left:50%;
		}

	
	</style>
<style type="text/css" media="all" id="my">                                                                               
                body {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/arrows/arrow06.png") 1x), auto !important;}              
                input, textarea {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cur/oschrome/text.cur") 1x) , auto !important;}                                              
                input[type="date"], input[type="time"], input[type="datetime-local"], input[type="month"] {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/arrows/arrow06.png") 1x), auto !important;}
                
                textarea {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cur/oschrome/text.cur") 1x), auto !important;}
                
                [type="search"], [type="number"]::-webkit-inner-spin-button, [type="number"]::-webkit-outer-spin-button { cursor:-webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cur/oschrome/text.cur") 1x), auto  !important;}
                 
                [type="search"]::-webkit-search-cancel-button, [type="search"]::-webkit-search-decoration { cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x), auto  !important;}
                
                input::-webkit-contacts-auto-fill-button {cursor: -webkit-image-set(url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/arrows/arrow06.png") 1x), auto  !important;}
                
                :link, :visited {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x ), auto !important;}
                
                a > * {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x), auto !important;}
                               
                input:read-only {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/arrows/arrow06.png") 1x), auto !important; }
                
                button {cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x), auto !important; }

                input:read-write{cursor: -webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cur/oschrome/text.cur") 1x),  auto !important;}
                              
                ::-webkit-resizer {cursor: -webkit-image-set(url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cur/oschrome/resizer.png") 1x), auto !important;}
                
                ::-webkit-scrollbar-button {cursor: -webkit-image-set(url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x),  auto !important;}
                
                ::-webkit-file-upload-button{cursor:-webkit-image-set( url("chrome-extension://ogdlpmhglpejoiomcodnpjnfgcpmgale/assets/cursors/pointers/arrow06.png") 1x),  auto !important;}                
                </style></head>
<body style="margin:0px" data-gr-c-s-loaded="true">
<ul class="navigation">
	<li><a href="#">Home</a></li>
	<li><a href="#">Profile</a></li>
	<li><a href="#">Gallery</a></li>
	<li><a href="#">Random Things</a></li>
</ul>

<div class="container">
	<img class="picture" src="black-bird.jpg" style="width:100%; height:700px;">
	<div class="textblock">
	<h3>“The reasons chickens cannnot fly high because they don't have faith in their wings.”</h3>
	</div>
</div>


 
  <div id="content">
  	<div style="text-align: center;" class="egg_count">0 Taps!</div>
  <div style="text-align: center;">
  	<p style="text-align: center; display: inline;">Multiplier: </p>
  	<spanny style="display:inline; " id="multiplier">1</spanny>	
  </div>
  	<img id="chicken" src="https://stickershop.line-scdn.net/stickershop/v1/product/1082755/LINEStorePC/main.png;compress=true?__=20161019" style="width:150px;" onclick="zoomy()">
  <div style="text-align: center;">	
  	<button onclick="upgrade()">Upgrade<br>[50]</button>
  </div>
  </div>
  <div id="idk" style=" margin-left:  height:100px;"></div>


<p>Eat chickens #KillPapyrus and do't eat his spaghetti.</p>








<script>
function suprise() {
	var egg_count = document.getElementsByClassName("egg_count")[0];
	if (egg_count.innerText.slice(0, -6) > 2000) {
		

		


function zoomy(){

var x = document.getElementById("egg");
var multiplier = document.getElementsByTagName("spanny")[0];
setTimeout(function(){ x.style.width="160px" }, 100);
setTimeout(function(){ x.style.width="150px" }, 150);
createNumbers("+" + multiplier.innerText);
var egg_counts = document.getElementsByClassName("egg_count")[0];
egg_counts.style.fontSize="22px";
egg_counts.innerText = egg_counts.innerText.slice(0, -6)* 1 + multiplier.innerText * 1 + " Taps!";
if (egg_counts.innerText.slice(0, -6) > 50) {
		var video = document.createElement('video');

		



}
function createNumbers(num) {
	var box = document.createElement('div');
	box.innerText = num;
	box.style.fontSize = "25px";
	box.style.color = "black";
	box.style.fontWeight = "bold";
	box.style.position = "fixed";

	box.style.top = Math.random() * 100 + 50 + "vh";
	box.style.left = Math.random() * 100 + "vw";
	box.style.opacity = 1;
	document.getElementById('content').appendChild(box);

	var gone = setInterval (function() {
		if (box.style.opacity == 0.1) {
			clearInterval(gone) ;
			document.getElementById("content").removeChild(box) ;
		}
		box.style.opacity -= 0.1;
	}, 200) ;
	
}
function upgrade() {
	var egg_count = document.getElementsByClassName("egg_count")[0];
	var multiplier = document.getElementsByTagName("spanny")[0];
	var cost = document.getElementsByTagName("button")[0];
	if (egg_count.innerText.slice(0, -6) * 1 >=multiplier.innerText * 25) {

		egg_count.innerText = egg_count.innerText.slice(0, -6) - multiplier.innerText * 25 + " Taps!";
		multiplier.innerText *=2 ;
		cost.innerHTML = "Upgrade<br>(" + multiplier.innerText * 25 + ")";
		cost.style.color = "black";
	
		
	} else {
		cost.style.color = "red";
	}
}




</script>
<embed src="chi.mp3" loop="true" autostart="true" hidden="true">
<pre>	





</pre>
<footer>Copyright: Ryan Lai. Song: Vicetone, Nevada. </footer>


</body></html>

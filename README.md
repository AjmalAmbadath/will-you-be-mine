<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Babe ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
overflow:hidden;
background:black;
color:white;
height:100vh;
}

/* Background */
.bg{
position:fixed;
width:100%;
height:100%;
background:url('https://i.ibb.co/v6yjDymN/pic.jpg') center/cover;
filter:blur(8px) brightness(0.3);
z-index:-2;
}

/* Intro Screen */
.intro{
position:absolute;
width:100%;
height:100%;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
background:rgba(0,0,0,0.5);
z-index:10;
transition:1s;
}

.intro h1{
font-size:3rem;
margin-bottom:20px;
text-align:center;
color:#ffd6e7;
animation:pulse 2s infinite;
}

.open-btn{
padding:15px 40px;
border:none;
border-radius:50px;
font-size:1.2rem;
background:#ff4d88;
color:white;
cursor:pointer;
transition:0.3s;
box-shadow:0 0 20px #ff4d88;
}

.open-btn:hover{
transform:scale(1.1);
}

/* Main Container */
.container{
display:none;
overflow-y:auto;
height:100vh;
padding:40px 20px;
}

.card{
max-width:900px;
margin:auto;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(10px);
border-radius:25px;
padding:30px;
border:1px solid rgba(255,255,255,0.2);
box-shadow:0 0 30px rgba(255,255,255,0.1);
animation:fadeIn 2s;
}

.top-img{
width:180px;
height:180px;
border-radius:50%;
object-fit:cover;
display:block;
margin:0 auto 20px;
border:4px solid rgba(255,255,255,0.5);
box-shadow:0 0 20px rgba(255,255,255,0.4);
}

.title{
text-align:center;
font-size:2.5rem;
margin-bottom:25px;
color:#ffd6e7;
}

.text{
line-height:2;
font-size:1rem;
white-space:pre-line;
}

/* Hearts */
.heart{
position:fixed;
bottom:-20px;
color:#ff4d88;
animation:float linear forwards;
z-index:-1;
}

@keyframes float{
to{
transform:translateY(-110vh);
opacity:0;
}
}

@keyframes pulse{
0%{transform:scale(1);}
50%{transform:scale(1.08);}
100%{transform:scale(1);}
}

@keyframes fadeIn{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.footer{
text-align:center;
margin-top:40px;
font-size:1.6rem;
color:#ffd6e7;
}

audio{
display:none;
}

@media(max-width:768px){

.title{
font-size:2rem;
}

.text{
font-size:0.95rem;
}

.top-img{
width:140px;
height:140px;
}

.intro h1{
font-size:2rem;
}

}

</style>
</head>

<body>

<div class="bg"></div>

<div class="intro" id="intro">
<h1>For My Babe ❤️</h1>
<button class="open-btn" onclick="openLetter()">
Open My Heart 💌
</button>
</div>

<div class="container" id="container">

<div class="card">

<img src="https://i.ibb.co/v6yjDymN/pic.jpg" class="top-img">

<div class="title">
My Love Letter ❤️
</div>

<div class="text" id="typingText"></div>

<div class="footer">
Will You Be Mine Forever? 🕊️❤️
</div>

</div>

</div>

<audio id="music" loop>
<source src="https://files.catbox.moe/m4uoqm.mp3" type="audio/mp3">
</audio>

<script>

const text = `അസ്സലാമു അലൈകും 
കൈഫൽ ഹാൽ 𝖇𝖆𝖇𝖊.....
എങ്ങനെയാ തുടങ്ങേണ്ടത് എന്താ പറയേണ്ടത് എന്നൊന്നും എനിക്ക് അറിയുന്നില്ല..... എന്റെ 25 വയസ്സ് 224 ദിവസത്തിൽ പേര് കൊണ്ട് പോലും പരിചയം ഇല്ലാത്ത ഒരാൾ...... അതിന് തൊട്ടടുത്ത ദിവസത്തിൽ ഒരു ചെറു പുഞ്ചിരിയോടെ എനിക്കൊട്ടും പരിചയം ഇല്ലാത്ത സാഹചര്യത്തിൽ എന്റെ മുന്നിലോട്ട് കടന്ന് വരുന്നു..... 𝖋𝖆𝖙𝖍𝖎𝖒𝖆 𝖆𝖓𝖘𝖎𝖑𝖆......
എന്റെ ജീവിതത്തിലെ ഏറ്റവും പ്രിയപ്പെട്ട എന്റെ ഉമ്മാന്റെ പേരിന്റെ കൂടെ എന്റെ രക്തബന്ധത്തിന്റെ പേര് കൂടെ ചേർത്ത് എന്റെ മുന്നിലോട്ട് വന്ന നിമിഷം...
The very first moment I saw you........
എനിക്കറിയില്ലായിരുന്നു.... എന്റെ ജീവിതാവസാനം വരെ എന്റെ കൂടെ ഉണ്ടാവേണ്ടത് ഈ മുഖമായിരുന്നെന്ന്.... കുറച്ചു ടെൻഷൻ ആയിട്ടാണ് നിന്നോട് സംസാരിച്ചിരുന്നത്... പക്ഷെ നിന്റെ ചിരിയും കണ്ണുകളും എല്ലാം എനിക്ക് ചുറ്റും ഒരു സുരക്ഷവലയം തീർത്തു.....നിന്നോട് അവിടെ നിന്നും യാത്ര പറഞ്ഞു പോവുമ്പോൾ എന്റെ ജീവിതത്തിൽ ഇതുവരെ ഇല്ലാത്ത പുഞ്ചിരിയും ഫീലിങ്‌സും എന്റെ കൂടെ ചേർന്ന് നിന്നു...
അതിന് ശേഷം ഇൻസ്റ്റയിൽ നിന്റെ അക്കൗണ്ട് നോക്കി നിന്റെ മെസ്സേജ് കാത്ത് ഇരുന്ന് അന്നത്തെ രാത്രിയിലെ നമ്മുടെ സംസാരം...... എന്തോ...... ഇത്രയും കാലത്തിനിടക്ക് പടച്ചോൻ എനിക്കായി കാത്തുവെച്ച ഏറ്റവും വലിയ നിധി നീ ആണെന്ന് എന്നിൽ എവിടെയോ അലയടിക്കുന്നുണ്ടായിരുന്നു...... പിന്നീട് നിന്നോടുള്ള സംസാരങ്ങളെല്ലാം എന്റെ ഹൃദയത്തോട് ചേർന്നതായിരുന്നു....പിറ്റേ ദിവസം രാത്രി നിന്റെ കോളേജിലേക്ക് നിന്നെ കാണാൻ വന്ന നിമിഷം....
ഒരു ഇളം പ്രകാശത്തിൽ ചെറിയ ചാറ്റൽ മഴയിൽ അതീവ സുന്ദരിയായി നിന്നെ കണ്ട ആ mσmєnt..... 
í fєll ín lσvє wíth чσu dєαr♥️..... അതിന് ശേഷമുള്ള എന്റെ നിമിഷങ്ങൾ എല്ലാം ഒരു സ്വപ്ന ലോകത്ത് ആയിരുന്നു...... അതിലെ എന്റെ രാജകുമാരി നീ ആയിരുന്നു.....
mч líttlє príncєѕѕ.....
നിന്നോടുള്ള സംസാരങ്ങൾ എല്ലാം എന്തോ നമ്മൾ തമ്മിൽ എത്രയോ വർഷങ്ങൾ പഴക്കമുള്ള പോലെ തോന്നി....
എന്റെ വാരിയെല്ലിലും നിന്നും പടച്ചോൻ പടച്ച് വിട്ടത് നിന്നെ തന്നെ ആണോ.....?
ചുരുങ്ങിയ സമയം കൊണ്ട് തന്നെ നിന്നെ കാണണം നിന്നോട് സംസാരിക്കണം എന്ന ആഗ്രഹം വല്ലാതെ കൂടി കൊണ്ടിരുന്നു..... ഒരുപാട് കാര്യങ്ങളിൽ ഒരുപോലെ ഇഷ്ടങ്ങളോടെ ജീവിക്കുന്നവർ... ഒരുപോലെ ഉള്ള സാഹചര്യങ്ങളിൽ നിന്നും ജീവിച്ചു വന്നവർ.... സമാനതകളില്ലാത്ത സാമ്യങ്ങൾ അല്ലെങ്കിലും ഒരു പരിതിവരെ എന്റെ ഒരു female വേർഷൻ ഞാൻ നിന്നിൽ കാണുന്നുണ്ടായിരുന്നു....എന്റെ ചളികളോടൊപ്പം കട്ടക്ക് നിൽക്കുന്ന...എന്റെ മണ്ടത്തരത്തിന് ചിരിച് തരുന്ന....
ഇന്നലെ നമ്മൾ സംസാരിച്ച അവസാനം നിന്റെ കണ്ണ് നിറഞ്ഞപ്പോൾ...... ചിരിച് മാത്രം കണ്ടിട്ടുള്ള നിന്റെ മുഖത്തിൽ ആദ്യമായി ഒരിറ്റ് കണ്ണുനീർ വന്നപ്പോ എനിക്ക് എന്തെന്നില്ലാതെ സങ്കടമായി......
സന്തോഷം കൊണ്ടല്ലാതെ ഇനി നിന്റെ കണ്ണ് നിറയരുതെന്ന് ഞാൻ വല്ലാതെ ആഗ്രഹിക്കുന്നു.....
തമ്മിൽ പിണങ്ങി പോവല്ലേ...നമ്മക്ക് നാം തന്നെ അല്ലെ.....

ഒരുപക്ഷേ ഞാൻ perfect ആയ മനുഷ്യൻ ആവില്ല.....
deserve ചെയ്യുന്ന രീതിയിൽ എല്ലായ്പ്പോഴും സ്നേഹിക്കാനും പറ്റാതെ വന്നേക്കാം.....
പക്ഷെ ഒരു കാര്യം ഉറപ്പാണ്.....
ഈ ലോകത്ത് ആരേക്കാളും കൂടുതൽ care ചെയ്യുന്നത് നിന്നെയായിരിക്കും.....

എന്റെ ജീവിതത്തിലെ സന്തോഷങ്ങളിലും സങ്കടങ്ങളിലും....

 ഉയർച്ചയിലും താഴ്ചയിലും.....

എന്നോടൊപ്പം ചേർന്ന് നമ്മുടെ success ലേക്ക് ഒരുമിച്ച് നടന്നു നീങ്ങാൻ.....

 എന്നോടൊപ്പം എന്റെ ജീവിതത്തിലെ ഏറ്റവും വലിയ സന്തോഷമായി മാറാൻ......

എന്റെ ജീവിതത്തിലെ എന്റേത് മാത്രമായി എനിക്ക് അവകാശപ്പെടാൻ......
ഞാൻ, നീ എന്ന് ആയിരുന്നത് നാം ആയി മാറാൻ.....

നിന്റെ കൈ പിടിച്ച് ജീവിതം മുഴുവൻ നടക്കാൻ.....

എന്റെ ѕαfє, എന്റെ pєαcє, എന്റെ hσmє എന്ന് എനിക്ക് അവകാശപ്പെടാൻ....

ഒരുപാട് ആളുകൾ വന്നുപോകുന്ന ജീവിതത്തിൽ
എനിക്ക് forever ആയി സൂക്ഷിക്കാൻ...

എന്റെ ജീവിതത്തിൽ ഞാൻ നഷ്ടപ്പെടുത്താൻ ആഗ്രഹിക്കാത്ത ഏറ്റവും വിലപ്പെട്ട ഡയമണ്ട് ആവാൻ.....

നമ്മൾ തമ്മിൽ എത്ര distance വന്നാലും
എത്ര problems വന്നാലും
ഒരിക്കലും കൈവിടാതെ
നിന്റെ കൈ കോർത്തു എന്റെ ജീവിതാവസാനം വരെ നടന്നു നീങ്ങാൻ....

wíll чσu вє wíth mє fσrєvєr mч вαвє......

Beacause.....

í juѕt wαnt чσu.....
чσur lσvє.....
чσur hαnd ín mínє.....
αnd α lífєtímє wíth чσu.....
í dσn't juѕt lσvє чσu...
í wαnt tσ lívє mч whσlє lífє wíth чσu.....🕊️♥️`;

let i = 0;

function typeWriter(){
if(i < text.length){
document.getElementById("typingText").innerHTML += text.charAt(i);
i++;
setTimeout(typeWriter,30);
}
}

function openLetter(){

document.getElementById("intro").style.opacity="0";

setTimeout(()=>{
document.getElementById("intro").style.display="none";
document.getElementById("container").style.display="block";
typeWriter();
},1000);

document.getElementById("music").play();

}

/* Floating hearts */

function createHeart(){

const heart = document.createElement("div");

heart.classList.add("heart");

heart.innerHTML = "♥";

heart.style.left = Math.random()*100 + "vw";

heart.style.fontSize = Math.random()*20 + 15 + "px";

heart.style.animationDuration = Math.random()*3 + 4 + "s";

document.body.appendChild(heart);

setTimeout(()=>{
heart.remove();
},7000);

}

setInterval(createHeart,250);

</script>

</body>
</html>

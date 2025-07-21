# DOM_Manipulation
document.body.style.backgroundColor = "Lightblue";
'Lightblue'
let img = document.createElement("img");
undefined
img
<img>​
img.style.width = "100 vw";
'100 vw'
console.log(img);
VM609:1 <img>​
undefined
img.src = "https://m.media-amazon.com/images/I/71N3x0uQObL._SL1500_.jpg";
'https://m.media-amazon.com/images/I/71N3x0uQObL._SL1500_.jpg'
img.style.height = "50vh";
'50vh'
img.style.objectFit = "cover";
'cover'
img.style.display = "block";
'block'
img.style.margin = "0 auto";
'0 auto'
document.body.appendChild(img);
<img src=​"https:​/​/​m.media-amazon.com/​images/​I/​71N3x0uQObL._SL1500_.jpg" style=​"height:​ 50vh;​ object-fit:​ cover;​ display:​ block;​ margin:​ 0px auto;​">​
let heading = document.createElement("h1");
undefined
heading.textContent = "Welcome to my Dynamic Page";
'Welcome to my Dynamic Page'
heading.style.color = "black";
'black'
heading.style.textAlign = "center";
'center'
heading.style.fontSize = "2.5 rem";
'2.5 rem'
heading.style.marginTop = "20px";
'20px'
document.body.appendChild(heading);
<h1 style=​"color:​ black;​ text-align:​ center;​ margin-top:​ 20px;​">​Welcome to my Dynamic Page​</h1>​
let para = document.createElement("p");
undefined
para.textContent = "This page is fully created using Javascript in the console!";
'This page is fully created using Javascript in the console!'
para.style.color = "#ddd";
'#ddd'
para.style.fontSize = "1.2 rem";
'1.2 rem'
para.style.textAlign = "center";
'center'
para.style.maxWidth = "600px";
'600px'
para.style.margin = "20px auto";
'20px auto'
para.style.lineHeight = "1.6";
'1.6'
document.body.appendChild(para);
<p style=​"color:​ rgb(221, 221, 221)​;​ text-align:​ center;​ max-width:​ 600px;​ margin:​ 20px auto;​ line-height:​ 1.6;​">​This page is fully created using Javascript in the console!​</p>​
para.style.color = "#7FFF00";
'#7FFF00'
para.style.color = "#00008B";
'#00008B'
let button = document.createElement("button");
undefined
button.textContent = "Click Me";
'Click Me'
button.style.display = "block";
'block'

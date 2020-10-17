
<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<body>


Eine Methode ist eine Funktion,
die als Eigenschaft gespeichert ist.
Methoden sind Aktionen ,
die für Objekte ausgeführt werden können.
break:
Beendet einen Schalter oder eine Schleife

continue:	
Springt aus einer Schleife und beginnt oben

debugger:
	Stoppt die Ausführung von JavaScript und ruft (falls verfügbar) die Debugging-Funktion auf
	
do ... while:	
Führt einen Anweisungsblock aus und wiederholt den Block, während eine Bedingung erfüllt ist

for	:
Markiert einen Block von Anweisungen, die ausgeführt werden sollen, solange eine Bedingung erfüllt ist

function	:
Deklariert eine Funktion

if ... else:	
Markiert einen Block von Anweisungen, die abhängig von einer Bedingung ausgeführt werden sollen

return:	
Beendet eine Funktion

switch:	
Markiert einen Block von Anweisungen, die abhängig von verschiedenen Fällen ausgeführt werden sollen

try ... catch:	
Implementiert die Fehlerbehandlung in einen Anweisungsblock

var:	
Deklariert eine Variable



<h1> Arrays</h1>
Beschreibung: arrays dienen dazu einer Variablen mehrere Werte zugeben.
wichtig: Bei Arrays wird ab 0 angefangen zu zählen
Beispiel: var variable=[wert1,wert2,wert3];
window.alert(Variable[0]
Ausgabe: wert1 wird ausgegeben



<h2>Variable.length()</h2> 
Beschreibung: wiedergabe der Array Anzahl in  einer Variable.
Beispiel:(Variable.length)
Ausgabe: Anzahl 3

<h2>variable.push()</h2>
Beschreibung: fügt einen wert der variable hinzu.
Beispiel: variable.push("wert4"); = variable=[wert1,wert2,wert3,wert4]
window.alert(variable[3]);
Ausgabe:wert4


<h2> variable.join()</h2>
Beschreibung: ersetzt das Komma zwischen den Werten von Arrays
Beispiel:variable.join("+");
Ausgabe: wert1+wert2+wert3+wert4


<h2>variable.shift()</h2>
Beschreibung: löscht den ersten Wert eines Arrays
Beispiel:variable.shift

<h2>variable.unshift()</h2>
Beschreibung:fügt einen wert an den start eines Arrays
Beispiel: variable.unshift("wert0");
Ausgabe:wert0,wert1,wert2,etc..

<h2>variable.sort()</h2>
Beschreibung: sortiert die Werte im Array nach dem alphabeth
Beispiel: variable.sort()

<h2>variable.reverse</h2>
Beschreibung: gibt die Werte der Variable rückwärts wieder
Beispiel:variable.reverse()
Ausgabe: wert4,wert3,wert2,wert1

<h1>Schleifen/loops</h1>
Beschreibung:dient zur Wiederholung von Funktionen
Wichtig:Funktion sollte irgendwann enden sonst kommt es zur Endlosschleife
Beispiel:var=0;


<h2>for schleife</h2>
Beschreibung:
i=0;variable ist auf 0
i<5;variable ist kleiner als 5
i++; variable wird bei jedem durchlauf um eins erhöht
Beispiel:
for(i=0;i<5;i++){
window.alert(i)};
Ausgabe: 0-4

<h2>for in schleife</h2>
Beschreibung:
kurzschreibweise der for schleife für Arrays
Beispiel:
var beispiel =[1,2,3]
for(i in beispiel){
window.alert(beispiel[i];}

<h2> while schleife</h2>
Beschreibung:Funktion wird ausgeführt solange die bedingung stimmt
Beispiel: 
while (i<5){window.alert(i)++};
Ausgabe:0-4


<h2>do while schleife</h2>
Beschreibung:funktion wird einmal ausgeführt bevor sie überprüft wird
Beispiel: 
do{window.alert(i);
i++;
}while(i<0);)
Ausgabe:0

<h2>break</h2>
Beschreibung: überspringt alle werte von array
beispiel:


<h2>continue</h2>
Beschreibung: überspringt einen wert vom array

<h2> function(){}</h2>
Beschreibung:führt eine Funktion aus
Beispiel:
function beispiel(){
window.alert("beispielsatz")};
beispiel();
Ausgabe:beispielsatz

<h2>parameter</h2>
Beschreibung: fügt variablen einer funktion hinzu
Beispiel:
function beispiel(a,b){
window.alert(a+b);}
beispiel(5+4);
Ausgabe:9

<h2>return</h2>
Beschreibung:
gibt den wert von einer funktion zurück
Beispiel:
function beispiel(a,b){
<strong>return</strong> a+b;}
var x= beispiel(5+4);
window.alert(x);
Ausgabe:9

<h2>events</h2>
Beschreibung: lösen eine bestimmte funktion aus
event arten:
onchange: ändert ein html element
onclick:ändert ein hmtl elemement durch einen klick	
onmouseover:ändert ein html element wenn man die maus drüber hält	
onmouseout:	ändert ein html element wenn man die maus wegbewegt 
onkeydown: ändert ein html element durch drücken einer taste	
onload	The browser has finished loading the page
Beispiel:
<button onclick="myFunction(a,b);">
</button>
<button onclick="myFunction();">
   Click here
</button>

<h2>Document object model</h2>
Beschreibung: kann auf elemente zugreifen und sie verändern
Beispiel:
<h5 id="test" onclick="meinefkt()">eine </h5>
function meinefkt(){
document.getElementById("test").innerHTML="TEST";
}


<h2>dom CSS</h2>
fuction beispiel(){
document.getElementById("idname").style.color="pink";}


<h2>dom animation</h2>
fuction beispiel(){
document.getElementById("idname").style.color="pink";
var add=0;
var id=setInterval(function(){
if (add >=500){
clearInterval(id);
}
},5);
}
<h2>this</h2>
Beschreibung: wiederverwendbare funktion zum einfügen
Beispiel:
<p <<id="idname" onclick="funktionname(this)"|> beispiel</p>
<p onclick="funktionname(this)">beispiel 2</p>
<p onclick="meinevent(this)"> beispiel3 </p>

function funktionname(element){
element.innerHTML="beispiel name ändert sich";}


<h2>createElement</h2>
Beschreibung: erstellt und fügt ein element hinzu
Beispiel:
function funktionname(){
var=document.getElementById("id name"};
var para=document.createElement("elementname");
para.innerHTML="neuer inhalt vom element";}
x.appendChild(para);}

<h2>objekte</h2>
beschreibung:

Beispiel:

function (){

var objektname={
eigenschaft1:"eins",
eigenschaft2:"zwei"
};
window.alert(objektname.eigenschaft1);
}
ausgabe: eins

<h2>konstruktor</h2>
beschreibung:

Beispiel:
function Beispiel(){
function auto(marke, farbe, kmh){
this.marke=marke;
this.farbe=farbe;
this.kmh=kmh;
}
var auto1= new auto("volvo",blau, 130);
var auto2= new auto("opel", gelb,120);
Window.alert(auto1.marke);
ausgabe:volvo
</body>
</html>

function poniedzialek(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 1){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}

function wtorek(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 2){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}

function sroda(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 3){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}



function czwartek(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 4){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}



function piatek(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 5){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}



function sobota(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 6){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}



function niedziela(){
var tabela = [];
var wyniki = 0;
 dzien = document.getElementById("dzien").value;
 miesiac = document.getElementById("miesiac").value -1;
 rok1 = document.getElementById("rok1").value;
 rok2 = document.getElementById("rok2").value;
	for(i = rok1; i<=rok2; i++){
		var d = new  Date(i, miesiac, dzien);
			if (d.getDay() === 0){ 
			tabela.push(i);			
}
}wyniki = tabela.toString();
document.getElementById("wynik").innerHTML = wyniki;
}

















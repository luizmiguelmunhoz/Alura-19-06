function  calculaTempo(tempoObjetivo) {
let tempoAtual = new Date ();
let minutos = Math.floor(segundos  / 60);
let horas = Math.floor (minutos  / 60);
let dias = Math.floor (horas/24);

segundos %= 60;
minutos %= 60;
horas %= 24;
if (tempoFinal > 0 ){
     return [dias,horas,minutos,segundos];
  } else {   
      return [0,0,0];
  }
}

function atualizaCronometro(){
  document.getElementByID("dias0").textContent = CalculaTempo(tempos[1])[0] ;
  document.getElementByID("horas0").textContent = CalculaTempo(tempos[1])[1] ;
  document.getElementByID("min0").textContent = CalculaTempo(tempos[1])[2] ;
  document.getElementById("seg0").textContent = CalculaTempo(tempos[1])[3] ;
  for (let i=0; i<contadores.length;i++){
    //  contadores [i].textContent = CalculaTempo(tempos[i]);
    }
    {
    function comecaCronometro (){
     atualizaCronometro ();
     

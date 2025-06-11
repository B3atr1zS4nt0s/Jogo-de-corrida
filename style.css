function setup() {
  createCanvas(400, 400);
}

let xJogador = [0, 0, 0, 0, 0];
let yJogador = [60, 130, 210, 290, 370];
let jogador = ["🐭", "🐨", "🐼", "🐺", "🐰"]
let teclas = ["a", "b", "m", "l", "c"];

function draw() {
  ativaJogo();

  desenhaJogadores();

  desenhaLinhaDeChegada();

  verificaVencedor();
}

  function ativaJogo() {
    if (focused == true) {
      background("#91D83F");
    } else {
      background("rgb(190,46,46)");
    }
  }

  function desenhaJogadores() {
    textSize(40);
    for (let i = 0; i< 5; i++) {
      text(jogador[i], xJogador[i], yJogador[i]);
    }
  }

  function desenhaLinhaDeChegada() {
   fill('white');
    rect(350, 0, 10, 400);
    fill('black');
    for (let yAtual=0; yAtual < 400; yAtual += 20){
        rect(350, yAtual, 10, 10);
    }
  }
  
   function verificaVencedor() {
    for (let i = 0; i < 5; i++) {
      if (xJogador[i] > 350) {
        text(jogador[i] + " venceu! ", 90, 200);
        noLoop();
      }
    }
   }  

function keyReleased() {
 for (let i = 0; i < 5; i++){
   if (key == teclas[i]){
     xJogador[i] += random(20);
   }
 }
}

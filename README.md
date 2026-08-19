1
nomes = ["Pedro","Lucas","Maria","Laura"];

i=0;
while( i < nomes.length){
    console.log(nomes[i]);
i = i + 1;
}
console.log("Fim");

2
nros = [18,14,21,15];
 i = 0;
 soma = 0;

 while( i < nros.length){
    soma = soma + nros[i];
    i = i + 1;
 }
 console.log(soma);


 3
 let nros = [32, 12, 58, 40];
let i = 0;
let soma = 0;
while( i < nros.length ){
    soma = soma + nros[i];
    i = i + 1;

}
let media = soma / nros.length;
console.log (`Média: ${media}`);

4

let nros = [32, 12, 58, 40, 23, 56];
let i = 0;
let maior = nros[i];
while( i < nros.length ){
   
if(maior < nros[i] ){
    maior = nros[i];

}
i = i + 1;
}
console.log (`Valor: ${maior}`);

5

let nros = [32, 12, 58, 40, 23, 56];
let i = 0;
let menor = nros[i];
while( i < nros.length ){
   
if( menor > nros[i] ){
    menor = nros[i];

}
i = i + 1;
}
console.log (`Valor: ${menor}`);


JASON

{
  "name": "aluno",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "um": "node ./src/um",
    "dois": "node ./src/dois",
    "tres": "node ./src/tres",
    "quatro": "node ./src/quatro",
    "cinco": "node ./src/cinco"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "type": "commonjs",
  "dependencies": {
    "prompt-sync": "^4.2.0"
  }
}

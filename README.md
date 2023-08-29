const bool1 = true
const bool2 = false
const bool3 = !bool2
let resultado = bool1 && bool2
console.log("a. ", resultado)
resultado = bool1 && bool2 && bool3
console.log("b. ", resultado)
resultado = !resultado && (bool1 || bool2)
console.log("c. ", resultado)
console.log("d. ", typeof resultado)

//a. false
// b.false
 //c.true
 //d. boolean

 //2.
 //let primeiroNumero = prompt("Digite um numero!")
//let segundoNumero = prompt("Digite outro numero!")
//const soma = primeiroNumero + segundoNumero
//console.log(soma)

// sera impresso os dois numeros digitados no console sem a soma..

//3.
//let primeiroNumero = prompt("Digite um numero!")
//let segundoNumero = prompt("Digite outro numero!")
//const soma = Number (primeiroNumero) + Number (segundoNumero)
//console.log(soma)

//
//let idade = Number(prompt("qual sua idade?"));
//let idadeAmigo = Number(prompt("qual a idade do seu melhor amigo?"));
//console.log("sua idade é maior que a do seu amigo?", (idade <=idadeAmigo));
//console.log("a diferença das nossas idades é:", (idade - idadeAmigo));

//2
//let numero =Number(prompt("ensira um numero par"));
//console.log ( numero % 2); 
//numero que é dividido  por 2 é igual a 0 
//ah nao ser que seja um numero impar

3//
let meses = Number(prompt("idade em anos"));
console.log("SUA IDADE EM MESES É;", meses *56);




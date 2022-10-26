# Projetos-em-sala-de-aula

console.log ('esse é um programa que lê o imc')

let peso = 80 
let altura = 1.80

let imc = peso/(altura*altura)

console.log ('seu imc é:' + imc)

if (imc > 30) {

    console.log('peso pesado')
}

else if(imc >= 25 || imc <= 30) {
    console.log('ta gordinho')
}

else if(imc >= 19 || imc <25) {

    console.log('normalzao')
}

else if (18 < imc) {
    console.log('chasi de grilo')

}

# Projetos-em-sala-de-aula

const fs = require('fs')

console.log('tempo que leva para gravar uma memória na RAM')

const timeOne = new Date ()
let a = 'ocupado memoria'
const timeSecond = new Date ()

console.log('Diferença entre os tempo')

console.log(timeSecond.getTime() - timeOne.getTime() + " ms")


console.log('tempo que leva para criar uma memória no disco rigido')

const timeTheree = new Date()

fs.writeFileSync('myfile','ocupado memoria')

const timeFour  = new Date()

console.log(timeFour.getTime() - timeTheree.getTime() + "ms")

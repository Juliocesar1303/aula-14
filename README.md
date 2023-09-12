// // Julio cesar

// aula sobre condicionais

//let condicao1 = true;
//if (condicao1){
   // console.log('Entrei no if 1!');
////}

// condicao2 = false;
//if (condicao2){
   // console.log('Entrei no if 2!');
//}


//let condicao = false 

//if (condicao){
  //  console.log('entrei no if!')
//} else {
 //   console.log('entrei no else!')
//}

//function comparaNumeros(a,b) {
    //if(a === b){
   //    return "iguais"
   // }
   // } else {
   // return "diferentes"
//}

//console.log(comparaNumeros(
//    Number(prompt('digite o primeiro numero')),
 //   Number(prompt('digite o segundo numero'))
//));

//let condicao9 = false 
//let condicao5 = true

//if (condicao9){
  //  console.log('entrei no if 9!')
//} else {
  //  if (condicao5){
       //  console.log('entrei no if 5!')
    //}
//}



//let condicao1 = false
//let condicao2 = false 
//
//if (condicao1){
  //  console.log('entrei no if 1!')
//} else if (condicao2){
  //  console.log('entrei no if 2!')
//} else {
  //  console.log('entrei no else!')
//}


// function comparaNumeros(a,b) {
//     if(a === b){
//        return "iguais"
//     } else if(a >) {
//     return "diferentes"
// }

// console.log(comparaNumeros(
//     Number(prompt('digite o primeiro numero')),
//     Number(prompt('digite o segundo numero'))
//  ));
// }
let paisDeOrigem 
if (paisDeOrigem === 'Brasil'){
    console.log('Brasileiro')
}else if (paisDeOrigem ==='EUA'){
    console.log('NORTE AMERICANO')
}else if (paisDeOrigem === 'INGLATERRA'){
    console.log('ingles')
}else if (paisDeOrigem === 'frança'){
    console.log('Françes')
}else if (paisDeOrigem === 'italia'){
    console.log('italiano')
}else if (paisDeOrigem === 'canáda'){
    console.log('canadense')
}else {
    console.log('nacionalidade não encontrada')
}

switch (paisDeOrigem){
    case 'Brasil':
    console.log('Brasileiro')
    break
    case 'EUA':
    console.log('norte americano')
    break
    case 'inglaterra':
        console.log('ingles')
        break
        default : 
        console.log('nacionalidade não encontrada')
        break

}

let PokemonUltra = prompt("Digite um pokemon")

switch (PokemonUltra){
    case 'Virizon':
    console.log('planta e veneno')
    break
    case 'Reshiram':
    console.log('Fogo')
    break
    case 'Bubble Beam':
        console.log('Água')
        break
        default : 
        console.log('nacionalidade não encontrada')
        break

}

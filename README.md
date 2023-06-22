# JS-Test
Testando prompt no JS

const idade = Number(prompt( "Qual sua idade"))

if (idade < 16){ 
console.log(`Você tem ${idade} anos, e não é permitido votar`)
}
else if (idade >= 16 && idade <18){
 console.log(`Você tem ${idade} anos, o voto é permitido mas não obrigatório`) 
}
else if(idade >= 18 && idade <65){
  console.log(`Você tem ${idade} anos,  o voto é obrigatório`)
}
else {console.log(`Você tem ${idade} anos, o voto não é obrigatório`)}

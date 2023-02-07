# Exercício-Java
 Here's an exercise I'm practicing during a course, and I'll post more progress. Thanks

const nome = 'Vinicius do Nascimento';
const sobrenome = 'Vergilio';
const idade = 27;
const peso = 80;
const alturaEmM = 1.70; 
let indiceMassaCorporal; 
let anoNascimento;
 
indiceMassaCorporal = peso / (alturaEmM * alturaEmM);
anoNascimento = 2023 - idade;
 
console.log(`${nome} ${sobrenome} tem ${idade} anos, pesa ${peso} kg`);
console.log(`tem ${alturaEmM}m de altura e seu IMC é de ${indiceMassaCorporal}`);
console.log(`${nome} nasceu em ${anoNascimento}.`);

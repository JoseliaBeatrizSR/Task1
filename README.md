# Task1
let tabela = "create table author (id number, name string, age number, city string, state string, country string)";

let tableName = tabela.substr(12,7);

console.log(tableName);

columns = tabela.substr(19);

columns = columns.replace(/[()]/g, ' ');

columns = columns.split(',');

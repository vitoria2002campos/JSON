# JSON
BREVE EXPLICAÇÃO DO QUE É O JSON 


Json  = Javascript Object Notation
Um formato de representacao de dados
Mais simples que XML , que é utilizado para fins parecidos
Utiliza o formato de chave e valor
É leve para ser enviado por requisições
Muito utilizado para API e também arquivos de configuração 

TIPOS DE DADOS 
O Json aceita diversos tipos de dados
Strings  -  "OLA MUNDO";
Números 123;
Arrays  - [1,3,4,5,6];
Objetos - {"nome": "Matheus"};
Dados Nulos - null;

COnvertendo um json para um objeto valido: 
const objData = JSON.parse(jsonData);

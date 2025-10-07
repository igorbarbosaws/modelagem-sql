# Tipos de Dados e Regras na modelagem SQL <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="30px">
Neste artigo desempenhamos uma pesquisa, para descrever os diferentes tipos de dados existentes no Banco de Dados SQL e as regras da sua Modelagem. 

## Dentre os diferentes tipos de dados usados em Bancos de Dados SQL, podemos citar:

**Numéricos** - INT (número inteiro), DECIMAL (número com casa decimais); 

**Strings** – VARCHAR (texto de comprimento variável); 

**Data e Hora** – DATE, DATETIME; 

**Binários** - Para armazenar dados binários 

### Dados Numéricos
São informações expressas como números, que podem ser medidos, contados e usados para realizar operações aritméticas e análises estatísticas. São divididos em dados discretos, como número de itens (ex: 5 alunos), e dados contínuos, que podem ter valores fracionados (ex: 2,5km de distância). 

<img src="https://cdn1.gnarususercontent.com.br/1/403201/43ed5b0b-71da-449b-b8ee-ea982af4970b.png" width="300px">

### Dados Strings
São sequência de caracteres alfanuméricos (letras, números e símbolos) usadas para armazenar informações textuais, como nomes, endereços ou senhas. Esse tipo de dado é fundamental para trabalhar com texto, é delimitado por aspas simples ou duplas, sendo usado em operações como busca, concatenação (junção de strings) e formatação. 

<img src="https://consultabd.wordpress.com/wp-content/uploads/2024/03/str_agg_img02.jpg" width="300px">

### Dados de Data e Hora
Tipos de dados estruturados usados para armazenar informações temporais, como datas e horários, permitindo consultas, classificações e análises baseadas no tempo de forma eficiente. Existem diferentes tipos para armazenar apenas a data (DATE), apenas a hora (TIME) ou a combinação de ambos (DATATIME). 

<img src="https://macoratti.net/14/06/tsql_tdh17.gif" width="300px">

### Dados Binários
Tipo de informação representada na sua forma mais fundamental, ou seja, como uma sequência de “uns” e “zero” (bits), que um computador pode processar. Eles incluem não apenas números e textos, mas também formatos complexos como arquivos de imagens (JPEG ou PNG), arquivos de áudio (MP3) ou vídeo (MOV), permitindo que o banco de dados armazene ou gerencie eficientemente dados que não se encaixam facilmente em formatos tradicionais. 

<img src="https://i.sstatic.net/9lPug.png" width="300px">

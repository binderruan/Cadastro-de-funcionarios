# Cadastro-de-funcionarios

1. Executar comando <br />
npm install nodemon express express-handlebars mysql

2. Criar usuario no mysql<br />
CREATE USER 'ruan'@'localhost' IDENTIFIED BY 'binderruan';
ALTER USER 'ruan'@'localhost' IDENTIFIED WITH mysql_native_password BY 'binderruan';
GRANT ALL PRIVILEGES ON * . * TO 'ruan'@'localhost';
flush privileges;

3. Criar database RH<br />
create database rh;

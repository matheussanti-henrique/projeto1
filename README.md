CREATE TABLE empresas (
    id INT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    email VARCHAR(100) UNIQUE,
    whatsapp BIGINT,
    endereco VARCHAR(100)
);
insert into empresas values(1,"Papelaria Status", "xeroxgtba@gmail.com", 41997772844,);
insert into empresas values(2,"vidapousada", "@pousadavivaguaratuba", 41991112043);
insert into empresas values(3 ,"vidapousada", "@pousadavivaguaratuba", 41991112043);
select * from empresas;

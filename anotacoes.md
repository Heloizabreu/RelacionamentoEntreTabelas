Atividade de SQL – Biblioteca da Escola 📚
Fiz essa atividade prática em SQL para entender melhor como funcionam os JOINs (INNER JOIN e LEFT JOIN), as consultas relacionais e a regra de integridade de dados no banco.

Criei a tabela
![alt text](image.png)

Coloquei todos os nomes
![alt text](image-1.png)

Para visualizar a tabela
![alt text](image-2.png)

Mostra todos os alunos cadastrados
![alt text](image-3.png)

Coloca os que fizeram emprestimo de livro primeiro
![alt text](image-4.png)

Tentativa de inserir um empréstimo para um aluno inexistente
![alt text](<Captura de tela 2026-10-08 100232.png>)
O que aconteceu? O banco de dados barrou a inserção e deu um erro de violação de Chave Estrangeira (foreign key constraint).   Por quê? O campo id_aluno é uma chave estrangeira ligada à tabela de alunos. O banco não aceita registrar um empréstimo para alguém que não existe no cadastro, garantindo que os dados fiquem sempre corretos.   
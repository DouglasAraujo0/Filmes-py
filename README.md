# **FILMES**


O CRUD de Filmes é um programa que realiza operações fundamentais em uma base de dados de filmes. Ele permite criar (Cadastrar) novos registros de filmes com informações como Gênero, Nome e Duração e Sinopse. Além disso, é possível visualizar (Visualizar) a lista completa de filmes cadastrados, atualizar (Atualizar) informações específicas de um filme existente e excluir (Excluir) filmes da biblioteca. 


# PASSO A PASSO

1 - Colocar no terminal:
<p>
    
    pip install oracledb
    pip install pwinput
</p>

2 - Colocar suas permissões no SQL Developer
<p>
    
    OBS: também substituir no código as mesmas permissões nos campos determinados
</p>


3 - Criar a tabela no SQL Developer

    drop table FILMES cascade constraints
    CREATE TABLE FILMES (
    ID NUMBER GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
    GENERO_FILME VARCHAR2(100),
    NOME_FILME VARCHAR2(255) NOT NULL,
    DURACAO NUMBER,
    SINOPSE VARCHAR2(200)
    );


4 - Entrar no programa com as mesmas permissões do SQL Developer

5 - Executar o programa

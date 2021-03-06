# TRABALHO 01 : Academia de Musculação
Trabalho desenvolvido durante a disciplina de BD

# Sumário

### 1	COMPONENTES<br>

Douglas Campos Sutil

Lucas Dipré Pereira

### 2	INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto do banco de dados de uma Academia de Musculação, que tem como objetivo modelar um sistema de criação, monitoramento e registro de exercícios fisicos para os alunos de uma academia, visando otimizar os treinamentos de acordo com as necessidades do aluno com um acompanhamento mais próximo do professor por meio das informações obtidas nos treinos <br>
      
### 3	MINI-MUNDO<br>
O “Academia Monstrão” é um software de gestão de exercícios de academia preparado para gerir e fiscalizar todas as séries de exercícios recomendadas para os frequentadores da academia. Com interfaces amigáveis e de fácil uso para criação de séries, é possível também controlar turmas com quantidades específicas de alunos por horários.

Além disso, o “Academia Monstrão” possui módulos específicos para atender diferentes necessidades. As ferramentas de montagem de treinos, por exemplo, são práticas e ajudam a proporcionar um atendimento de qualidade, com um gasto de tempo muito menor, enquanto você amplia o relacionamento com seus alunos por meio dos aplicativos integrados às atividades desenvolvidas na academia.

O sistema possui 4 tipos diferentes de categorias de usuários: Recepção,Aluno,Instrutor e Médico.

O usuário do tipo “Recepção”, entrará com as informações de cadastros iniciais do aluno.

A categoria “Aluno” terá acesso à série recomendada, histórico de evolução dos exercícios, histórico de mudanças das medidas do seu corpo, além da possibilidade de inserir espécies de anotações nos exercícios praticados naquele determinado dia (peso e repetições praticadas naquele dia).

Já o “Instrutor” poderá criar/editar/visualizar as séries de exercícios de todos os seus “Alunos”, além do acesso ao histórico para o monitoramento da evolução do mesmo.

O “Médico” basicamente irá inserir as métricas do aluno, além de apontar as restrições que cada um terá.

Dentro da academia, o “Academia Monstrão” funciona sem depender da velocidade ou estabilidade da internet. Assim, é possível manter o software de gestão de exercícios sempre ativo, com ou sem conexão. Mas é possível também acessar o sistema de qualquer lugar, com um aplicativo que se conecta com o servidor da academia, basta estar conectado a uma rede.

### 4	RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>


![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20de%20Cadastro%20do%20Aluno.png)
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20de%20Login%20do%20Aluno.png)
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20de%20Treino%20Usuario.png)
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20de%20Exame%20do%20M%C3%A9dico.png)
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20do%20Professor%20de%20Cria%C3%A7%C3%A3o%20de%20S%C3%A9rie%20de%20Exercicios.png)
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Tela%20do%20professor%20de%20Atividade%20do%20Aluno.png)



### 5	MODELO CONCEITUAL<br>
#### 5.1 NOTACAO ENTIDADE RELACIONAMENTO
![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/Conceitual_1.png)
    
     5.2 NOTACAO UML (Caso esteja fazendo a disciplina de Projeto)

#### 5.3 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

#### 5.4 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 6	MODELO LÓGICO<br>


### 7	MODELO FÍSICO<br>

![Alt text](https://github.com/Ldipr3/Topicos-Trabalho-BD2/blob/master/png_bd.png)


### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        Detalhamento sobre as informações e processo de obtenção ou geração dos dados.
        Referenciar todas as fontes referentes a:
        a) obtenção dos dados
        b) obtenção de códigos reutilizados
        c) fontes de estudo para desenvolvimento do projeto
        
#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELAS E INSERÇÃO DOS DADOS (ARQUIVO ÚNICO COM):
        a) inclusão das instruções para criação das tabelas e estruturas de amazenamento do BD
        b) inclusão das instruções de inserção dos dados nas referidas tabelas
        c) inclusão das instruções para execução de outros procedimentos necessários

### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
#### 9.1	GERACAO DE DADOS (MÍNIMO DE 1,5 MILHÃO DE REGISTROS PARA PRINCIPAL RELAÇAO)<br>
    Data de Entrega: (Data a ser definida)
<br>
OBS: Incluir para os tópicos 9.2 e 9.3 as instruções SQL + imagens (print da tela) mostrando os resultados.<br>

#### 9.2	SELECT DAS TABELAS COM PRIMEIROS 10 REGISTROS INSERIDOS <br> 
    Data de Entrega: (Data a ser definida)
<br>

#### 9.3	SELECT DAS VISÕES COM PRIMEIROS 10 REGISTROS DA VIEW <br>
        a) Descrição da view sobre que grupos de usuários (operacional/estratégico) <br>
        e necessidade ela contempla.
        b) Descrição das permissões de acesso e usuários correlacionados (após definição <br>
        destas características)
    Data de Entrega: (Data a ser definida)
<br>

#### 9.4	LISTA DE CODIGOS DAS FUNÇÕES, ASSERÇOES E TRIGGERS<br>
        Detalhamento sobre funcionalidade de cada código.
        a) Objetivo
        b) Código do objeto (função/trigger/asserção)
        c) exemplo de dados para aplicação
        d) resultados em forma de tabela/imagem
<br>

#### 9.5	Administração do banco de dados<br>
        Descrição detalhada sobre como serão executadas no banco de dados as <br>
        seguintes atividades.
        a) Segurança e autorização de acesso:
        b) Estimativas de aquisição de recursos para armazenamento e processamento da informação
        c) Planejamento de rotinas de manutenção e monitoramento do banco
        d) Plano com frequencia de análises visando otimização de performance
<br>

#### 9.6	Backup do Banco de Dados<br>
        Detalhamento do backup.
        a) Tempo
        b) Tamanho
        c) Teste de restauração (backup)
        d) Tempo para restauração
        e) Teste de restauração (script sql)
        f) Tempo para restauração (script sql)
<br>

Data de Entrega: (Data a ser definida)
<br>

#### 9.7	APLICAÇAO DE ÍNDICES E TESTES DE PERFORMANCE<br>
    a) Lista de índices, tipos de índices com explicação de porque foram implementados
    b) Performance esperada VS Resultados obtidos
    c) Tabela de resultados comparando velocidades antes e depois da aplicação dos índices.
<br>
    Data de Entrega: (Data a ser definida)
<br>   

#### 9.8	ANÁLISE DOS DADOS COM ORANGE<br>    
    a) aplicação de algoritmos e interpretação dos resultados
<br>
    Data de Entrega: (Data a ser definida)
<br>

### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO/ SLIDES E ENTREGA FINAL<br>
<br>
    Data de Entrega: (Data a ser definida)
<br>

### 11	DIFICULDADES ENCONTRADAS PELO GRUPO<br>  

### 12  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/

Link para BrModelo: <br>
http://sis4.com/brModelo/brModelo/download.html

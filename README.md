# gestaocondominio.github.io
ENDEREÇO PARA ACESSAR O SITE: gestaocondominio.github.io/home.html

ETAPAS DO PROJETO:
1- CRIAÇÃO DO SITE DO SITEMA
1.1- PÁGINAS PARA SEREM CRIADAS
    1.1.1- HOME
    1.1.2- ABOUT US
    1.1.3- PLANS
    1.1.4- TEAM
    1.1.5- CONTACT

2- MODELAGEM DO BANCO DE DADOS E CRIAÇÃO DAS TABELAS
2.1- CRIAÇÃO DO MODELO DE DADOS DAS TABELAS COM OS SEUS RELACIONAMENTOS
2.2- TABELAS PARA SEREM CRIADAS:
    2.2.1- GESTÃO DOS SERVIÇOS (ADMINISTRATIVO)
        2.2.1.1- CONDOMINIUM (ARMAZENA OS DADOS DOS CONDOMÍNIO)
        2.2.1.2- SERVICE (ARMAZENA OS SERVIÇOS QUE SERÃO E/OU SERÁ FEITO NO CONDOMÍNIO)
        2.2.1.3- LANDLORD (ARMAZENA OS DADOS DO(S) SÍNDICOS(S) DO CONDOMÍNIO)
        2.2.1.4- BUDGET (ARMAZENA OS ORÇAMENTOS DOS SERVIÇOS QUE SERÃO EXECUTADOS E/OU PLANEJADOS PELO CONDOMÍNIO)
        2.2.1.5- STATUS_BUDGET (ARMAZENA OS TIPOS SITUAÇÃO QUE O ORÇAMENTO PODERÁ RECEBER(EM ANÁLISE, CANCELADO, APROVADO, PARALIZADO))
       
    2.2.2- GESTÃO DAS ENTRADAS E SAÍDAS (FINANCEIRO)
        2.2.2.1- ENTRIE (ARMAZENA TODAS AS ENTRADAS DO CONDOMÍNIO)
        2.2.2.2- EXIST (ARMAZENA TODAS AS SAÍDAS DO CONDOMÍNIO)
        2.2.2.3- INVOICE (ARMAZENAS AS NF DOS SERVIÇOS EXECUTADOS PARA O CONDOMÍNIO)
    
    2.2.3- TABELAS UTILIZADAS NOS DOIS MÓDULOS (ADMINISTRATIVO E FINANCEIRO)
        2.2.3.1- CREATED_AT (ARMAZENA A DATA E HORÁRIO DE CRIAÇÃO DO DADOS (CRIADO AUTOMATICAMENTE))
        2.2.3.2- UPDATED_AT (ARMAZENA A DATA E HORÁRIO DE ATUALIZAÇÃO DO DADOS (CRIADO A PARTIR DA ATUALIZAÇÃO DE ALGUM REGISTRO NO BD))
        2.2.3.3- USER (ARMAZENA O(S) USUÁRIO(S) DO SISTEMA)
        2.2.3.4- PROFILE (ARMAZENA O TIPO DO PERFIL DO USUÁRIO(SINDICO(PERFIL CRUD), SUBSINDICO(PERFIL CRUD), TESOUREIRO(PERFIL CRUD), CONDÔMINO(PERFIL R))
        2.2.3.5- PLAN (ARMAZENA OS PLANOS COMERCIALIZADOS PELA EMPRESA (BÁSCIO, INTERMEDIÁRIO, COMPLETO))

3- CRIAÇÃO DO SISTEMA DE GERENCIAMENTO
3.1- LINGUAGEM DE PROGAMAÇÃO
    3.1.1- PYTHON

3.2- BIBLIOTECAS UTILIZADAS
    3.2.1- DJANGO
    3.2.2- REQUEST

4- LEGENDA
    C- CREATE
    R- READE
    U- UPDATE
    D- DELETE
    NF- NOTA FISCAL

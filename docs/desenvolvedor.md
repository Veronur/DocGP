# Tutorial para Desenvolvimento

## Configurando ambiente de desenvolvimento

Primeiramente instale sqlite3 
Sistemas baseados em debian (Ubuntu, Debian etc.):   

    $ sudo apt-get update
    $ sudo apt-get install sqlite3

Sistemas baseado em RPM (RHEL, CentOS, Fedora etc.):

    $ sudo yum update
    $ sudo yum install sqlite

Tambem e necessaria a instalacao do flask e o flask_httpauth com:

    $ sudo pip3 install flask
    $ sudo pip3 install flask_httpauth


## Instalacao do software

Para a instalacao do software e necessario entrar no ambiente do sqlite3 para criar o banco de dados utilizando

    $ sqlite3 quiz.db

Uma vez no ambiente do sqlite3 rode o script de criacao do banco de dadods com 

    $ .read quiz.sql

Com o banco de dados criados e necessario criar agora os usuarios. Crie um arquivo chamado  ```users.csv ```  e siga as instrucoes de criacao de usuario na aba professores.

Com isso o software esta pronto. Para rodar basta executar:

    $ sudo python3 softdes.py


## Estrutura do codigo

As funcoes que constituem o codigo sao:

::: softdes.lambda_handler
    :docstring:
    :members:

::: softdes.converte_data
    :docstring:

::: softdes.get_quizes
    :docstring:


::: softdes.get_user_quiz
    :docstring:


::: softdes.set_user_quiz
    :docstring:


::: softdes.get_quiz
    :docstring:


::: softdes.set_info
    :docstring:


::: softdes.get_info
    :docstring:


::: softdes.get_quizes
    :docstring:

::: softdes.get_quizes
    :docstring:








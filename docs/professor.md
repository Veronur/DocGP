# Tutorial para professores

## Adicionando Usuarios

Para adicionar um novo usuario basta adiciona-lo ao arquivo ``` users.csv ``` fornecendo-o um nome e um tipo como na imagem abaixo.

```
Lucca,aluno
Gabriel,aluno
Igor,Professor
```
E entao rodar o codigo ```addUser.py ```


## Adicionando um novo quiz

Para adicionar um novo quiz e necessario que primeiro se tenha o sqlite3 intalado e entao se executa um insert no banco de dados como no ecemplo abaixo: ("<<>>" Para axilio do preechimento)
```
>$sqlite3 quiz.db
><sqlite3> Insert into QUIZ(numb, release, expire, problem, tests, results, diagnosis) 
 values (<<NUMERO DO DESAFIO (Inteiro)>>, <<Data da adicao ("aaaa-mm-dd")>>,
  <<Data e hora limite da entrega ("aaaa-mm-dd hh:mm:ss")>>,
   <<Enunciado do problema (string) >> ,
    <<Entrada dos testes (Ex:"[[1],[2],[3]]")>> ,
     <<Resultado esperado para os testes (Ex:("[0, 0, 0]") >>,
      <<Feedback dos testes (Ex:"['a','b','c']")>>);
```

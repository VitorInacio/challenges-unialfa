#### Atividade 8

## bindParam

* Ele evita de usuários mal intencionados conseguir criar algum erro na hora da pesquisa no bando de dados
* Por exemplo: Se o usuário mudar na URL o que era para ser o valor do ID para "1 or 1+1=2", sem o bindParam nesse caso, o banco iria passar todos os dados da tabela
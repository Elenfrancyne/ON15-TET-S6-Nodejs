# Respostas
1.Qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)? 
R: Ele está no nível 2 de maturidade essas APIa  usam os verbos HTTP, na forma do CRUD, é mais fácil de se comprender e tem um consumo mais simples, reduzindo o seu consumo. O mais desorganizado é o de nível 0, e o mais organizado nível 3.
 
2.Qual a relação entre os métodos HTTP e CRUD?
R: Relação de correspondência, e sim é proposital. POST, GET, PUT, PATCH E DELETE,  são os verbos HTTP e significam: LER,CRIAR, SUBSTITUIR, MODIFICAR, EXCLUIR. No CRUD temos: CREATE, READ, UPDATE, DELETE  	traduzindo em  CRIAR, LER, ATUALIZAR(corresponde ao substituir e modificar).

3.O que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
R: É uma restrição de aplicativos do Rest, e não é opcional, portanto obrigatório  Este modelo ajuda os Clients que consomem o REST(Web API)  a navegar pelos recursos, e tornar as ações da WEB API, mais faceis de entender. A 

4.O que quer dizer quando dizemos que uma API é idempotente?
R:Quando o resultado de um request com sucesso, não depende do numero de vezes que é executada. Ou seja pode ser explicada mais de uma vez sem que altere o resultado da API.

5.Qual a diferença entre os métodos PUT e PATCH?
R:O método de requisição HTTP PATCH aplica modificações parciais a um recurso, ou seja ele modifica um recurso , faz mudanças e alterações.já o método  de requisição HTTP PUT cria um novo recurso, ou seja  subsititui uma representação do recurso de destino com os novos dados.

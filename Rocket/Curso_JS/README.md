## TESTES DE MODELOS DE README.

- Aqui iremos colocar algumas formatações do README.


beleza?


## A.P.I - API - Application Programming Interface (Interface de Programação de Aplicações):

É um conjunto de rotinas e padrões estabelicidos por uma aplicação, para que possa ser utilizada as funcionalidades da mesma.
- Responsável por estabelecer comunicação entre diferentes serviços.
- Meio de campo entre as tecnologias.
- Intermediador para troca de informações.

## REST - REpresentational State Transfer (Transferência de Estado Representativo):

É feita a transferência de dados de uma maneira símbolica, figurativa, representativa e didática:
- Tranferência geralmente usa o protocolo HTTP.
- Delimita algumas obrigações na tranferência de dados.
- Resources seria então, uma entidade, um objeto.


## RESTFULL.
- RESTFull é aplicar os padrões REST.

## 5 NECESSIDADES (CONSTRAINTS) PARA SER RESTFULL:
- 1: _Client-Server_: Separação do cliente e do armazenamento de dados(Servidor), dessa forma, poderemos ter uma portabilidade do nosso sistema, usando o React para WEB e React Native para o Smartphone, por exemplo.

- 2: _Stateless_:(sem estado) Cada requisção que o cliente faz para o servidor, deverá conter todas as informações necessárias para o servidor entender e responder(RESPONSE) a requisição(REQUEST). Exemplo: A sessão do usuário está autenticado e apto a usar os serviços, e o servidor não pode lembrar que o cliente foi autenticado na requisição anterior. Para esta comunicação se recomenda usar tokens.

- 3: _Cacheable_: As resposta para uma requisição, deverão ser explicitadas ao dizer se aquela requisição,pode ou não ser cacheada pelo cliente.

- 4: _Layered System_: o Cliente acessa a um endpoint, sem precisar saber a complexidade de quais passos estão sendo necessários para o servidor está lidando, para que a requisiçãp seja respondida.

- 5:_Code on Demand(optional)_: Dá a possibildade da nossa aplicação pegar códigos, como o JavaScript, por exemplo, e executar no cliente.








Aula de Mayk Brito.
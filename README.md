Repositório relativo ao desafio "Explorando IA Generativa em um Pipeline de ETL com Python" do "Bootcamp Santander 2025 - Ciência de Dados com Python" da plataforma DIO.

Desafio simples com o objetivo de pegar informações de clientes de um arquivo CSV, e alimentar uma IA para gerar pequenas mensagens de marketing bancário. 

Para a IA, foi utilizada a Pollinations.ai (100% livre, zero burocracia), pois não precisa de chave, nem de cadastro, nem de cartão de crédito. Ele faz uma requisição HTTP comum via requests e já devolve a resposta gerada por IA (a requisição pode demorar).

Após o retorno das mensagens de campanhas, elas são salvas em um novo arquivo CSV com o ID do cliente e data que foi gerada para controle.

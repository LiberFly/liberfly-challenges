# Desafio Frontend LiberFly

## Cenário hipotético

Nosso designer projetou no figma a interface do novo aplicativo de carteira digital da LiberFly. Infelizmente o arquivo foi corrompido e nos restou apenas um arquivo PNG apresentando as telas projetadas. Enquanto o designer refaz o projeto no figma precisamos ganhar tempo no desenvolvimento para não atrasar a entrega do app e você é o programador frontend responsável por implementar a interface. A figura abaixo apresenta o projeto de interface elaborado pelo designer que você terá que implementar.

![Projeto de interface da carteira digital.](https://i.pinimg.com/originals/a8/b9/13/a8b9132cac792813e64813e728e1754c.png)

## Requisitos do projeto

* O frontend deve ser desenvolvido utilizando Vue.js ou React Native.
* O projeto deve ser versionado no GitHub.
* É necessário implementar a transição de uma tela para outra.
* Crie um README.md no repositório com a documentação do projeto e um tutorial para executá-lo.
* Descubra quais as fonts utilizadas na interface ou utilize a mais parecida que encontrar. Uma dica é pesquisá-las no site: https://whatfontis.com
* A interface deve ser responsiva e se a adaptar a diferentes resoluções de smartphones.

## O que será avaliado

* Tempo de entrega.
* Fidelidade da interface com o projeto.
* Boas práticas de desenvolvimento seguindo os padrões da tecnologia escolhida.
* Versionamento no GitHub.
* Documentação no GitHub.
* Criativade ao solucionar problemas durante o desenvolvimento.

## Json para obter dados

Os dados apresentados no frontend devem ser obtidos a partir de um json, que deve estar armazenado no seu projeto, com a estrutura abaixo:

~~~json
[
	{
		"category": "Checkout",
		"item": "Depósito Bancário",
		"amount": "100.00",
		"type": "spending",
		"datetime": "2020-08-20",
		"status": "pending"
	},
	{
		"category": "MGM",
		"item": "Indicação",
		"status": "100.00",
		"type": "income",
		"datetime": "2020-08-19",
		"status": "approved"
	},
	{
		"category": "MGM",
		"item": "Indicação",
		"amount": "100.00",
		"type": "income",
		"datetime": "2020-08-18",
		"status": "approved"
	},
	{
		"category": "MGM",
		"item": "Indicação",
		"amount": "100.00",
		"type": "income",
		"datetime": "2020-08-17",
		"status": "approved"
	}
]
~~~

## Para ganhar pontos extras

* Implemente o selectbox com filtro de períodos: no mês, na semana, no dia.
* Implemente a paginação da tela de extrato ao clicar em "See more" onde as transações são exibidas.
* No valor da transação, diferenciar por cor as que estão pendentes, aprovadas ou recusadas.

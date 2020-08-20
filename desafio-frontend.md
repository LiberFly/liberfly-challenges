# Desafio Frontend LiberFly

Nosso designer projetou no figma a interface do nosso novo aplicativo de carteira digital. Infelizmente o arquivo foi corrompido e nos restou apenas o um PNG apresentando as telas projetadas. Enquanto o designer refaz o projeto no figma precisamos ganhar tempo no desenvolvimento para não atrasar a entrega do app e você é o programador frontend responsável por implementar a interface. A figura abaixo apresenta o projeto de interface elaborado pelo designer que você terá que implementar.

![Projeto de interface da carteira digital.](https://i.pinimg.com/originals/a8/b9/13/a8b9132cac792813e64813e728e1754c.png)

## Requisitos do projeto

* O frontend deve ser desenvolvido utilizando Vue.js ou React Native.
* O projeto deve ser versionado no GitHub.
* É necessário implementar a transição de uma tela para outra.
* Crie um README.md no repositório com a documentação do projeto e um tutorial para executá-lo.
* Descubra quais as fonts utilizadas na interface ou utilize a mais parecida que encontrar. Uma dica é pesquisá-las no site: https://whatfontis.com
* A interface deve ser responsiva e se a adaptar a diferentes resoluções de smartphones.
* Implemente o efeito de transição de página.

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
		"category": "",
		"item": "",
		"amount": "",
		"direction": "",
		"datetime": ""
	},
	{
		"category": "",
		"item": "",
		"amount": "",
		"direction": "",
		"datetime": ""
	},
	{
		"category": "",
		"item": "",
		"amount": "",
		"direction": "",
		"datetime": ""
	},
	{
		"category": "",
		"item": "",
		"amount": "",
		"direction": "",
		"datetime": ""
	}
]
~~~

## Para ganhar pontos extras

* Implemente o selectbox com filtro de períodos: no mês, no dia, na semana.
* Implemente a paginação da tela de extrato onde as transações são exibidas.

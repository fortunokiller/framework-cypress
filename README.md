###Cypress###

#ferramentas necessarias
	-node js
	-vs code
	-cypress
	-cmder

#para criar json	
	npm init -y

#instalando cypress
	npm install cypress
	npm install cypress@3.6.0 //caso queira instalar determinada versao
	
#abrindo cypress
	-dentro do arquivo package.json, apos a linha "test", inserir:
		,
		"cypress:open":"cypress open"
		
	-entao ir na pasta raiz pelo cmd e inserir
		npm run cypress:open
	
#rodando teste na pasta 'advanced-examples'
	-dentro da ferramenta cypress:
		basta clicar em algum teste, por exemplo clicar em => actions.spec.js
	-quando confirmar o funcionamento, podemos excluir as pastas:
		cypress/integration/1-getting-started
		cypress/integration/2-advanced-examples

#link doc cypress
	https://docs.cypress.io/
	https://github.com/cypress-io/cypress
	
#end#

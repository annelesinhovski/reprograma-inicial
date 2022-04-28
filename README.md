# Repositório com estrutura básica para projeto

Olá!

Aqui você vai encontrar uma estrutura básica para montar o seu primeiro projeto de front-end e construir a sua primeira página usando HTML, CSS e Javascript.

É só clonar esse repositório na sua máquina e usar essa estrutura para começar um novo projeto. :)

---

## **JAVASCRIPT:**

Existem algumas funcionalidades no Javascript, que utilizamos no nosso dia-a-dia, e que facilitam muito nossa vida na hora de conseguir achar algum dado específico ou até mesmo escrever uma funcionalidade nova.

No ES6, temos algumas funcionalidades que são muito utilizadas diariamente. São elas:

![enter image description here](https://raw.githubusercontent.com/kimuradev/gh-assets/master/assets/javascript.jpg)


E aqui começa o **1 º Desafio:**

A partir do array de objetos abaixo contendo login, email e idade:

```
const users = [
	{
		login: 'brunohs',
		email: 'brunohs@pbtech.net.br',
		age: 18
	},
	{
		login: 'thainabcc',
		email: 'thaina.biudes@gmail.com',
		age: 25
	},
	{
		login: 'annecl',
		email: 'annecl@pbtech.net.br',
		age: 34
	},
   	{
        	login: 'willianfl',
	        email: 'willianfl@pbtech.net.br',
        	age: 30
	},
    	{
        	login: 'lucasplc',
	        email: 'lucasplc@pbtech.net.br',
        	age: 20
	}
];
```

- Criar uma função para somar a idade de todos os usuários na lista
- Criar uma função para validar se o login existe dentro do objeto
- Criar uma função para mostrar todos os emails no console.log
- Criar uma função para contar quantos usuários possuem e-mail da empresa pbtech.net.br

> **Importante**: cada uma das funções acima, deve utilizar pelo menos uma das funções do javascript descritas na imagem. (map, filter, find, reduce)

**2 º Desafio:** 

Com todas as funções criadas, você deve utilizá-las na landing page do Reprograma, para digitar e-mail e senha, e em seguida clicar no botão "Continuar".

> O campo login deve ser preenchido com um login existente no array de objetos do modelo passado acima, e a senha é a soma das idades dos usuários da lista.

- Você deve utilizar a função criada para validar se o login existe e comparar com o login que você digitou
- Você deve utilizar a função criada para somar as idades e comparar com a senha que você digitou.
- Caso o login e senha estejam corretos, você deve alertar o usuário que o formulário foi submetido.

> **Plus**: Alertar o usuário quando o e-mail ou senha estiverem vazios ou incorretos.

> Links de referência:
>
> - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
> - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
> - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)
> - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
> - [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search)

---

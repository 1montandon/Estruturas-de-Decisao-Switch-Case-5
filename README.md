# Estruturas de Decisão [switch-case]

##### Como assim... Switch... Case?

* **Outra estrutura de decisão**
* As linguagens de programação possuem outra estrutura de condições.

**Quando usar?**
- Quando houverem várias alternativas a partir do valor de uma constante/variável.
- É uma lógica fácil e intuitiva

**Sobre a utilização**
O comando switch inicia pela definição da variável/constante que escolhe a condição a ser executada. Cada instrução deve conter um valor de comparação (seguida pelos ":")
```javascript
switch (mes) {
  case "Janeiro":
    alert('Férias!');
    breack;
  case "Fevereiro":
    alert('Aulas!')
}
```

Objetivo é, com operador ternário, obter a seguinte estrutura:
* _condição ? valor verdadeiro : valor falso_

Ou então, quando necessário aninhar operador ternário:
* _condição ? valor verdadeiro : nova condição ? valor verdadeiro : valor falso_

> **_O maior ganho ao utilizar operador ternário é a economia de linhas!_**

### Exemplos
* [Exemplo 1](exemploIf_01.html)
* [Exemplo 2](exemploIf_02.html)
* [Exemplo 3](exemploIf_03.html)


##### Alguns links para estudos complementares

* [Developer.mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
* [Programando Soluções](https://programandosolucoes.dev.br/2021/04/13/operador-ternario-javascript/)
* [Programador viking](https://programadorviking.com.br/if-ternario-javascript/)

##### Vídeos de apoio
* [YouTube CFTv - Operador Ternário](https://www.youtube.com/watch?v=YjEtiFi2k7g)
* [YouTube Dev Aprender - Operador Ternário](https://www.youtube.com/watch?v=Mbwg0YIZwYo)

##### Dúvidas da comunidade sobre if-else
* [Stack Overflow - if else](https://pt.stackoverflow.com/questions/4907/como-funciona-este-if-else-com-e)
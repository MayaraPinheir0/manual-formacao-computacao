data: 03 jun 2026


# Exercicios
## 1. 
### um homem precisa atravessar um rio com um barco que possui capacidade somente para carregar ele mesmo e mais uma de suas três cargas, que são um lobo, uma cabra e um repolho. O que o homem deve fazer para conseguir atravessar o rio sem perder suas cargas? 

primeiro definir as condicoes do problema que nao estao explicitas, 

* delimitar o problema:
o lobo nao pode ficar sozinho com o bode,
o bode nao pode ficar sozinho com o repolho.
atravessa-se só dois no barco.

* definicoes:
atravessar o rio - sair de A ao B

Nesse sentido, a sequencia seria:

**\ Algoritmo Travessia_Lobo_Bode_Repolho \**


o homem vai pegar o bode:
  coloca no barco:
  
    no barco:
      sair do ponto A ao B:
      deixar o bode no ponto B do rio,
      voltar ao ponto A

_situacao 1: o lobo e repolho estao do lado A, e o bode do lado B_

o homem vai pegar o repolho:
  coloca no barco,
  
    no barco:
      sair de A, chegar ao B:
        trocar:
          deixa o repolho no lado B,
          pegar o bode, 
          colocar no barco,
          e volta ao A.

_situacao 2: agora, o repolho está no lado B, o bode com o homem, e o lobo no lado A._

o homem vai deixar o bode:
pegar o lobo:
  colocar no barco,

    no barco:
      sair de A, chegar a B:
        trocar:
          deixa o lobo no lado B,
          e volta ao A.

_situacao 3: tem-se, a condicao da situacao 1, mas no lado diferente do começo. o lobo e repolho do lado B, e o bode do lado A._

o homem vai pegar o bode:
  colocar no barco,
    no barco:
      sair de A, chegar a B:
      Fim
    

pergunta: será que o algoritimo so funciona, no sentido mais amplo, ligado a sua existencia mesmo, porque consiguimos analisar os passos que nao estao sendo relatando enquanto esta sendo resolvido, o problema?



## 2. três jesuítas e três canibais precisam atravessar um rio; para tal dispõem de um barco com capacidade para duas pessoas. Por medidas de segurança, não se deve permitir que em alguma margem a quantidade de jesuítas seja inferior a de canibais. 
data: 02 jun 2026

# Introdução à Lógica Teórica e Computacional

Este repositório destina-se ao registro, estruturação e divulgação de estudos fundamentais em Lógica, servindo como base conceitual para o desenvolvimento de habilidades em Lógica de Programação e Ciência da Computação.

---

## 1. Fundamentos da Lógica

### 1.1 O Conceito de Lógica: Correção e Ordenação do Pensamento

De acordo com Forbellone e Eberspacher (2022), a lógica pode ser definida como a ciência da "correção do pensamento". Seu foco reside em determinar quais operações intelectuais são válidas ou inválidas por meio da análise rigorosa das formas e das leis que regem o pensamento. 

* **Reflexão Crítica e Epistemológica:** Expandindo a visão clássica dos autores, a lógica atua não apenas como um corretor passivo, mas como um instrumental normativo e metodológico. Ela fornece o arcabouço estrutural que valida e orienta a transição legítima entre proposições, garantindo que as conclusões ou suposições inferidas sejam formalmente consistentes.
* **Lacuna Metodológica:** Embora a literatura tradicional enfatize o uso da lógica para a correta aplicação das "leis do pensamento", frequentemente há uma omissão ontológica quanto à definição e à origem dessas próprias leis (sejam elas axiomáticas, biológicas ou construídas socialmente).
* **Definição Expandida:** Em termos contemporâneos, a Lógica constitui um ramo interdisciplinar da ciência que investiga, classifica e formaliza as estruturas de enunciados e argumentos. Sua finalidade precípua é identificar e isolar critérios normativos para discernir inferências válidas (corretas) de falácias ou paradoxos (incorretas) (OUTLINE..., 2026).

Para auxiliar na navegação dos conceitos e na terminologia clássica frequentemente catalogada em verbetes e glossários de lógica, adota-se a taxonomia formal de argumentos (GLOSSARY OF LOGIC, 2026):

<p align="center">
  <img src="./imagens/img1-argument_terminology.png" alt="Terminologia Clássica de Argumentos" width="450">
  <br>
  <em>Figura 1: Terminologia clássica de argumentos e estruturas lógicas.</em>
</p>

---

## 2. Análise Estrutural de Argumentos: O Silogismo Clássico

Considere o seguinte exemplo clássico de silogismo categórico:

> *Todo mamífero é um animal.*
> *Todo cavalo é um mamífero.*
> *Portanto, todo cavalo é um animal.*

Este argumento pode ser formalizado e interpretado sob múltiplos prismas metodológicos:

### Abordagem 1: Dedução Formal e Transitividade Proposicional
Podemos mapear as proposições atribuindo variáveis às classes:
* $A$ : Mamífero
* $B$ : Animal
* $C$ : Cavalo

A estrutura lógica baseia-se na propriedade da **transitividade da implicação** (ou inclusão de conjuntos):
$$	ext{Se } C \subset A \quad 	ext{e } \quad A \subset B, \quad 	ext{logo } \quad C \subset B$$

*Nota de correção técnica:* Na formulação estritamente matemática, expressa-se via inclusão de conjuntos ou implicação lógica ($
ightarrow$), e não por igualdade mecânica ($C = B$), visto que o Cavalo ($C$) está contido no conjunto dos Animais ($B$), mas não o exaure.

### Abordagem 2: Abstração Computacional (Especialização e Generalização)
Sob a ótica da Ciência da Informação e da Programação Orientada a Objetos (POO):
* **Animal** representa a classe mais genérica (pertencente ao Filo no reino biológico).
* **Mamífero** configura uma subclasse de Animal, herdando seus atributos e métodos (Especialização de Animal).
* **Cavalo** configura uma subclasse ainda mais específica, contida em Mamífero.

Aqui, o raciocínio lógico é modelado por meio de hierarquias de herança e taxonomia de dados, onde a ontologia mapeia o mundo real em estruturas computacionais.

---

## 3. Discussão Filosófica e Cognitiva

A convergência do pensamento humano para métodos estruturados de resolução de problemas levanta questões profundas:

1. **Cognição vs. Estrutura:** Resolvemos problemas cotidianos aplicando lógica formal abstrata ou por meio de mecanismos evolucionários de especialização e generalização? O pensamento humano parece convergir para um método algorítmico, cujas nuances variam conforme o contexto sociocultural e a linguagem.
2. **Dependência Científica:** A articulação sucessiva e estruturada de ideias exige o respeito estrito às leis da física e da natureza? No campo da lógica computacional e matemática, a resposta é **não**. Somos capazes de criar sistemas axiomáticos inteiramente novos e consistentes modificando as premissas fundamentais (como ocorre nas físicas não-euclidianas ou em lógicas polivalentes e paraconsistentes), permitindo a manipulação e a criação de conhecimentos em realidades puramente abstratas.

---

## 4. Referências Bibliográficas

* FORBELLONE, André Luiz Villar; EBERSPACHER, Henri Frederico. **Lógica de Programação**: a construção de algoritmos e estruturas de dados. 4. ed. São Paulo: Bookman, 2022.
* GLOSSARY of logic. In: **WIKIPEDIA**: the free encyclopedia. [San Francisco, CA: Wikimedia Foundation], 2026. Versão estável do artigo. Disponível em: <https://en.wikipedia.org/w/index.php?title=Glossary_of_logic&oldid=1255864119>. Acesso em: 2 jun. 2026.
* OUTLINE of logic. In: **WIKIPEDIA**: the free encyclopedia. [San Francisco, CA: Wikimedia Foundation], 2026. Versão estável do artigo. Disponível em: <https://en.wikipedia.org/w/index.php?title=Outline_of_logic&oldid=1255864115>. Acesso em: 2 jun. 2026.
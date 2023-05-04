**[Centro Universitário do Instituto Mauá de Tecnologia]{.smallcaps}\
Escola de Engenharia Mauá\
**Engenharia de Computação

[Rodrigo Machado Pedreira\
\
\
]{.smallcaps}

**Computação quântica\
**

São Caetano do Sul\
2023

[Rodrigo Machado Pedreira\
\
\
]{.smallcaps}

**Computação quântica\
**

Trabalho de Conclusão de Curso apresentado à Escola de Engenharia Mauá
do Centro Universitário do Instituto Mauá de Tecnologia como requisito
parcial para a obtenção do título de Engenheiro de Computação.

Orientador: Dr. Prof. Sandro Martini

> Área de concentração: Engenharia eletrônica

São Caetano do Sul\
2023

+-------+--------------------------------------------------------------+
|       | Pedreira, Rodrigo                                            |
|       |                                                              |
|       | [Título principal]{.mark} : [subtítulo]{.mark}. / Rodrigo    |
|       | Machado Pedreira. --- São Caetano do Sul : CEUN-IMT, 2023.   |
|       |                                                              |
|       | [Número de páginas]{.mark} p.                                |
|       |                                                              |
|       | Trabalho de Conclusão de Curso -- Escola de Engenharia Mauá  |
|       | do Centro Universitário do Instituto Mauá de Tecnologia, São |
|       | Caetano do Sul, SP, 2023.                                    |
|       |                                                              |
|       | Orientador(a): Dr. Prof. Sandro Martini                      |
|       |                                                              |
|       | > 1\. [Palavra-chave1]{.mark}. 2. [Palavra-chave2]{.mark}.   |
|       | > 3. [Palavra-chave3]{.mark}. 4. [Palavra-chave4]{.mark}. 5. |
|       | > [Palavra-chave5]{.mark}. I. Instituto Mauá de Tecnologia.  |
|       | > Escola [de Engenharia ou de Administração]{.mark}. II.     |
|       | > Título.                                                    |
+=======+==============================================================+
+-------+--------------------------------------------------------------+

[Rodrigo Machado Pedreira\
\
\
]{.smallcaps}

**Computação quântica**

Trabalho de Conclusão de Curso aprovado pela Escola de Engenharia Mauá
do Centro Universitário do Instituto Mauá de Tecnologia como requisito
parcial para a obtenção do título de Engenheiro de Computação.

Banca avaliadora:

Dr. Prof. Sandro Martini\
Orientador(a)

Nome completo do professor(a) avaliador(a) 1 e título\
Avaliador(a) ou Instituição, se externo

Nome completo do professor(a) avaliador(a) 2, se houver, e título\
Avaliador(a) ou Instituição, se externo

São Caetano do Sul, [data da apresentação]{.mark} de [mês]{.mark} de
2023.

*Dedicamos este trabalho para\
[pessoa ou pessoas às quais o trabalho é dedicado]{.mark}.*

Agradecimentos

*A epígrafe é texto contendo um pensamento ou uma ideia,\
em português ou em outro idioma alusivo ao conteúdo ou experiência do
trabalho,\
com a devida citação de seu autor.*

Resumo

Palavras‑chave: Palavra‑chave1. Palavra‑chave2. Palavra‑chave3.
Palavra‑chave4. Palavra‑chave5.

*Abstract*

Keywords: Keyword1. Keyword2. Keyword3. Keyword4. Keyword5

Lista de figuras

Lista de tabelas

Lista de abreviaturas e siglas

IA -- Inteligência Artificial

Lista de símbolos

Sumário

[1 Introdução [27](#introdução)](#introdução)

[1.1 Contextualização [27](#contextualização)](#contextualização)

[1.2 Objetivos [27](#objetivos)](#objetivos)

[1.3 Justificativa [27](#justificativa)](#justificativa)

[1.4 Organização do trabalho
[27](#organização-do-trabalho)](#organização-do-trabalho)

[2 Fundamentos da computação clássica
[29](#fundamentos-da-computação-clássica)](#fundamentos-da-computação-clássica)

[2.1 sistemas digitais [29](#sistemas-digitais)](#sistemas-digitais)

[2.2 Portas logicas clássicas
[29](#portas-logicas-clássicas)](#portas-logicas-clássicas)

[2.2.1 Porta AND [29](#porta-and)](#porta-and)

[2.2.2 Porta OR [29](#porta-or)](#porta-or)

[2.2.3 Porta NOT [29](#porta-not)](#porta-not)

[2.2.4 Porta NAND, NOR, XOR e XNOR
[29](#porta-nand-nor-xor-e-xnor)](#porta-nand-nor-xor-e-xnor)

[2.3 Circuitos combinacionais e sequenciais
[29](#circuitos-combinacionais-e-sequenciais)](#circuitos-combinacionais-e-sequenciais)

[3 Fundamentos da Computação Quântica
[31](#fundamentos-da-computação-quântica)](#fundamentos-da-computação-quântica)

[3.1 Mecânica quântica e qubits
[31](#mecânica-quântica-e-qubits)](#mecânica-quântica-e-qubits)

[3.2 Princípios de superposição e entrelaçamento
[31](#princípios-de-superposição-e-entrelaçamento)](#princípios-de-superposição-e-entrelaçamento)

[3.3 Portas lógicas quânticas
[31](#portas-lógicas-quânticas)](#portas-lógicas-quânticas)

[3.3.1 Porta de Pauli-X [31](#porta-de-pauli-x)](#porta-de-pauli-x)

[3.3.2 Porta de Pauli-Y [31](#porta-de-pauli-y)](#porta-de-pauli-y)

[3.3.3 Porta de Pauli-Z [31](#porta-de-pauli-z)](#porta-de-pauli-z)

[3.3.4 Porta Hadamard [31](#porta-hadamard)](#porta-hadamard)

[3.3.5 Portas CNET, Toffoli e outras
[31](#portas-cnet-toffoli-e-outras)](#portas-cnet-toffoli-e-outras)

[3.4 Circuitos quânticos e algoritmos
[31](#circuitos-quânticos-e-algoritmos)](#circuitos-quânticos-e-algoritmos)

[4 Simulação em Python [33](#simulação-em-python)](#simulação-em-python)

[4.1 Introdução ao Python
[33](#introdução-ao-python)](#introdução-ao-python)

[4.2 Simulação de portas lógicas clássicas
[33](#simulação-de-portas-lógicas-clássicas)](#simulação-de-portas-lógicas-clássicas)

[4.2.1 Implementação das portas lógicas
[33](#implementação-das-portas-lógicas)](#implementação-das-portas-lógicas)

[4.2.2 Exemplos de simulações e análise
[33](#exemplos-de-simulações-e-análise)](#exemplos-de-simulações-e-análise)

[4.3 Simulação de portas lógicas quânticas
[33](#simulação-de-portas-lógicas-quânticas)](#simulação-de-portas-lógicas-quânticas)

[4.3.1 Introdução a bibliotecas quânticas em Python
[33](#introdução-a-bibliotecas-quânticas-em-python)](#introdução-a-bibliotecas-quânticas-em-python)

[4.3.2 Implementação das portas lógicas quânticas
[33](#implementação-das-portas-lógicas-quânticas)](#implementação-das-portas-lógicas-quânticas)

[4.3.3 Exemplos de simulações e análise
[33](#exemplos-de-simulações-e-análise-1)](#exemplos-de-simulações-e-análise-1)

[5 Comparação entre Computação Clássica e Quântica
[35](#comparação-entre-computação-clássica-e-quântica)](#comparação-entre-computação-clássica-e-quântica)

[5.1 Vantagens e desvantagens
[35](#vantagens-e-desvantagens)](#vantagens-e-desvantagens)

[5.2 Aplicações e implicações práticas
[35](#aplicações-e-implicações-práticas)](#aplicações-e-implicações-práticas)

[5.3 Desafios e perspectivas futuras
[35](#desafios-e-perspectivas-futuras)](#desafios-e-perspectivas-futuras)

[6 Conclusão [37](#conclusão)](#conclusão)

[6.1 Síntese dos resultados
[37](#síntese-dos-resultados)](#síntese-dos-resultados)

[6.2 Contribuições do trabalho
[37](#contribuições-do-trabalho)](#contribuições-do-trabalho)

[6.3 Sugestões para trabalhos futuros
[37](#sugestões-para-trabalhos-futuros)](#sugestões-para-trabalhos-futuros)

[Referências [38](#referências)](#referências)

[Glossário [39](#glossário)](#glossário)

[Apêndice a -- Códigos das simulações em Python
[40](#apêndice-a-códigos-das-simulações-em-python)](#apêndice-a-códigos-das-simulações-em-python)

[Anexo [41](#anexo)](#anexo)

[Índice [42](#índice)](#índice)

# Introdução

## Contextualização

## Objetivos

## Justificativa

## Organização do trabalho

# Fundamentos da computação clássica

## sistemas digitais

## Portas logicas clássicas

### Porta AND

### Porta OR

### Porta NOT

### Porta NAND, NOR, XOR e XNOR

## Circuitos combinacionais e sequenciais

# Fundamentos da Computação Quântica

## Mecânica quântica e qubits

## Princípios de superposição e entrelaçamento

## Portas lógicas quânticas

### Porta de Pauli-X

### Porta de Pauli-Y

### Porta de Pauli-Z

### Porta Hadamard

### Portas CNET, Toffoli e outras

## Circuitos quânticos e algoritmos

# Simulação em Python

## Introdução ao Python

## Simulação de portas lógicas clássicas

### Implementação das portas lógicas

### Exemplos de simulações e análise

## Simulação de portas lógicas quânticas

### Introdução a bibliotecas quânticas em Python

### Implementação das portas lógicas quânticas

### Exemplos de simulações e análise

# Comparação entre Computação Clássica e Quântica

## Vantagens e desvantagens

## Aplicações e implicações práticas

## Desafios e perspectivas futuras

# Conclusão

## Síntese dos resultados

## Contribuições do trabalho

## Sugestões para trabalhos futuros

###### Referências {#referências .unnumbered}

ABNT NBR 6028. **NBR 6028: Informação e documentação - Resumo -
Procedimento**. Associação Brasileira de Normas Técnicas. Rio de
Janeiro, p. 2. 2003.

ABNT NBR 6034. **NBR 6034: Informação e documentação - Índice -
Apresentação**. Associação Brasileira de Normas Técnicas. Rio de
Janeiro, p. 8. 2004.

###### Glossário {#glossário .unnumbered}

-   **Bit:**

-   **Qubit:**

###### Apêndice a -- Códigos das simulações em Python {#apêndice-a-códigos-das-simulações-em-python .unnumbered}

###### Anexo {#anexo .unnumbered}

###### Índice {#índice .unnumbered}

I

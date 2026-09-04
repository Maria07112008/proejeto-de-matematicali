# matematica2
 Modelagem Matemática e Programação: O Uso de Algoritmos na Inovação Tecnológica

## 1. Texto de Introdução do Trabalho

A era digital moderna é sustentada por uma base invisível, porém robusta: a união entre a **matemática** e a **programação**. Conceitos abstratos como cálculo, estatística, progressões e equações diferenciais deixaram de ser apenas teorias acadêmicas para se tornarem o motor de inovações como inteligência artificial, criptografia e modelagem de sistemas dinâmicos.

Este projeto tem como **objetivo principal** demonstrar a aplicação prática de conceitos de Matemática II por meio de um algoritmo desenvolvido em **JavaScript**, resolvendo um problema de simulação de sistemas complexos. Para ilustrar esse impacto, escolhemos modelar uma **Simulação de Reação em Cadeia** (inspirada em modelos de crescimento exponencial e decaimento dinâmico, como o modelo estocástico de propagação).

Através da interface web desenvolvida, mostramos como a automação de fórmulas matemáticas permite prever comportamentos em larga escala, provando que a computação é a ferramenta essencial que traduz equações abstratas em soluções tecnológicas interativas.

## 2. Explicação da Atividade: Como o Site Foi Feito

Para transformar a proposta teórica em um projeto funcional, interativo e visualmente moderno, a atividade foi estruturada utilizando os padrões fundamentais da web (**HTML5** e **CSS3**), integrados com a lógica de programação em **JavaScript**.

Abaixo está a explicação de como o site foi construído e como cada parte funciona:

### A. Estrutura de Arquivos do Projeto

O projeto foi dividido em dois arquivos principais para manter o código limpo, organizado e profissional (seguindo as boas práticas de desenvolvimento web):

1. **`index.html`**: É o esqueleto da página. Ele organiza o conteúdo textual do trabalho em seções semânticas (`<header>`, `<main>`, `<section>`, `<footer>`) e abriga a estrutura do **Laboratório de Simulação Interativa** (campos de entrada de dados e botões).
2. **`style.css`**: É a folha de estilos responsável pelo design visual. Utilizando variáveis globais (`:root`), um sistema moderno de cores em tons de azul escuro/ardósia, sombras suaves e o conceito de *Flexbox/Grid*, o CSS garante que a página seja totalmente responsiva, adaptando-se perfeitamente a telas de computadores, tablets e celulares.

### B. A Lógica Matemática no Código JavaScript

O coração interativo da página reside no script em JavaScript inserido no final do arquivo HTML. Ele executa os seguintes passos:

* **Entrada de Dados do Usuário:** O script captura os valores definidos pelo usuário nos campos da tela (núcleos iniciais, média da taxa de reação e número total de gerações).
* **Processamento Estocástico (Equação Discreta):** Através de um laço de repetição (`for`), a aplicação simula o crescimento exponencial geração por geração. Cada novo estado é calculado multiplicando o ativo atual pela taxa e aplicando um fator de aleatoriedade (`Math.random()`) para simular as incertezas do mundo real:

$$\text{Ativos}_{\text{novo}} = \text{Ativos}_{\text{atual}} \times \text{Taxa} \times \text{Fator Aleatório}$$


* **Condicionais de Alerta:** O código monitora se a reação atinge um limite crítico de crescimento, disparando avisos visuais de alerta ou conclusão estável.
* **Manipulação do DOM:** O resultado numérico gerado pelo loop é convertido dinamicamente em elementos de lista (`<li>`) e injetado na tela em tempo real, permitindo que o avaliador teste diferentes cenários matemáticos com apenas um clique.

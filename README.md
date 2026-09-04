# matematica2
 Modelagem Matemática e Programação: O Uso de Algoritmos na Inovação Tecnológica

## 1. Texto de Introdução do Trabalho

A matemática e a programação estão cada vez mais presentes no desenvolvimento das tecnologias utilizadas na sociedade. Sistemas de inteligência artificial, análise de dados, segurança digital, aplicativos, jogos e diversas outras tecnologias utilizam conceitos matemáticos para funcionar.

A matemática permite representar problemas e fenômenos por meio de fórmulas, funções, probabilidades e modelos. A programação, por sua vez, transforma esses modelos em algoritmos que podem ser executados por computadores.

Neste trabalho foi desenvolvido um projeto utilizando HTML, CSS e JavaScript, com o objetivo de demonstrar na prática como um conceito matemático pode ser transformado em uma simulação computacional.

O projeto consiste em uma simulação de crescimento em cadeia, na qual elementos podem gerar novos elementos de acordo com uma determinada taxa de crescimento e uma probabilidade de ativação. Os resultados são apresentados de forma visual por meio de contadores, tabela e gráfico.

## 2. Explicação da Atividade: Como o Site Foi Feito


O projeto desenvolvido consiste em uma página web que permite ao usuário configurar e executar uma simulação matemática.

A interface possui campos para definir:

- quantidade inicial de elementos;
- taxa de crescimento;
- probabilidade de ativação;
- número de etapas da simulação.

Também foram adicionados botões para controlar a execução:

Iniciar, Pausar, Continuar e Reiniciar.

Durante a simulação, o sistema mostra a etapa atual e a quantidade de elementos ativos.

Além disso, os resultados são registrados em uma tabela e representados graficamente.

---

3. METODOLOGIA

O desenvolvimento do projeto foi dividido em algumas etapas.

3.1 Criação da estrutura HTML

Primeiramente foi criada a estrutura da página utilizando HTML.

Foram adicionados os títulos, campos de entrada, botões, área de resultados, tabela e elemento destinado ao gráfico.

3.2 Desenvolvimento da aparência

Em seguida foi utilizado CSS para melhorar a aparência da página.

Foram definidos:

- cores;
- tamanho das letras;
- espaçamento;
- botões;
- caixas de informações;
- fundo da página;
- organização dos elementos.

O objetivo foi criar uma interface simples, organizada e adequada para uma apresentação escolar.

3.3 Desenvolvimento do algoritmo

A parte principal da aplicação foi desenvolvida utilizando JavaScript.

O programa recebe os valores definidos pelo usuário e inicia a simulação.

A cada etapa, o algoritmo analisa os elementos existentes e utiliza uma função aleatória para verificar quais serão ativados.

Um dos principais comandos utilizados foi:

Math.random()

Essa função gera um número aleatório entre 0 e 1, permitindo representar a probabilidade no modelo.

3.4 Estruturas de repetição

O programa utiliza uma estrutura "for" para analisar os elementos existentes.

De forma simplificada:

for (let i = 0; i < quantidade; i++) {
    // cálculo da simulação
}

Essa estrutura permite repetir uma determinada operação várias vezes automaticamente.

3.5 Atualização da simulação

Foi utilizada a função:

setInterval()

para fazer com que uma nova etapa fosse executada automaticamente depois de determinado intervalo de tempo.

Isso cria o efeito de animação e permite acompanhar a evolução da simulação.

3.6 Construção do gráfico

Os resultados são armazenados pelo programa e utilizados para desenhar um gráfico.

O gráfico permite observar visualmente a relação entre:

Etapas → Quantidade de elementos

Dessa maneira, o usuário consegue perceber com maior facilidade o comportamento do modelo.

---

4. FUNCIONAMENTO DO PROGRAMA

Para executar a simulação, o usuário informa os parâmetros desejados.

Um exemplo de configuração é:

Parâmetro| Valor
Quantidade inicial| 1
Taxa de crescimento| 2
Probabilidade| 70%
Número de etapas| 10

Após clicar em Iniciar, o programa começa a executar as etapas.

A cada etapa, cada elemento possui uma determinada chance de ser ativado. Quando ocorre a ativação, novos elementos são adicionados de acordo com a taxa de crescimento.

Como existe um componente aleatório, duas simulações utilizando os mesmos parâmetros podem apresentar resultados diferentes.



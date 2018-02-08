---
layout: default
---

Nesse curso, nós investigaremos a replicação de DNA e responderemos a seguinte pergunta: Onde em um genoma começa a replicação de DNA? Nós veremos que, para muitas bactérias, nós podemos responder essa pergunta com apenas alguns algoritmos simples para achar mensagens escondidas no genoma. Usaremos o genoma da bactéria Vibrio Cholerae como estudo de caso.

Esse curso possui duração de 20 horas, e nele  aprenderemos alguns conceitos básicos de programação, usando a linguagem [Python](https://www.python.org/) e [Jupyter notebooks](http://jupyter.org/) para responder a pergunta acima.

## Horários
O curso será ministrado de 05 a 09 de fevereiro de 2018 no LEC I, bloco 910.

Nos dias 05 a 08 será de 14:00 às 18:00 e no dia 09 de 08:00 às 12:00.

## Conteúdo

### Módulo I: Introdução e definição do problema (8h)
- Preparação da Replicação de DNA para ser resolvido de forma algorítmica;
- Definindo o problema de achar a origem (ori) da replicação num genoma.
- Dada uma origem, verificar se existe alguma mensagem escondida que faz com que a replicação se inicie ali (sequências frequentes)

Conceitos de programação abordados:
- Introdução à Sintaxe do Python
- Variáveis, Tipos de dados simples, Comentários
- Operações numéricas
- Strings e Saída de dados
- Condições e Estruturas de Controle
- Laços com for

### Módulo II: Contando sequências frequentes (8h)
- Identificar as sequências de tamanho k (k-mers) mais frequentes em um fragmento de DNA (abordagem ingênua)
- Lidando com duplicatas
- Identificando o k-mer mais provável de ser o início da replicação
- Computando o complemento reverso de uma fita de DNA
- Encontrando todas as ocorrências de uma sub-sequência em um fragmento de DNA

Conceitos de programação abordados:
- Listas e Dicionários
- Funções
- Laços
- Leitura de arquivos

### Módulo III: Explorando mensagens escondidas em múltiplos fragmentos de DNA (4h)
- Achando k-mers que aparecem muitas vezes dentro de um curto intervalo do genoma
- Comparando ori em diferentes genomas (Usaremos E. Coli)
- Assimetria da Replicação
- Calculando Estatísticas do DNA 
- Lidando com mutações

Conceitos de programação abordados
- Desenhando gráficos
- Funções, Cálculo de distância de Hamming

## Material Dia 1

#### Slides em formato pdf
* [Apresentação do Curso](https://drive.google.com/open?id=1JbgDdvtziyqTw2KzHFxZinicnNZ2rr_K)
* [Módulo I - Dia 1 - Introdução e Motivação](https://drive.google.com/open?id=1JjRxWLSCNLDl3rWO5SWIhpMpm3cEffuV)

#### Prática
* [Jupyter Notebooks](https://notebooks.azure.com/emanueles/libraries/biopython-dia1)

> Observação: As instruções para criação de conta e utilização dos notebooks na Azure estão nos slides.
> 

## Material Dia 2

#### Prática
* [Jupyter Notebooks](https://notebooks.azure.com/emanueles/libraries/biopython-dia2)

## Material Dia 3

#### Prática
* [Mais exercícios sobre o comando for (notebook avulso)](https://raw.githubusercontent.com/emanueles/biopython/master/notebooks/05-for-exercicios.ipynb)
* [Listas em Python (notebook avulso)](https://raw.githubusercontent.com/emanueles/biopython/master/notebooks/08-listas.ipynb)

## Material Dia 4

* [Dicionários em Python (notebook avulso)](https://raw.githubusercontent.com/emanueles/biopython/master/notebooks/09-dicionarios.ipynb)
* [Listas e Funções em Python (notebook avulso)](https://raw.githubusercontent.com/emanueles/biopython/master/notebooks/10-listas-funcoes.ipynb)


> Observação: Os notebooks avulsos devem ser adicionados à sua biblioteca do dia 2. Você pode usar as urls dos notebooks diretamente sem precisar fazer o download. As instruções de como fazer isso serão dadas no laboratório.

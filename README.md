# 2019.2 - Turbulência em Fluidos
# Experimento de Reynolds
## Integrantes
Roberto Diniz Ramalho da Rocha - 17/0021637  
Matheus Lobo Leite Ferreira - 17/0019161   
Isaac Moura de Alencar - 17/0059171

## Objetivos
<p>Identificar os diferentes tipos de regime hidráulico em tubeiras, determinar experimentalmente valores de vazões mássicas e volumétricas, determinar a velocidade do escoamento, o Número de Reynolds e consequentemente classificar o fluxo de acordo com o Número de Reynolds.<p>

## Requisitos de solução
* Observar e analisar o fluxo de água de acordo com o regime hidráulico estabelecido;
* Determinar os valores de vazão mássica e volumétrica experimentalmente;
* Calcular a velocidade do escoamento, o Número de Reynolds e classificar o fluxo de acordo com os dados obtidos.

## Escopo do experimento
* Após a montagem do aparato experimental, iremos abrir a válvula reguladora para regular o fluxo de água. Com o fluxo constante, iremos inserir tinta para observar o comportamento do fluxo;
* Quando o regime hidráulico for estabelecido, iremos medir o tempo e tomaremos medida do volume de água que sai pela válvula durante esse tempo;
* Após obter os dados necessários, iremos realizar os cálculos com o objetivo de classificar o fluido de acordo com o regime hidráulico.


## Avaliação de viabilidade 
<p> O experimento foi definido pelo grupo como viável, devido a simplicidade de execução e a possibilidade de realizar o mesmo na bancada hidráulica do Laboratório de Termofluidos da FGA. O experimento será bastante proveitoso para o grupo por estar diretamente relacionado com boa parte do conteúdo visto em sala de aula, auxiliando no entendimento do conteúdo. <p>

## Planejamento e preparação
### Teoria do experimento
<p> A partir da equação de Navier-Stokes é possível entender o comportamento de um escoamento, entretanto, há vários fatores que atrapalham uma análise geral do escoamento, como a transição do escoamento de laminar para turbulento.<p> 
<p> Desta maneira, para analisar a transição de um escoamento laminar para turbulento é preciso entender os conceitos de escoamento laminar e turbulento. Um escoamento laminar é aquele que é suave, permanente, com poucas perturbações e apresenta lâminas ou camadas. Nesse tipo de escoamento a viscosidade tem o papel de amortecer e evitar o surgimento de turbulência. Já escoamentos turbulentos, diferente dos laminares, o fluido se comporta de uma forma flutuante e agitado, fazendo com que suas partículas tenham movimentos aleatórios e irregulares. Esse tipo de escoamento é difícil de definir matematicamente, visto que a sua aleatoriedade atrapalha qualquer modelo matemático conhecido. <p>
<p> Com essas definições, é possível compreender o conceito por trás da transição de um escoamento laminar para turbulento. Diz-se que quando um escoamento deixa de ser laminar e se torna turbulento, houve um processo de mudança chamado transição para turbulento. Normalmente, a transição de um escoamento laminar para turbulento está diretamente associada com a variação do número de Reynolds, visto que, com um número de Reynolds baixo, normalmente, o escoamento é laminar, e, com o aumento desse número, o escoamento tende a mudar para turbulento. Assim, segundo White 2018, temos os seguintes comportamentos: <p>
  
*	0 < Re < 1 – Movimento laminar altamente viscoso;
*	1 < Re < 100 – Laminar, muito dependente do número de Reynolds;
*	100 < Re < 10^3 –  Laminar, teoria da camada limite; 
*	10^3 < Re < 10^4 – Transição para turbulência;
*	10^4 < Re < 10^6 – Turbulento, dependente do número de Reynolds;
*	10^6 < Re < ∞  - Turbulento, pouco dependente do número de Reynolds.
  
<p> Cabe salientar que não sempre o fluido vai se comportar dessa forma, tudo depende das situações em que o escoamento é exposto. <p>
<p> No intuito entender o escoamento viscoso em um duto, realizou-se, uma série de experimentos, para a compreensão do escoamento e sua transição para turbulento. Assim, encontrou-se a relação exposta na Fig. 1, em que mostra a perda de pressão em um escoamento de água em tubos longos. <p> 

  ![Figura 1](https://user-images.githubusercontent.com/42550287/69881364-98c55c00-12ab-11ea-99e1-e8d92c43e54f.gif)

Figura 1. Equação da queda de pressão encontrada pelo cientista G.H.L Hagen, onde E é o efeito de entrada.

<p> Entretanto, apesar da relação entre queda de pressão e velocidade do escoamento, a equação mostrada na Fig. 1 não descreve todos os escoamento, pois com um Q muito alto a fórmula não é válida. Assim, Reynolds mostrou que a mudança de um escoamento laminar para turbulento pode ser equacionado, conforme a Fig. 2. Nesse modelo, que recebeu o seu nome, Osborne Reynolds relacionou o coeficiente de viscosidade do fluido, massa específica, velocidade e diâmetro do duto, e, com essa relação e um conjunto de experimentos, pode mostrar que a transição de um escoamento laminar para turbulento ocorre em Re ~ 2300. <p>

![Figura 2](https://user-images.githubusercontent.com/42550287/69881482-f659a880-12ab-11ea-9e09-eb7b8d239dcf.gif)
  
Figura 2. Equacionamento do Número de Reynolds.

<p> Esse número é essencial para determinar o comportamento de um determinado fluido em um condição específica, de modo que, a partir dele é possível dizer se o fluido possui um escoamento laminar ou turbulento. <p> 
<p> Reynolds estudou a transição do escoamento de laminar para turbulento conforme mostrado a Fig. 3. Ele introduziu um filete de corante, com auxilio de uma seringa, em um escoamento em um duto, e, foi variando a vazão volumétrica do duto. A variação da vazão volumétrica está relacionada com a mudança da velocidade do escoamento, influenciando diretamente no número de Reynolds. <p>
  
  Figura 3

<p> Para calcular o Número de Reynolds, é necessário conhecer a velocidade do escoamento. Utilizaremos um Tubo de Venturi para encontrar a velocidade. O Tubo de Venturi funciona com base no Princípio de Bernoulli, que descreve o comportamento de um fluido movendo-se ao longo de uma linha de corrente. Para um fluido real, o Princípio de Bernoulli pode ser escrito da seguinte maneira: <p>
  
![Figura 4](https://user-images.githubusercontent.com/42550287/69881523-112c1d00-12ac-11ea-86dc-350e985215c5.gif)

Figura 4. Princípio de Bernoulli para fluidos reais.

<p> A Lei da Conservação das Massas para um volume de controle é: <p>
  
![Figura 5](https://user-images.githubusercontent.com/42550287/69881545-23a65680-12ac-11ea-960f-b0b8820ae8c4.gif)

Figura 5. Lei da Conservação das Massas para um volume de controle.

<p> Iremos considerar o escoamento em regime permanente e o fluido incompressível. Assim, a Lei da Conservação das Massas para um volume de controle fica da seguinte maneira: <p>

![Figura 6](https://user-images.githubusercontent.com/42550287/69881573-36b92680-12ac-11ea-8d44-c2cf2a171928.gif)

Figura 6. Lei da Conservação das Massas para um volume de controle em regime permanente e fluido incompressível

<p> Podemos reescrever a equação do Princípio de Bernoulli com base na Lei da Conservação das Massas da seguinte maneira: <p>
  Figura 7

### Cronograma 
Datas         | Tarefa
------------- | --------------------------
18/11 - 22/11 | Análise do experimento
25/11 - 28/11 | Realização do experimento 
28/11 - 01/12 | Confecção do relatório


### Dados a serem medidos e calculados
<p> Iremos medir experimentalmente a vazão volumétrica com base nos dados obtidos do Tubo de Venturi. Para isso, precisamos medir a variação de pressão, o diâmetro do tubo, o comprimento do tubo, a massa específica do fluido e a velocidade do escoamento. Após a realização das medições, iremos calcular o Número de Reynolds do escoamento com o intuito de classificar o mesmo. <p>

### Resultados esperados 
<p> Espera-se aferir pressão, velocidade e vazão do escoamento a partir dos instrumentos do laboratório para que seja possível classificar o fluxo do fluido de trabalho, que será água, e que assim seja possivel visualizar claramente o escoamento devido à tinta na água quando o mesmo estiver plenamente desenvolvido. Os resultados obtidos experimentalmente não necessariamente deverão coincidir com os cálculos analíticos realizados previamente, porém devem estar dentro de uma margem de erro estipulada pelo grupo em 10% para validar assim o experimento. <p>

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
* Após a montagem do aparato experimental, iremos abrir a válvula reguladora para regular o fluxo de água. Com o fluxo constante, iremos observar o comportamento do fluxo;
* Tomaremos as devidas medidas do aparato experimental e estimaremos o possível erro dessas medidas com o intuito de realizar um cálculo preciso;
* Quando o regime hidráulico for estabelecido, iremos medir a variação da altura da coluna de mercúrio do tubo de venturi;
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
  
![Figura 3](https://user-images.githubusercontent.com/42550287/69883374-9d414300-12b2-11ea-8c41-0488d1f1c50b.GIF)

Figura 3. Experimento realizado por Reynolds para estudar a transição de um escoamento laminar para turbulento.

<p> Para calcular o Número de Reynolds, é necessário conhecer a velocidade do escoamento. Utilizaremos um Tubo de Venturi para encontrar a velocidade. O Tubo de Venturi funciona com base no Princípio de Bernoulli, que descreve o comportamento de um fluido movendo-se ao longo de uma linha de corrente. O Princípio de Bernoulli pode ser escrito da seguinte maneira: <p>
  
![Figura 4](https://user-images.githubusercontent.com/42550287/69882258-6a954b80-12ae-11ea-96a1-b3a0c9523d38.gif)

Figura 4. Princípio de Bernoulli.

<p> A Lei da Conservação das Massas para um volume de controle é: <p>
  
![Figura 5](https://user-images.githubusercontent.com/42550287/69881545-23a65680-12ac-11ea-960f-b0b8820ae8c4.gif)

Figura 5. Lei da Conservação das Massas para um volume de controle.

<p> Iremos considerar o escoamento em regime permanente e o fluido incompressível. Assim, a Lei da Conservação das Massas para um volume de controle fica da seguinte maneira: <p>

![Figura 6](https://user-images.githubusercontent.com/42550287/69881573-36b92680-12ac-11ea-8d44-c2cf2a171928.gif)

Figura 6. Lei da Conservação das Massas para um volume de controle em regime permanente e fluido incompressível

<p> Podemos reescrever a equação do Princípio de Bernoulli com base na Lei da Conservação das Massas da seguinte maneira: <p>
  
 ![Figura 7](https://user-images.githubusercontent.com/42550287/69905597-a3a7eb80-1394-11ea-9e6d-b15ef9f969ec.gif)
  
 Figura 7. Relação vinda do Princípio de Bernoulli para calcular a velocidade de um escoamento utilizando um Tubo de Venturi.

### Cronograma 
Datas         | Tarefa                    | Divisão de tarefas
------------- | --------------------------|----------------------
18/11 - 22/11 | Análise do experimento    | Todos os membros
25/11 - 28/11 | Realização do experimento | Todos os membros
28/11 - 01/12 | Confecção do relatório    | Todos os membros


### Dados a serem medidos e calculados
<p> Iremos medir experimentalmente a vazão volumétrica com base nos dados obtidos do Tubo de Venturi. Para isso, precisamos medir a variação de pressão, o diâmetro do tubo, o comprimento do tubo, a massa específica do fluido e a velocidade do escoamento. Após a realização das medições, iremos calcular o Número de Reynolds do escoamento com o intuito de classificar o mesmo. <p>

### Resultados esperados 
<p> Espera-se aferir pressão, velocidade e vazão do escoamento a partir dos instrumentos do laboratório para que seja possível classificar o fluxo do fluido de trabalho, que será água, com base na teoria desenvolvida em sala de aula. Espera-se que assim seja possivel visualizar claramente o escoamento quando o mesmo estiver plenamente desenvolvido.  <p>

## Procedimentos experimentais 
<p>O primeiro procedimento a ser realizado foi a medição do Comprimento do duto com uma trena e dos diâmetros dos dutos utilizando-se de um paquímetro, após isso foi verificado se os instrumentos estavam ligados ao duto correto.<p>
<p>Após os procedimentos descritos posteriormente serem realizados a bancada foi ligada com a válvula que controla o escoamento totalmente aberta, com essa configuração aferiu-se a pressão com o tubo de venturi da bancada e filmou-se o escoamento na seção transparente do duto, tal procedimento foi repetido com a válvula aberta pela metade e a válvula aberta a aproximadamente ⅛<p>.

## Resultados

### Medições 

![Comprimento(L)](https://user-images.githubusercontent.com/42550287/69889789-9d9d0680-12d1-11ea-875d-7872903912bf.jpg)

Figura 8. Comprimento do duto.

![Diâmetro maior](https://user-images.githubusercontent.com/42550287/69889863-fd93ad00-12d1-11ea-9545-9250816797fd.jpg)

Figura 9. Diâmetro maior do duto.


![Medição do diâmetro maior](https://user-images.githubusercontent.com/42550287/69889886-1d2ad580-12d2-11ea-8850-da02a6620ae2.jpg)

Figura 10. Medição do diâmetro maior do duto.

### Válvula quase fechada


![Quase fechado](https://user-images.githubusercontent.com/42550287/69890264-a098f680-12d3-11ea-9bc0-363a911c0365.gif)

Gif 1. Fluxo de água com a válvula quase fechada.

![Quase fechado](https://user-images.githubusercontent.com/42550287/69890173-53b52000-12d3-11ea-90ee-796c7cc6c19d.jpg)

Figura 11. Variação de altura com a válvula quase fechada.

### Válvula aberta pela metade

![Meio aberto(2)](https://user-images.githubusercontent.com/42550287/69890396-33399580-12d4-11ea-852b-a08813d95570.gif)

Gif 2. Fluxo de água com a válvula aberta pela metade.

![Meio aberto](https://user-images.githubusercontent.com/42550287/69890103-1b154680-12d3-11ea-9205-70a2358f897a.jpg)

Figura 12.Variação de altura com a válvula aberta pela metade.

### Válvula toda aberta

![Todo aberto](https://user-images.githubusercontent.com/42550287/69889995-a7733980-12d2-11ea-946c-7128965c81c1.gif)

Gif 3. Fluxo de água com a válvula toda aberta.

![Todo aberto](https://user-images.githubusercontent.com/42550287/69890057-f7ea9700-12d2-11ea-8545-2fc8107cd239.jpg)

Figura 13. Variação de altura com a válvula toda aberta.

## Análise e conclusão
<p> Para a realização do cálculo da velocidade e do número de Reynolds, criou-se um código na liguagem C no programa CodeBlocks, como mostrado abaixo: <p>
  
  #include <stdio.h> 
  
  #include <stdlib.h> 
  
  #include <math.h> 

int main()
{
    <p> // declaracao da variaveis que serao utilizadas<p>
    <p>float h_mercurio, visc_agua, gravidade, diam_maior, diam_menor, massa_esp_agua, massa_esp_mercu;<p>
    <p>float comprimento_tubo, velocidade, numero_reynolds,auxiliar_1,razao_massa_es, razao_diam; <p>

    gravidade = 9.81000;
    diam_maior = 0.061000;
    diam_menor = 0.03960;
    massa_esp_mercu = 13560.00000;
    massa_esp_agua =1000.00000;
    visc_agua = 0.0500;
    comprimento_tubo = 0.93;
    razao_diam = diam_maior/diam_menor;
    razao_massa_es = massa_esp_mercu/massa_esp_agua;

    printf("Informe a altura da coluna de mercurio em metros: \n");
    scanf("%f",&h_mercurio);


    // Aplicar o valor encontrado na formula a seguir

    auxiliar_1 = (2*gravidade*h_mercurio*razao_massa_es)/((pow(razao_diam,4.0))-1);
    velocidade = sqrt(auxiliar_1);

    printf("A velocidade calculada foi de: %f\n", velocidade);

    //vamos agora calcular o numero de reynolds

    numero_reynolds = (massa_esp_agua*velocidade*comprimento_tubo)/visc_agua;

    printf("O numero de Reynolds calculado foi de: %.8f\n", numero_reynolds);

    return 0;
}

<p> Deste modo, criou-se um código em C para calcular o erro experimental, levando em consideração todas as medidas. O código feito está disponível abaixo: <p>
  
    #include <stdio.h> 
  
  #include <stdlib.h> 
  
  #include <math.h> 

int main()
{
 // declaracao da variaveis que serao utilizadas
    float h_mercurio, visc_agua, gravidade, diam_maior, diam_menor, massa_esp_agua, massa_esp_mercu, erroH, errodiam_menor;
    float comprimento_tubo, velocidade, numero_reynolds,auxiliar_1,razao_massa_es, razao_diam, errodiam_maior, errototal; 
    float errocomprimento_tubo;
    
    gravidade = 9.81000;
    diam_maior = 0.06100;
    diam_menor = 0.03960;
    massa_esp_mercu = 13560.00000;
    massa_esp_agua =1000.00000;
    visc_agua = 0.0500;
    comprimento_tubo = 0.93;
    errodiam_maior=0.0005
    errodiam_menor=0.0005
    erroH=0.0005
    errocomprimento_tubo=0.0005
    razao_diam = diam_maior/diam_menor;
    razao_massa_es = massa_esp_mercu/massa_esp_agua;
    printf("Informe a altura da coluna de mercurio em metros: \n");
    scanf("%f",&h_mercurio);
    float derivcomprimento = massa_esp_agua*(sqrt(2*gravidade*h_mercurio*razao_massa_es)/((pow(razao_diam,4.0))-1))/visc_agua;
    float derivH = massa_esp_agua*comprimento_tubo*0,5(sqrt(2*gravidade*razao_massa_es)/(h_mercurio*(pow(razao_diam,4.0))-1))/visc_agua;
    float aux1=comprimento_tubo*massa_esp_agua/visc_agua;
    float aux2= 2*sqrt(2)*razao_massa_es*h_mercurio*diam_maior*diam_maior*diam_maior;
    float Dmaior4 = diam_maior*diam_maior*diam_maior*diam_maior;
    float Dmenor4 = diam_menor*diam_menor*diam_menor*diam_menor;
    float aux3 = Dmenor4*((Dmaior4/Dmenor4)-1)*sqrt(h_mercurio*gravidade*razao_massa_es/((Dmaior4/Dmenor4)-1)));
    float derivdiam_maior =aux1*aux2/aux3;
    float aux4 = 2*sqrt(2)*Dmaior4*diam_menor*pow((h_mercurio*razao_massa_es/(Dmaior4*Dmenor4)), 3/2);
    float aux5 = h_mercurio*gravidade*razao_massa_es;
    float derivdiam_menor = aux1*aux4/aux5;
    float erro = sqrt(derivdiam_menor*errodiam_menor+derivdiam_maior*errodiam_maior+derivH*erroH+derivcomprimento*errocomprimento_tubo);
    printf("O erro relacionado ao numero de Reynolds calculado foi de: %.8f\n", errototal);
    return 0;
{

<p> A partir desses códigos foi possível extrair os dados da velocidade e o número de Reynolds e os seus respectivos erros. Deste modo calculou-se a velocidade e o Reynolds para três escoamentos com vazões diferentes, de modo que os resultados obtidos estão expressos na tabela a abaixo: <p>
  
  Válvula       | Velocidade calculada (m/s) | Número de Reynolds encontrado 
  ------------- | -------------------------- | -----------------------------
  Toda aberta   | 0,153088                   | 2847,438
  Meio aberta   | 0,095194                   | 1770,609
  Quase fechada | 0,074998                   | 1394,954
  
<p>Ao se observar a tabela obtida nota-se que dois dos escoamentos observados foram laminares(com número de Reynolds<2000) e um turbulento(Reynolds>2000), e nenhum em estado de transição(número de Reynolds próximo a 2000), diferente do que foi esperado do experimento(visualizar o escoamento laminar, turbulento e transicional). Tal divergência dos resultados esperados possivelmente pode ser justificada por 2 acontecimentos, o primeiro sendo a impossibilidade da utilização da tinta para melhor visualizar o escoamento já que poderia danificar o equipamento da Universidade de Brasília, o segundo sendo o difícil manuseio da válvula da bancada que controla o escoamento já que o intervalo onde o escoamento transicional ocorre é muito pequeno quando comparado ao laminar e principalmente ao turbulento. Com exceção dos problemas apresentados acima todos os objetivos do experimento foram atingidos(visualizar o escoamento e aferir vazão e velocidade do mesmo).<p>


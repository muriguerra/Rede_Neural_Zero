# Análise de Imagens de Dígitos de 0 a 9

Nosso problema consiste em analisar imagens de dígitos escritos à mão, cada uma com uma resolução de 28x28 pixels.

Cada um dos 784 pixels pode variar de 0 a 255, onde 0 representa a cor preta e 255 representa a cor branca.

## Representação de Dados

Para representar esses dígitos em nossa rede neural, organizaremos os dados em uma matriz. Essa matriz terá 784 linhas, onde cada linha representa uma característica de pixel. No entanto, para a entrada em nossa rede neural, faremos a transposição dessa matriz, transformando as linhas em colunas, de modo que cada coluna represente um pixel.

## Camadas da Rede Neural

Nossa rede neural será composta por três camadas:

1. **Camada de Entrada (Input Layer):** Esta camada receberá as 784 características como entrada.

2. **Camada Oculta (Hidden Layer):** A segunda camada, chamada de camada oculta, processará os dados intermediários.

3. **Camada de Saída (Output Layer):** A terceira e última camada, chamada de camada de saída, fornecerá o resultado final.

## Treinamento da Rede Neural

Após passar pelas camadas, calcularemos os erros dos parâmetros para, em seguida, atualizar esses parâmetros. Esse processo será repetido até que as previsões da rede estejam satisfatórias.

![esquema_rede](https://github.com/muriguerra/Rede_Neural_Zero/blob/master/data/rede%20neural.png?raw=true)

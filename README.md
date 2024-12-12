# Dimensionality-Reduction

Este repositório contém um exemplo de aplicação prática de redução de dimensionalidade usando imagens, projetado para ser executado no Google Colab. O código processa uma imagem, convertendo-a para tons de cinza e binário, e exibe os resultados lado a lado.
<br><br>

## Funcionalidades

- **Conversão para tons de cinza:** Reduz a dimensionalidade da imagem, eliminando informações de cores.
- **Conversão para binário:** Transforma a imagem em preto e branco com base em um limiar fixo.
- **Visualização comparativa:** Exibe a imagem original, a versão em tons de cinza e a versão binária em um gráfico.
<br>

## Configuração do Ambiente no Colab

1. Faça o upload da imagem `Lenna.png` para o ambiente do Colab. 
2. Crie uma pasta chamada `images/` no ambiente e coloque a imagem nela.

### Fluxo de Execução

1. **Carregar a imagem original:** 
   A imagem `Lenna.png` é carregada da pasta `images/`.
2. **Converter para tons de cinza:** 
   A imagem original é convertida para escala de cinza e salva como `Lenna_gray.jpg`.
3. **Converter para binário:** 
   A imagem em tons de cinza é binarizada utilizando um limiar fixo (128) e salva como `Lenna_binary.jpg`.
4. **Exibir as imagens processadas:** 
   As imagens original, em tons de cinza e binária são exibidas lado a lado.
<br><br>

## Exemplo de Resultado

Ao executar o código no Google Colab, o gráfico exibirá as três versões da imagem:

1. **Original Image:** Imagem em cores.
2. **Grayscale Image:** Imagem convertida para tons de cinza.
3. **Binary Image:** Imagem binarizada (preto e branco).

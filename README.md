# AtividadeCompressao
Sera realizado a compressao de uma imagem em Gray Scale utilizando Wavelet

Objetivo: Utilizar a transformada Wavelet para realizar a compressão de uma imagem, removendo componentes de alta frequência (detalhes) e reconstruindo a imagem comprimida.

Instruções:

    Carregue uma imagem em escala de cinza.
    1- Aplique a transformada Wavelet (usando 'haar') para decompor a imagem em componentes: (LL, LH, HL, HH)
    2- Descarte os componentes de detalhes  (LH, HL, HH) e mantenha apenas o componente de baixa frequência (LL)
    3- Realize a reconstrução inversa usando apenas o componente LL e visualize a imagem reconstruída.
    4- Desafio: Compare a imagem original com a imagem reconstruída. Avalie a qualidade da imagem comprimida.
  R: Ao comparar as imagens, é possível perceber que a imagem comprimida está próxima da qualidade da imagem original, embora apresente algumas diferenças, como o foco em áreas específicas da imagem reconstruida.


<img width="1463" alt="Captura de Tela 2024-11-06 às 17 18 26" src="https://github.com/user-attachments/assets/19090782-1112-46e8-8d65-4e94a534c76c">

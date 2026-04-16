# Questoes Objetivas de Computacao Grafica (HARDER)

Versao pensada no estilo de um professor que ensina Pygame, PyOpenGL e OpenCV com foco em jogos.

## Questoes

1. Em um jogo feito com Pygame, qual e o principal papel do loop principal (`game loop`)?

A) Instalar as bibliotecas do projeto  
B) Processar eventos, atualizar estados e redesenhar a cena continuamente  
C) Salvar o jogo automaticamente em arquivo texto  
D) Criar modelos 3D complexos sem programacao

2. Se o exercicio pede para desenhar um ponto na tela ao clicar com o mouse, qual evento deve ser verificado?

A) `KEYDOWN`  
B) `MOUSEBUTTONDOWN`  
C) `JOYAXISMOTION`  
D) `QUIT`

3. Para que os pontos clicados continuem aparecendo na tela durante a execucao do programa, o mais adequado e:

A) Desenhar o ponto uma unica vez e nunca mais atualizar a tela  
B) Salvar as posicoes em uma lista e redesenhar todos os pontos a cada quadro  
C) Fechar a janela apos cada clique  
D) Desenhar apenas o ultimo ponto clicado

4. Em uma ferramenta de desenho dentro de um jogo, um botao de reset normalmente serve para:

A) Aumentar o FPS  
B) Limpar os pontos, linhas ou formas desenhadas  
C) Trocar OpenGL por OpenCV  
D) Converter a cena de 3D para 2D

5. Se o programa deve ligar os pontos na ordem em que foram clicados, qual resultado visual e esperado?

A) Uma sequencia de segmentos formando um caminho  
B) Um circulo perfeito automatico  
C) Uma imagem em escala de cinza  
D) Um histograma da tela

6. Em exercicios com formas geometricas, a diferenca principal entre desenhar apenas a borda e desenhar a forma preenchida e:

A) A forma preenchida ocupa a area interna; a borda mostra apenas o contorno  
B) A borda sempre usa mais memoria que o preenchimento  
C) O preenchimento so existe em imagens 3D  
D) Nao existe diferenca visual entre os dois

7. Ao criar poligonos aleatorios com 3 a 10 lados em um jogo, qual valor abaixo NAO representa um poligono valido dentro da regra do exercicio?

A) 3 lados  
B) 5 lados  
C) 8 lados  
D) 11 lados

8. Em um objeto 3D renderizado com PyOpenGL, a rotacao e a transformacao usada para:

A) Mudar a cor do fundo  
B) Girar o objeto em torno de um ou mais eixos  
C) Aumentar a resolucao da janela  
D) Converter a imagem para escala de cinza

9. Em uma cena 3D, a translacao do objeto serve para:

A) Mover o objeto de posicao no espaco  
B) Alterar apenas o brilho da cena  
C) Apagar os vertices invisiveis  
D) Preencher o objeto com cor aleatoria

10. Em uma cena 3D de jogo, diminuir ou aumentar o tamanho de um cubo sem mudar sua forma corresponde a:

A) Interpolacao  
B) Escala  
C) Rasterizacao  
D) Colisao

11. Por que muitos exemplos em PyOpenGL usam `gluPerspective(...)` seguido de `glTranslatef(0, 0, -5)`?

A) Para desenhar o histograma da imagem  
B) Para mover o objeto para uma regiao visivel da camera com perspectiva  
C) Para ativar eventos do teclado  
D) Para transformar triangulos em quadrados

12. Se cada vertice de um triangulo recebe uma cor diferente no OpenGL, o interior do triangulo geralmente fica:

A) Com uma unica cor solida  
B) Transparente  
C) Com transicao gradual entre as cores  
D) Sem ser renderizado

13. No contexto de OpenCV, converter uma imagem para escala de cinza significa:

A) Reduzir a imagem a tons de intensidade, sem informacao de cor RGB completa  
B) Transformar a imagem em modelo 3D  
C) Desenhar poligonos sobre a imagem  
D) Dividir a imagem em varias janelas

14. O histograma de uma imagem em escala de cinza e util porque mostra:

A) A quantidade de pixels para cada nivel de intensidade  
B) A posicao exata dos vertices 3D  
C) A velocidade de renderizacao do jogo  
D) O numero de cliques do mouse por segundo

## Gabarito

1. B  
2. B  
3. B  
4. B  
5. A  
6. A  
7. D  
8. B  
9. A  
10. B  
11. B  
12. C  
13. A  
14. A

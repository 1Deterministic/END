<h2><strong>END</strong></h2>
<p>pt-br</p>
<p>
    END é um jogo de sobrevivência contra zumbis que tem absolutamente nenhum objetivo. Foi um projeto de faculdade que eu fiz há algum tempo, escrito na linguagem Racket. Foi planejado para ser modificado e uma espécie de referência de código para eventual uso futuro.
</p>
Gameplay
<p>
    Direcionais - movimentam o jogador
    a - Ativa o kit medico
    Espaco - atira
    Esc - pause (cuidado, o pause nao para o jogo, apenas abre o menu)
</p>
Estrutura do projeto
<p>
    Alguns elementos do jogo devem ser alterados fora do código. 
    As Imagens da pasta "Imagens" podem ser livremente editadas, atentando apenas para que suas resoluções sejam preservadas. Do contrário, a lógica do jogo deve ser alterada em locais como o detecção de colisão e renderização da imagem, mas nada que seja impossível de alterar. 
    A pasta "Recursos/Mapa" contém vários arquivos-texto com as coordenadas dos locais de colisão de cada parte do mapa (localizado em "Imagens/Mapa/Base"). Uma colisão é formada por quatro coordenadas: x inicial, y inicial, x final e y final. Ao mudar o mapa lembre-se de adequar os locais de colisão do arquivo texto referente a parte do mapa que foi editada. Jamais deixe uma linha em branco no fim do arquivo, o arquivo deve ter um numero de linhas multiplo de 4 para que os locais de colisao sejam carregados corretamente (você também pode editar isso, ou até o código inteiro como preferir xD).
    A pasta "Imagens/Mapa/Sobreposicao" contém imagens de partes do mapa que devem ser renderizadas por cima do jogador (locais onde o mapa o esconde). Essas imagens devem ser transparentes e conter o desenho somente da parte a ser impressa sobre os demais elementos do mapa.
    A pasta "Imagens/Jogador" contém os sprites do jogador que dão impressão de movimento. O nome da imagem refere a sua utilização no código: direção que o jogador anda e numero do sprite. 
</p>

<p>en-us</p>
<p>
    END is a zombie survival game that has absolutely no objective. It was a college project I made some time ago, written in Racket language. It was planned to be modified and some kind of code reference for eventual future use.
</p>
Gameplay
<p>
    Arrows - move the character
    a - activates the medkit
    space - shoot
    esc - pause (be careful, it doesnt stop the game, just opens the menu)
</p>
Project Structure
<p>
    Some elements of the game must be modified outside the code.
    The images on the "Imagens" folder can be modified as wish, just pay attention to maintain its resolutions. Otherwise, the game logic must be modified in colision detection and image rendering, no big deal. The "Recursos/Mapa" folder contains various text files with collision location coordinates for each part of the map (located in "Imagens/Mapa/Base"). A collision is formed by 4 coordinates: starting x, starting y, ending x and ending y. When changing the map remember to change the collision locations on its respecting text file. Never let a blank line at the end of the file, it must have a number of lines multiple of 4 for the collision locations to be loaded correctly (you can also change this, or even the entire code if you wish xD).
    The "Imagens/Mapa/Sobreposicao" folder contains images of parts of the map wich must be rendered over the character (locations where the map hides it). These images must be transparent and contain only the image of the part wich will be rendered over the other elements.
    The "Imagens/Jogador" folder contains the sprites for the character that gives movement effect. The name of the image is your application on the code: the direction the character walks and its number on the sequence. Baixo = down, cima = up, direita = right, esquerda = left.
</p>
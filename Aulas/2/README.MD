# Sumário

Iniciação ao Fusion 360, Uso dos exercicios do livro Simões moraes da pagina 126 para a utilização do software paramétrico. Fizemos até ao exercicio 9.
Funções Utilizadas: - sketch; - extrude;

--------------------------

[![Aula2](https://user-images.githubusercontent.com/17902658/196556621-5b274900-4ff4-4bbf-a2d5-80456d6c3683.png)](https://www.youtube.com/watch?v=iyjRYjhyIkw)

----------------------------

Fusion 360

Este software é paramétrico o que significa que usa parametros para defenir os modelos 3d "peças" de forma rigorosa 
e podem utilizar estas peças para fabricação diretamente do program quer seja impressão 3d cnc ou corte laser.

![image](https://user-images.githubusercontent.com/17902658/196098636-dfe5d462-300f-4e40-87d3-fc3230eac8bb.png)

1. Painel de Ficheiros ou informação
2. Barra de Desenho de peças - existem outras como por exemplo renderização ou Maquinação por CNC
3. Arvore de peças e Conjuntos
4. View Port - Janela de visualização de desenho
5. Barra de solidos - Onde a maioria da acção acontece
6. Barra de Superficies - Vamos falar sobre ela mais para o fim do curso e para que serve.
7. Barra de malhas triangulares ou quadradas - serve por exemplo para reparar STLS e convertelos para solidos editaveis no fusion
8. Barra de SHEET METAL - Modulo de chapa quinada
9. Barra Plastic - Podem não ter esta barra porque pode não fazer parte do modulo maker/free mas são ferramentas novas mais para moldação
10. Barra Utilidades - é mesmo isso utilidades de exportação e outras como extenção do Fusion
11. Informações a activação de extenções
12. Estado de trabalho - indica se estam ou não liogados a cloud
13. notificações, normalmente utilizado para informar de actualizações - devem estar atentos as novas verções e dentro deste separador aparece whats new é importante estar dentro das novas fuincionalidades.
14. Ajuda- uma das funcionalidades menos procuradas nos softwares e das mais importantes deves procurar o que precisas aqui primeiro do que em qualquer outro lado.
15. criar novo Gravar exportar e muitas outras opções
16. GRAVAR
17. Retroceder | avançar
18. Ferramentas de visualização e Vports
19. Comentarios para equipas
20. Barra do tempo de parametros (das barras mais importantes para a modelação de peças no fusion)

______________________________

Para fazer:

1. PAN - é como no AUTOCAD butão do meio do rato e movimentar
2. ZOOM - Com a roda de scrool
3. Orbit - Shift + Botão do meio do rato

_____________________________

# Desenho

1. Antes de começar, como podem ter limitações de peças por causa da licença gratuita, devem criar multiplas peças uma por exercico dentro do fusion
como na imagem seguinte. Podem dar o nome de "EXERCICIO1"
![image](https://user-images.githubusercontent.com/17902658/196100727-06eebdf6-c148-4dab-bfba-9386ea9cadc5.png)

2. Cirar o Skech carregando no 1 e selecionando o plano carregando no 2
![image](https://user-images.githubusercontent.com/17902658/196105675-84051fd1-80be-498c-90ed-7100a1016aab.png)

3. Desenhar a vista frontal Tendo em conta que:
  - A amarelo é a barra de senho 2D
  - A azul a barra de constrangimentos
  - A barra de opçõpes de desenho 2D
  
- Sendo o Fusion um programa de 3D Paramétrico CAD-CAE ele para poder alterar parametros o desenho tem que ser defenido do ponto de vista geométrico, ou  seja o programa tem de compreender as regras do modelo exemplo se um quadrado estiver sempre no centro de outro isso tem de ser defenido e também os tamanhos dos objectos, quando um objecto esta completamente defenido esta todo a preto quando contem porções a azul significa que não esta defenido, devem sempre so sair do sketch quando estiver tudo a preto. !IMPORTANTE!

![image](https://user-images.githubusercontent.com/17902658/196103973-39fa39a6-940c-45f0-9b4e-69b70269aafa.png)

- Para criar a vista de frente a cima, temos que criar novo rectangulo (1) mas tambem podes pressionar a tecla "r" devemos colocar o primeiro ponto na origem, primeiro desenhas os rectangulos a "olhometro" so depois das as medidas (não tem que ser assim mas faz como te digo o GURU sou eu! mais tarde vais perceber que este é nma generalidade o melhor workflow) com o comando dimention (2) ou pressionas a tecla "d"
Cada unidade eu estipuilei 10mm por isso e multiplicar 10mm pelo numero de unidades.
Replica o desenho como na imagem.

![image](https://user-images.githubusercontent.com/17902658/196561370-2dc7f2b7-a863-42a5-95e3-5309cb0a4c86.png)

- Para fazr a vista de topo vamos repetir o processo anterior mas no plano XY, primeiro carrega no botão skecht (1) e depois seleciona o plano XY (2)
Ao selecionares o plano o fusion por defeito roda para colocar a vista orotgonal, neste caso para visualizar melhor é mais facil rodar a vista com o orbit e fazer a vista em perspectiva tal e qual eu fiz no video.

4. No passo seguinte podemos vamos contruir a vista de cima do exercicio, como podemos ver estou a usar tudo com linhas de desenho e nenhuma linha de construção e o motivo tem a ver com o fusion não ler as linhas de cosntrução como areas de uteis para desenho e a unica coisa que pode fazer é ver os pontos ou usalas como eixos.
Temos de desenhar a vista de cima para isso começamos pode desenhar o rectangulho de silhueta do desenho (o maior) com o primeiro ponto na origem arrastamos para ser ligeiramente maior que o nesseçário, após queremos fazer com que a linha (3) se alinhe com o ponto (4) para isso temos que selecionar o cointrain colinear (11) depois selecionar o (3) só depois o (4) depois pressionando a tecla "d" (5) podem adicionar a medida de 3 unidades á pçrofundidade.
![image](https://user-images.githubusercontent.com/17902658/196636009-6ae7b066-0663-40f9-837d-b4f628e6b18d.png)
 - Depois podemos passar ao  quadrado mais pequeno (6) (7), o melhor é contruir fora de todo o desenho um quadrado sem medidas e depois escolher o lado paralelo ao (3)  o reta (6) e ecolher outro constrangimento o midpoint este centra pontos em rectas ou retas em retas existem outras formas de fazer isto mas esta é a mais simples para frente vamos dar mais constrangimentos que podem completar este, depois so falta dizer que o (7) é = (12) a uma das arestas que não esta selecionada no seguinte quadrado.
 - o quadrado maior é feito da mesma forma que o anterior mas no sitio correto. !
 > !NOTA! so conseguimos usar os pontos do desenho anterior porque fazem parte do nosso plano de trabalho noutros exercicios mostro a ferramenta para projectar pontos está atento!
5. Extrusão e criação de sólidos vamos analizar o quadro EDIT FEATURE
 - (1) Tipo  : Queremos solido (mais tarde explico o outro tipo);
 - (2) Perfiz ou perimetros - como ja deves ter percebido o fusion procurar nos sckehts todos os perimetros estes podem ser desenhos ou faces se forem planas;
 - (3) START - de onde começa a extrusão? (10) a partir do sketch, (11) Com um offset "espaçamento" relativamente ao desenho pode ser posiotivo ou negativo, (12) a partir do objecto pode ser qualquer ponto ou face criados anteriormente (por defeito escolher sempre pontos da referencia inicial bidimenciona se começarem a escolher faces 3d com o tempo o desenho fica mais pesado e mais passivel de perder referencias)
 - (4) Direcção de extrusão - (13)Para um lado (se derem um valor positio vai para um lado mas se derem um negativo vai para o outro), (14) Dois lados - se escolherem esta opção vai aparecervos o extend tipe duas vezes(5) para poderm escolher uma das 3 opções nas duas direcções, (15) Simétrico = para os dois lado podem dar a medida total ou de metade. 
 - (5) Colocar a distancia (16) , para o objecto (17) para o maximo (18) esta feature so funciona se ja tiverem alguim modelo 3d no documento e tenta ir até o ponto mais afawstado que existir no volume desenhado antes.
 - (6) esta opção so aparece porque escolhemos a opção (17) na (5) e basicamente é para escolhermos o ponto que pertendemos que seja a bitola maxima de extrusão
 - (7) se qeremos dar algum afastamento mesuravel do ponto
 - (8) se quieremos dar algum angulo as paredes da extrusão, muito util para criar saidas para moldes
 - (9) Tipo de operação (19) aditiva - (20) subtractiva - (21) Intersecção - (22) novo solido
 
![image](https://user-images.githubusercontent.com/17902658/196649245-f69cb8b3-6f51-4e09-afab-14a25db8e448.png)

 - Depos de analizar vamos construir o sólido
  - começamos por selecionar os perimetros (24,25,26) no ponto (2);
  - escolhemos as outras opções como na imagem;
  - (6) aqui escolhemos o ponto do desenho (23);
 - Desta forma criamos a primeira faze do solido.


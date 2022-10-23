# Sumário

Iniciação ao Fusion 360; Resolução dos exercícios do livro Simões Moraes da página 126 com conteúdo para a utilização do software paramétrico; Resolução até ao exercício 9.
Funções utilizadas: - sketch; - extrude;

--------------------------

[![Aula2](https://user-images.githubusercontent.com/17902658/196556621-5b274900-4ff4-4bbf-a2d5-80456d6c3683.png)](https://www.youtube.com/watch?v=iyjRYjhyIkw)

----------------------------

Fusion 360

Este software é paramétrico o que significa que usa parâmetros para definir de forma rigorosa os modelos 3d, isto é, as "peças". Estas peças poderão ser usadas para fabricação diretamente em programas, quer sejam de impressão 3d, CNC ou corte laser.

![image](https://user-images.githubusercontent.com/17902658/196098636-dfe5d462-300f-4e40-87d3-fc3230eac8bb.png)

1. Painel de Ficheiros ou informação
2. Barra de Desenho de peças - existem outras como por exemplo renderização ou Maquinação por CNC
3. Árvore de peças e conjuntos
4. View Port - Janela de visualização de desenho
5. Barra de sólidos - Onde a maioria da ação acontece
6. Barra de superfícies - Vamos falar sobre ela mais para o fim do curso e para que serve.
7. Barra de malhas triangulares ou quadradas - serve para, por exemplo, reparar STLS e converter os mesmos para sólidos editáveis no Fusion
8. Barra de SHEET METAL - Modulo de chapa quinada
9. Barra Plastic - Podem não ter esta barra porque pode não fazer parte do modulo maker/free mas são ferramentas novas mais para uso em moldação
10. Barra Utilidades – Tal como o nome indica são utilidades de exportação e outras como extensão do Fusion
11. Informações a ativação de extensões
12. Estado de trabalho - indica se estão ou não ligados á cloud
13. Notificações, normalmente utilizado para informar de atualizações - devem estar atentos às novas versões. Dentro deste separador aparece ‘whats new’, sendo importante estar dentro das novas funcionalidades.
14. Ajuda- uma das funcionalidades menos procuradas nos softwares e das mais importantes! Deves procurar o que precisas aqui primeiro do que em qualquer outro lado.
15. Criar novo, gravar, exportar e muitas outras opções
16. GRAVAR
17. Retroceder | avançar
18. Ferramentas de visualização e Vports
19. Comentários para equipas
20. Barra do tempo de parâmetros (das barras mais importantes para a modelação de peças no Fusion)

______________________________

Para fazer:

1. PAN - é como no AUTOCAD botão do meio do rato e movimentar
2. ZOOM - Com a roda de scroll
3. Orbit - Shift + Botão do meio do rato

_____________________________

# Desenho

1. Antes de começar, e como podem ter limitações de peças por causa da licença gratuita, devem criar múltiplas peças, uma por exercício, dentro do Fusion tal como observado na imagem seguinte. Podem dar o nome de "EXERCICIO1"
![image](https://user-images.githubusercontent.com/17902658/196100727-06eebdf6-c148-4dab-bfba-9386ea9cadc5.png)

2. Criar o Skech carregando no 1 e selecionando o plano carregando no 2

![image](https://user-images.githubusercontent.com/17902658/196105675-84051fd1-80be-498c-90ed-7100a1016aab.png)

3. Desenhar a vista frontal, tendo em conta que:
  - A amarelo é a barra de desenho 2D
  - A azul a barra de constrangimentos
  - A vermelho a barra de opções de desenho 2D
  - Sendo o Fusion um programa de 3D Paramétrico CAD-CAE, para se poder alterar parâmetros, o desenho tem que ser definido do ponto de vista geométrico, ou seja o programa tem de compreender as regras do modelo. Por exemplo se um quadrado estiver sempre no centro de outro isso tem de ser definido tal como os tamanhos dos objetos. Quando um objeto está completamente definido este fica todo a preto. Quando apresenta porções a azul, significa que não esta definido, e como tal devem sempre só sair do sketch quando estiver tudo a preto. !IMPORTANTE!

![image](https://user-images.githubusercontent.com/17902658/196103973-39fa39a6-940c-45f0-9b4e-69b70269aafa.png)

- Para criar a vista de frente a cima, temos que criar um novo retângulo (1) mas também podes pressionar a tecla "r". Devemos colocar o primeiro ponto na origem, e primeiro desenhas os retângulos a "olhometro" e só depois atribuis as medidas (nota: não tem que ser assim, mas faz como te digo, o GURU sou eu! Mais tarde vais perceber que este é na generalidade o melhor workflow). As medidas são atribuídas com o comando dimention (2) ou pressionando a tecla "d".
Cada unidade eu estipulei a 10mm, por isso é multiplicar 10mm pelo número de unidades.
Replica o desenho como na imagem.

![image](https://user-images.githubusercontent.com/17902658/196561370-2dc7f2b7-a863-42a5-95e3-5309cb0a4c86.png)

- Para fazer a vista de topo vamos repetir o processo anterior mas no plano XY, primeiro carrega no botão sketch (1) e depois seleciona o plano XY (2)
Ao selecionares o plano, o Fusion por defeito roda para colocar a vista ortogonal. Neste caso para visualizar melhor é mais fácil rodar a vista com o orbit e fazer a vista em perspetiva tal e qual como eu fiz no vídeo.

4. No passo seguinte vamos contruir a vista de cima do exercício. Como podemos ver, estou a usar tudo com linhas de desenho e nenhuma linha de construção, e o motivo tem que ver com o Fusion não ler as linhas de construção como áreas uteis para desenho. A única coisa que pode fazer é ver os pontos ou usar os mesmos como eixos.

Temos de desenhar a vista de cima para isso começamos por desenhar o retângulo de silhueta do desenho (o maior) com o primeiro ponto na origem. Arrastamos para ser ligeiramente maior que o necessário. Necessitamos fazer com que a linha (3) se alinhe com o ponto (4). Para isso temos que selecionar o constrain colinear (11), depois selecionar o (3), e só depois o (4). Pressionando a tecla "d" (5) podem adicionar a medida de 3 unidades á profundidade.

![image](https://user-images.githubusercontent.com/17902658/196636009-6ae7b066-0663-40f9-837d-b4f628e6b18d.png)

 - Depois podemos passar ao  quadrado mais pequeno (6) (7), o melhor é contruir fora de todo o desenho um quadrado sem medidas e depois escolher o lado paralelo ao (3) à reta (6) e escolher outro constrangimento, o midpoint. Este centra pontos em retas ou retas em retas. Existem outras formas de fazer isto, mas esta é a mais simples. Para frente vamos dar mais constrangimentos que podem completar este. Depois só falta indicar que o (7) é = (12) a uma das arestas que não está selecionada no seguinte quadrado.
 - O quadrado maior é feito da mesma forma que o anterior mas no sitio correto!
 > !NOTA! Só conseguimos usar os pontos do desenho anterior porque fazem parte do nosso plano de trabalho. Noutros exercícios mostro a ferramenta para projetar pontos. Está atento!
5. Extrusão e criação de sólidos vamos analisar o quadro EDIT FEATURE
 - (1) Tipo  : Queremos sólido (mais tarde explico o outro tipo);
 - (2) Perfiz ou perímetros - como já deves ter percebido o Fusion procura nos sketch todos os perímetros. Estes podem ser desenhos ou faces se forem planas;
 - (3) START - de onde começa a extrusão? (10) a partir do sketch, (11) Com um offset "espaçamento" relativamente ao desenho que pode ser positivo ou negativo, (12) a partir do objeto onde pode ser qualquer ponto ou face criados anteriormente (por defeito escolher sempre pontos do referencia inicial bidimensional. Se começarem a escolher faces 3d, com o tempo, o desenho fica mais pesado e mais passível de perder referências)
 - (4) Direção de extrusão - (13) Para um lado (se derem um valor positivo vai para um lado mas se derem um negativo vai para o outro); (14) Dois lados - se escolherem esta opção vai aparecer o ‘extend type’ duas vezes; (5) para poderem escolher uma das 3 opções nas duas direções; (15) Simétrico = para os dois lado podem dar a medida total ou de metade. 
 - (5) Colocar a distância (16), para o objeto (17) e para o máximo (18). Esta feature só funciona se já tiverem algum modelo 3d no documento. Tenta ir até o ponto mais afastado que existir no volume desenhado antes.
 - (6) esta opção só aparece porque escolhemos a opção (17) na (5) e basicamente é para escolhermos o ponto que pretendemos que seja a bitola máxima de extrusão.
 - (7) se queremos dar algum afastamento mesurável do ponto
 - (8) se queremos dar algum angulo as paredes da extrusão. Muito útil para criar saídas para moldes
 - (9) Tipo de operação: (19) aditiva - (20) subtrativa - (21) Intersecção - (22) novo sólido
 
![image](https://user-images.githubusercontent.com/17902658/196649245-f69cb8b3-6f51-4e09-afab-14a25db8e448.png)

6. Depois de analisar vamos construir o sólido
  - Começamos por selecionar os perímetros (24,25,26) no ponto (2);
  - Escolhemos as outras opções como na imagem;
  - (6) aqui escolhemos o ponto do desenho (23);
 - Desta forma criamos a primeira fase do sólido.
 7. Temos que selecionar o quadrado grande vista de topo (1) até ao ponto (2), verificar se esta em cut (3)  
![image](https://user-images.githubusercontent.com/17902658/197073503-7a08dfdd-714c-468e-b98a-b093f531474a.png)
 
 8.Usar o rectangulo na vista de frente (1) depois começar a extrudir (4) a partir do ponto (2) até ao ponto (6) (3)
 
 ![image](https://user-images.githubusercontent.com/17902658/197074053-86a6414a-e24e-4ee0-ac79-8605099fadcd.png)

Pronto o primeiro exercicio todos os outros são similares vê o video do youtube se tiveres alguma duvida!



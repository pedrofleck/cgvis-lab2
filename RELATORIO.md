# Relatório - Coelinhos do Brasil

## Dados do aluno

- **Cartão UFRGS**: 00233700
- **Nome**: Pedro H. F. Fleck

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

1) Crie 25 coelhos verdes que andem pulando em torno da borda de um retângulo, eles precisam ser menores pra caber no plano, ter uma animação de pulo seguindo uma senoide (animação por tempo) e girar 90º nas curvas sempre olhando pra frente do caminho que estão fazendo.

2) Ajuste a posição na qual os coelhos observam considerando que o modelo aponta para -x.

3) Ajuste a altura do plano (que originalmente estava em -1f) para que as "patas" do coelho toquem o chão.

4) Modifique para seguir o sentido horário

5) Faça uma oscilação sincronizada com 2 * sen de uma rotação no eixo z

6) Crie 14 coelhos amarelos e faça os andar num losângo seguindo a distância das arestas a 1,7 módulos das bordas do retângulo, faça o pré-cálculo da rotação de cada aresta usando a tangente, faça mapeamento e interpolação linear para mapear a posição com base na distância percorrida. Mantenha as animações iguais à do retângulo.

7) Crie 8 coelhos azuis e faça-os andar num círculo de raio 0,875f (3,5 módulos, em relação ao 5/3,5 da largura, seguindo as dimensões oficiais da Bandeira), a posição x e z segue a equação paramétrica do círculo, a orientação (y) acompanha a tangente do círculo, a distância para a animação do pulo é convertida para distância linear (ângulo X raio) para aproveitar a mesma lógica da animação.

8) Implemente o chapéu a partir da esfera achatada (escala da matriz 0,35, 0,15, 0,35) e transladada para o topo da cabeça (-0.6f, 0.6f, 0.05f) herdando a matriz model do coelho.

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

- Tive problemas para o Cmake do projeto rodar no Windows que utilizei um agente de IA para resolver.

- Tive dificuldade em começar, precisei de ajuda da IA para entender as partes do código e quais transformações matemáticas poderiam ser necessárias. Creio que estar enferrujado com programação (atualmente estou praticamente focado somente em hardware) possa ter auxiliado nisso.

## Você acha que conseguiu resolver o problema de forma adequada?

- Praticamente sim, creio que ficou similar o suficiente, entendo que o formato da bandeira ficou um pouco diferente (propositalmente) e a escala ou do chão ou dos coelhos diferente do resultado final, mas creio que isso não afete o que foi desejado.

- Porém, faltou a parte das curvas suaves, tendo o retângulo e o losango curvas imediatas de 90º.

- Além disso, a iluminação parece diferente, creio que seja as propriedades do material pois a luz parece vir do mesmo local no meu teste e no exemplo em vídeo, mas, não sei se isso é parte do trabalho e, como exigia muita tentativa e erro com os materiais sem saber exatamente o que era desejado, deixei a iluminação original.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

- O losango e o círculo estão seguindo as dimensões oficiais da Bandeira do Brasil (20 módulos de largura, 14 de altura, com as bordas dos losangos a 1,7 módulos de distância das bordas do retângulo e o círculo azul com 3,5 módulos de raio), o que pode significar alguma diferença em relação ao original.

- Foi feita uma entrega parcial antes do deadline mas continuei tentando completar a solução do problema, caso ainda considere a entrega atrasada!

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

- N/A.

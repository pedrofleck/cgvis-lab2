# Relatório - Coelinhos do Brasil

## Dados do aluno

- **Cartão UFRGS**: 00233700
- **Nome**: Pedro H. F. Fleck

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

1) Crie 25 coelhos verdes que andem pulando em torno da borda de um retângulo, eles precisam ser menores pra caber no plano, ter uma animação de pulo seguindo uma senoide (animação por tempo) e girar 90º nas curvas sempre olhando pra frente do caminho que estão fazendo.

2) Ajuste a posição na qual os coelhos observam considerando que o modelo aponta para -x.

3) Ajuste a altura do plano (que originalmente estava em -1f) para que as "patas" do coelho toquem o chão.

4) Modifique para seguir o sentido horário

5) Faça uma oscilação sincronizada com 2 * sen de uma rotação no eixo z

6) Crie 14 coelhos amarelos e faça os andar num losângo (...)

7) Crie 8 coelhos azuis e faça-os andar num círculo de raio 0,875f (3,5 módulos, em relação ao 5/3,5 da largura, seguindo as dimensões oficiais da Bandeira), a posição x e z segue a equação paramétrica do círculo, a orientação (y) acompanha a tangente do círculo, a distância para a animação do pulo é convertida para distância linear (ângulo X raio) para aproveitar a mesma lógica da animação.

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

- Tive problemas para o Cmake do projeto rodar no Windows que utilizei um agente de IA para resolver.

## Você acha que conseguiu resolver o problema de forma adequada?

Entrega parcial no deadline.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

- O losango e o círculo estão seguindo as dimensões oficiais da Bandeira do Brasil (20 módulos de largura, 14 de altura, com as bordas dos losangos a 1,7 módulos de distância das bordas do retângulo e o círculo azul com 3,5 módulos de raio), o que pode significar alguma diferença em relação ao original.

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>

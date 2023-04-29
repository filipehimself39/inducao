# indução

![menina_na_banheira](https://user-images.githubusercontent.com/128937668/235308224-b2f715fa-b2f4-4d3e-9083-3b12889c8874.gif)

## Introdução ao pensamento matemático (*livro 2*)

* Em Matemática, não basta intuir, não basta testar: é preciso demonstrar.

Nos tempos atuais, estima-se que mais de 100.000 novos resultados matemáticos são publicados anualmente. Esses resultados podem ser de vários tipos: propriedades e classificações de objetos matemáticos, novos métodos e algoritmos, etc.

Cada um desses resultados é fruto de um trabalho que envolve duas etapas: a heurística e a demonstração.

A heurística consiste no trabalho de descoberta dos resultados matemáticos. Usando-se de casos particulares, fazendo-se analogias, simulações, ou mesmo usando-se simplesmente nossa experiência e intuição, produzimos ou enunciamos o que chamamos usualmente de **conjectura:** a afirmação de um resultado matemático do qual temos alguma evidência da veracidade, mas não a certeza.

Dizendo de um outro modo: embora estejamos até dispostos a apostar na veracidade da afirmação feita por uma conjectura, estamos bem cientes de que há um risco de que a mesma corresponda a um resultado falso.

Uma vez que intuímos uma conjectura, passa-se à sua **demonstração**.

Essa objetiva dar condições para que tanto a pessoa que intuiu a conjectura, como a qualquer outra pessoa, convença-se de modo indubitável da sua veracidade ou, se for o caso, da sua falsidade.

O produto da demonstração é o que chamamos prova. Toda prova que demonstre a veracidade de uma dada conjectura consiste num encadeamento de deduções que mostram que o resultado afirmado pela conjectura é uma consequência lógica e irrefutável de resultados matemáticos já aceitos como verdadeiros.

Por outro lado, uma prova que demonstre a falsidade de uma conjectura resume-se, em geral, na exibição de um **contraexemplo**, ou seja, na exibição de uma situação particular (exemplo) onde o que é afirmado pela conjectura não ocorre.

Uma conjectura que tenha sido demonstrada ser verdadeira passa a ter o status de teorema, de verdade matematicamente demonstrada. Por outro lado, chamamos de conjectura falsa a toda conjectura que tenha sido demonstrada não ser verdadeira.

---

e **Notas sobre indução** (*bastante útil*).

## Indução Matemática (capítulo primeiro)

Dentre todos os números que o ser humano já considerou, os números naturais foram os primeiros a serem criados, inicialmente com o intuito de contar.

**O Princípio de Indução Matemática**

Mas, afinal, o que é o conjunto N dos números naturais?

Bem, podemos intuitivamente descrevê-lo dizendo quais são os seus elementos; eles são os números reais da forma:

1, 2 = 1+1, 3 = 2+1 = (1+1)+1, 4 = 3+1 = (1+1+1)+1,...

Ocorre, porém, que dificilmente poderemos provar alguma propriedade desses números utilizando apenas esta descrição, pois, apesar de sabermos intuitivamente quais são os números que os pontinhos acima representam, teríamos dificuldade em descrevê-los de modo suficientemente explícito.

Uma alternativa consiste em dar algumas propriedades que caracterizem de modo inequívoco o conjunto dos naturais dentro do conjunto dos números reais.

Inicialmente, considere um subconjunto S dos números reais que possui as seguintes propriedades:

1. S contém o número 1.

2. Toda vez que S contém um número n, ele necesariamente contém o número n + 1.

3. Não existe subconjunto próprio de S satisfazendo as condições (1) e (2).

## Tradução da parte 1

### Inglês
This is the first of five videos on phylogenetic reconstruction. 
Today. We're just going to, in this video, we're just going to introduce the topic.

All right, phylogenetic reconstruction. We have already talked about different ways of doing classification systems, 
and we have shown that the cladistic or phylogenetic approach really has the strongest biological and philosophical 
foundation for figuring out evolutionary relationships. So the question then becomes, how do we actually infer phylogenies? 
There are a very, very small number of speciation events that human beings have actually witnessed.

The vast majority, millions of them, have not been witnessed. And so how are we going to infer the actual set of evolutionary 
relationships of species? Today we're going to look at just one of the methods. It's called parsimony.

And there are methods besides parsimony. There are ways of doing things by what we call distance measures, maximum likelihood, 
and something called bayesian inference. Those last two are statistical approaches, and they're very important, but we don't have 
time to consider them all.

So we're going to focus on parsimony because it's more straightforward. All right, so the goal of phylogenetics, if you haven't 
guessed it already, is to recreate the ancestor descendant relationships among species. So our goal is to build phylogenetic trees, 
and this is necessarily going to be a branching pattern.

And this should make sense to you based on the discussion we've already had on speciation, because usually we have an original parental
species that divides into two or more additional species. And so that's going to create a branching pattern when we represent this 
graphically. We've also talked about the fact that you can have reticulate evolution, hybrid speciation, but we're going to be ignoring 
that for this part of the class.

All right, so first, let's make sure we understand how to read and interpret phylogenetic trees. So trees have different parts. Most trees 
are rooted trees.

So the base of the tree is what we call the root here. It's where things begin. And then whenever we have a speciation event, we have 
what we call a node.

So here, this branch represents an ancestral species, and then that splits into two new species represented by these branches. Now, 
if you ever talk to somebody in computer science, they will call these branches edges, but they mean the same thing that we do when we 
call them branches. And then here at the tips of the tree, we have what are called either leaves or taxa or species.

And so these are the different organisms, organisms that we're trying to reconstruct the relationships for. Now, another thing that can 
be tricky about reading phylogenetic trees is that the order at which things appear on the tips often actually means absolutely nothing. 
What really matters when we're dealing with a phylogenetic tree is the relationships of things through the actual branches on the tree.

And so one way to think about this is that each node on the tree can spin. Now, before we get to that, let's look at one other thing here. 
This dimension on the tree is time.

So time is flowing from the root up to the tips, where we have our present day species. This dimension here, however, actually means nothing.
It's just there so that we can see the relationships of the species.

If we made a phylogenetic tree one dimensional, only had this dimension on it, then all of these branches would lay down on top of each other 
and we wouldn't be able to see the relationships. So we use this axis here to spread things out so we can see the relationships. But it doesn't 
tell us anything at all about how closely related to things, how closely related different species are to one another.

So, for example, here, b is not more closely related to C than it is to D. It's actually equally related to C and D. And the reason for that is,
if you trace through this tree, you go through the same set of common branches to get to c from b as you do to go from b to get to d.

And this is something really important to remember. Now, one way to think about this is to think of every single node on the tree as being a pivot,
and you can spin around that pivot. So, for example, here, let's look at this node.

You could imagine these branches literally spinning around each other on that node. So, as a practical matter, what that means is that this tree, 
where we have a, b, c, d, is exactly the same as this tree where we have ABDC. All we did was spin around this 180 degrees here.

But these two trees, topologically, are exactly the same. There's no difference, even though they look different to your eye. Similarly, in this tree,
 we could also spin the entire tree around this node at the root here.

So we could spin it like this, which means that this tree, a, b, c, d, is exactly the same as this tree here. DCBA. All we did was took that original 
tree and spin it 180 degrees around that node.

So here's an interesting exercise for you. You can always, on this next slide, these three trees all depict exactly the same evolutionary history. 
They're just variations on each other by spinning the tree around different nodes that it has.

And if you want to figure that out for yourself, just pause the demonstration here. And work that out for yourself. Alright, one last thing about 
interpreting phylogenetic trees.

Sometimes branch length means something in phylogenetic trees, and sometimes it doesn't mean anything at all. When it doesn't mean anything at all. 
We make what are called cladograms, and that's what this is over here.

This is a cladogram. The cladogram gives us branching orders, but the branch lengths themselves don't mean anything. So, for example, here we've got 
these two species, and we know that they evolved after this speciation event here for these three species.

But the branch lengths are not telling us how long it's been since any of those events, just the order in which they occurred. Now, alternatively, 
we can say that branch lengths mean something. So that's when we have these things called phenograms, and that's what's presented over here.

In this case, the branch lengths do mean something. So here there's been more change on this long branch here than there's been, for example, on 
this short branch over here. So cladograms tell us branching order, but they don't tell us the timing or how much change there's been.

Phenograms do give us branching order, just like cladograms, but they also tell us how much time or how much change there's been on each branch. It.

---

### Português
Este é o primeiro de cinco vídeos sobre reconstrução filogenética.

Hoje. Vamos apenas introduzir o tópico.

Tudo bem, reconstrução filogenética. Já falamos sobre diferentes maneiras de fazer sistemas de classificação, e mostramos que a abordagem
cladística ou filogenética realmente tem a base biológica e filosófica mais sólida para descobrir relações evolutivas. Então a pergunta então
é, como inferimos filogenias? Existem um número muito, muito pequeno de eventos de especiação que os seres humanos realmente testemunharam.

A grande maioria, milhões deles, não foram testemunhados. E então como vamos inferir o conjunto real de relações evolutivas das espécies? 
Hoje vamos olhar apenas um dos métodos. Chama-se parcimônia.

E existem métodos além da parcimônia. Existem maneiras de fazer as coisas por meio do que chamamos de medidas de distância, máxima verossimilhança,
e algo chamado inferência bayesiana. Esses dois últimos são abordagens estatísticas e são muito importantes, mas não temos tempo para considerar 
todos eles.

Então vamos nos concentrar na parcimônia porque é mais direto. Tudo bem, então o objetivo da filogenética, se você ainda não adivinhou, é 
recriar as relações de ancestralidade entre as espécies. Então nosso objetivo é construir árvores filogenéticas, e isso necessariamente será 
um padrão de ramificação.

E isso deve fazer sentido para você com base na discussão que já tivemos sobre especiação, porque geralmente temos uma espécie parental original que 
se divide em duas ou mais espécies adicionais. E isso vai criar um padrão de ramificação quando representamos isso graficamente. Também falamos sobre o 
fato de que você pode ter evolução reticulada, especiação híbrida, mas vamos ignorar isso para esta parte da aula.

Tudo bem, primeiro, vamos garantir que entendemos como ler e interpretar árvores filogenéticas. 
Então as árvores têm diferentes partes. A maioria das árvores são árvores enraizadas.

Então a base da árvore é o que chamamos de raiz aqui. É onde as coisas começam. E então sempre que temos um evento de especiação, temos o que chamamos de nó.

Então aqui, este ramo representa uma espécie ancestral, e então isso se divide em duas novas espécies representadas por esses ramos. Agora, 
se você falar com alguém em ciência da computação, eles chamarão esses ramos de arestas, mas eles querem dizer a mesma coisa que nós quando os 
chamamos de ramos. E então aqui nas pontas da árvore, temos o que são chamados de folhas ou táxons ou espécies.

E então esses são os diferentes organismos, organismos para os quais estamos tentando reconstruir as relações. Agora, outra coisa que pode ser 
complicada sobre a leitura de árvores filogenéticas é que a ordem em que as coisas aparecem nas pontas muitas vezes realmente não significa absolutamente nada. O que realmente importa quando estamos lidando com uma árvore filogenética são as relações das coisas através dos ramos reais da árvore.

E então uma maneira de pensar sobre isso é que cada nó na árvore pode girar. Agora, antes de chegarmos a isso, vamos olhar para outra coisa aqui. 
Esta dimensão na árvore é o tempo.

Então o tempo está fluindo da raiz até as pontas, onde temos nossas espécies atuais. No entanto, essa dimensão aqui realmente não significa nada. 
Está apenas lá para que possamos ver as relações das espécies.

Se fizéssemos uma árvore filogenética unidimensional, tivéssemos apenas essa dimensão nela, então todos esses ramos se deitariam uns sobre os outros e 
não poderíamos ver as relações. Então usamos esse eixo aqui para espalhar as coisas para que possamos ver as relações. Mas isso não nos diz absolutamente nada sobre o quão intimamente relacionadas são as diferentes espécies umas com as outras.

Então, por exemplo, aqui, b não está mais intimamente relacionado a C do que está a D. Na verdade, está igualmente relacionado a C e D. E a razão para isso é que, se você traçar esta árvore, você passa pelos mesmos ramos comuns para chegar a c de b como você faz para ir de b para d.

E isso é algo muito importante para lembrar. Agora, uma maneira de pensar sobre isso é pensar que cada nó na árvore pode girar. Então, por exemplo, aqui, vamos olhar para este nó.

Você pode imaginar esses ramos girando literalmente um ao redor do outro nesse nó. Então, como uma questão prática, o que isso significa é que esta árvore, onde temos a, b, c, d, é exatamente a mesma que esta árvore onde temos ABDC. Tudo o que fizemos foi girar em torno disso 180 graus aqui.

Mas essas duas árvores, topologicamente, são exatamente as mesmas. Não há diferença, mesmo que pareçam diferentes para o seu olho. Da mesma forma, nesta árvore, também poderíamos girar toda a árvore em torno deste nó na raiz aqui.

Então poderíamos girá-lo assim, o que significa que esta árvore, a, b, c, d, é exatamente a mesma que esta árvore aqui. DCBA. Tudo o que fizemos foi pegar aquela árvore original e girá-la 180 graus em torno desse nó.

Então aqui está um exercício interessante para você. Você sempre pode, no próximo slide, essas três árvores retratam exatamente a mesma história evolutiva. Elas são apenas variações uma da outra girando a árvore em torno de diferentes nós que ela tem.

E se você quiser descobrir isso por si mesmo, basta pausar a demonstração aqui. E trabalhe isso por si mesmo. Tudo bem, mais uma coisa sobre a interpretação de árvores filogenéticas.

Às vezes, o comprimento do ramo significa algo em árvores filogenéticas, e às vezes não significa absolutamente nada. Quando não significa absolutamente nada. Fazemos o que chamamos de cladogramas, e é isso que está aqui.

Este é um cladograma. O cladograma nos dá ordens de ramificação, mas os comprimentos dos ramos em si não significam nada. Então, por exemplo, aqui temos essas duas espécies, e sabemos que elas evoluíram após este evento de especiação aqui para essas três espécies.

Mas os comprimentos dos ramos não nos dizem há quanto tempo ocorreram esses eventos, apenas a ordem em que ocorreram. Agora, alternativamente, podemos dizer que os comprimentos dos ramos significam algo. Então é quando temos essas coisas chamadas fenogramas, e é isso que está apresentado aqui.

Neste caso, os comprimentos dos ramos significam algo. Então aqui houve mais mudança neste ramo longo aqui do que houve, por exemplo, neste ramo curto aqui. Então os cladogramas nos dizem a ordem de ramificação, mas não nos dizem o tempo ou quanto mudança houve.

Os fenogramas nos dão a ordem de ramificação, assim como os cladogramas, mas também nos dizem quanto tempo ou quanto mudança houve em cada ramo. Isso.

---

### Revisão Final (Português)
- Este é o primeiro de cinco vídeos sobre reconstrução filogenética.
- Hoje, vamos apenas introduzir o tema.
- Já discutimos diferentes maneiras de criar sistemas de classificação.
- Mostramos que a abordagem cladística ou filogenética possui a base biológica e filosófica mais sólida para entender as relações evolutivas.
- A pergunta que surge é: como, de fato, inferimos filogenias?
- Existem pouquíssimos eventos de especiação que os seres humanos realmente testemunharam.
- A grande maioria, milhões deles, não foram testemunhados.
- Então, como inferimos o conjunto real de relações evolutivas das espécies?
- Hoje, vamos olhar para apenas um dos métodos: a parcimônia.
- Existem métodos além da parcimônia, como medidas de distância, máxima verossimilhança e inferência bayesiana.
- Esses dois últimos são abordagens estatísticas e são muito importantes, mas não temos tempo para considerá-los todos.
- Vamos focar na parcimônia porque é mais direta.
- O objetivo da filogenética é recriar as relações de ancestralidade entre as espécies.
- Nosso objetivo é construir árvores filogenéticas, que necessariamente serão um padrão de ramificação.
- Isso deve fazer sentido com base na discussão que já tivemos sobre especiação.
- Geralmente, temos uma espécie parental original que se divide em duas ou mais espécies adicionais.
- Isso cria um padrão de ramificação quando representamos isso graficamente.
- Falamos sobre evolução reticulada e especiação híbrida, mas vamos ignorar isso nesta parte da aula.
- Primeiro, vamos garantir que entendemos como ler e interpretar árvores filogenéticas.
- A maioria das árvores são enraizadas.
- A base da árvore é a raiz, onde as coisas começam.
- Sempre que temos um evento de especiação, temos um nó.
- Esse nó representa uma espécie ancestral que se divide em duas novas espécies.
- Se você falar com alguém em ciência da computação, eles chamarão esses ramos de arestas.
- Nas pontas da árvore, temos folhas, táxons ou espécies.
- São os diferentes organismos para os quais estamos tentando reconstruir as relações.
- A ordem em que as coisas aparecem nas pontas muitas vezes não significa absolutamente nada.
- O que importa são as relações das coisas através dos ramos reais da árvore.
- Cada nó na árvore pode girar.
- A dimensão na árvore é o tempo.
- O tempo flui da raiz até as pontas, onde temos nossas espécies atuais.
- A dimensão aqui não significa nada.
- Está apenas lá para que possamos ver as relações das espécies.
- Se fizéssemos uma árvore filogenética unidimensional, todos os ramos se deitariam uns sobre os outros.
- Usamos esse eixo para espalhar as coisas para que possamos ver as relações.
- Mas isso não nos diz nada sobre o quão intimamente relacionadas são as diferentes espécies.
- Cada nó na árvore pode girar.
- As árvores a, b, c, d e ABDC são exatamente as mesmas.
- Mesmo que pareçam diferentes, topologicamente, são exatamente as mesmas.
- Os cladogramas nos dão ordens de ramificação, mas os comprimentos dos ramos não significam nada.
- Os fenogramas nos dão a ordem de ramificação e nos dizem quanto tempo ou quanto mudança houve em cada ramo.

---

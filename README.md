### <h2 align="center">Linguagens formais e automatos</h2>

<br><br><br>
<p></p>

- <h2> Automatos finitos deterministicos (AFD) </h2>

<img height="220px" width= "80%" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbQsiGIWWZ8FDW-lPnj9oZ-lO9yxOLmi4f3HpstDOtQUnIg9hvpXkogacS-pg6cerCftQ&usqp=CAU"/>
<br>
<p>
Um autômato finito determinístico (AFD) é um modelo abstrato de computação usado em ciência da computação e teoria dos autômatos. Ele consiste em um conjunto finito de estados, um alfabeto finito de entrada, uma função de transição, um estado inicial e um conjunto de estados finais.

Cada estado representa uma configuração específica do sistema, e a função de transição define como o autômato muda de um estado para outro em resposta a cada símbolo de entrada. A natureza determinística do AFD significa que, para cada estado e símbolo de entrada, há uma única transição definida.

Os AFDs são frequentemente usados para modelar sistemas de processamento de linguagens regulares, como análise léxica em compiladores ou expressões regulares em mecanismos de busca. Sua simplicidade e facilidade de implementação os tornam ferramentas valiosas na concepção e análise de algoritmos.</p>
<br>
- <h2> Automatos finitos não deterministicos (AFND) </h2>

<img  height="220px" width= "80%" src="http://www.dsc.ufcg.edu.br/~pet/jornal/junho2014/images/materias/recapitulando/afn.jpg" />

<p>Um autômato finito não determinístico (AFND) é outro modelo abstrato de computação utilizado na ciência da computação e na teoria dos autômatos. Assim como o autômato finito determinístico (AFD), ele também consiste em um conjunto finito de estados, um alfabeto finito de entrada, uma função de transição, um estado inicial e um conjunto de estados finais.

A principal diferença entre um AFND e um AFD está na função de transição. Enquanto em um AFD cada transição é determinística, ou seja, para cada estado e símbolo de entrada há uma única transição definida, em um AFND uma transição pode levar a um ou mais estados, ou até mesmo a nenhum estado em particular, em resposta a um símbolo de entrada. Isso significa que um AFND possui a capacidade de "escolher" entre múltiplas transições possíveis em um determinado estado e símbolo de entrada.

Embora possa parecer mais complexo, os AFNDs têm vantagens significativas em relação aos AFDs em alguns contextos. Eles são mais expressivos e permitem uma representação mais compacta de certas linguagens. Além disso, muitos algoritmos de conversão existem para converter um AFND em um AFD equivalente, o que permite que linguagens reconhecidas por AFNDs sejam processadas por máquinas mais eficientes como os AFDs. AFNDs são amplamente utilizados em teoria da computação, linguagens formais e em áreas de computação onde a flexibilidade na especificação de comportamentos não determinísticos é útil.</p>

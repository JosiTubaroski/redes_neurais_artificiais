# Redes Neurais Artificiais

Vamos dividir em 4 partes para ficar bem clara: <b>origem, evolução histórica, como funciona</b>, e <b>por que voltaram com tanta força.</b>

### 🧠 1. Origem: inspiração biológica

As redes neurais artificiais foram inspiradas no <b>funcionamento do cérebro humano.</b>
Nosso cérebro é formado por <b>neurônios</b> que se comunicam através de <b>sinapse</b>, transmitindo sinais elétricos e químicos.
A idéia era simples, mas revolucionária:

"E se criássemos um sistema computacional que imitasse esse comportamento - aprender a partir de exemplos, assim como o cérebro faz?"

O promeiro modelo surgiu em <b>1943</b>, com os cientistas <b>Warren McCulloch</b> e <b>Walter Pitts</b>, que publicaram o artigo

"A Logical Calculus of Ideas Immanent in Nervous Activity".

Eles criaram um modelo matemático de neurônio simples: recebia entradas, aplicava um peso, somava e gerava uma saída (ativação).

### 🧩 2. Linha do tempo histórica

- <b>1950-1960</b> → surgem os primeiros experimentos práticos, como o <b>Perceptron</b> (Frank Rosenblatt, 1958).
  Ele aprendia a classificar padrões simples, mas tinha limitações - não resolvia problemas mais complexos (como o famoso XOR).

- <b>1970-1980</b> → "inverno da IA": o entusiasmo caiu, porque as máquinas eram lentas e os modelos, fracos.

- <b>1986</b> → ressurgimento com o <b>algoritmo de retropropagação (backpropagation)</b>, criado por <b>Rumelhart, Hinton e Williams,</b> permitindo treinar redes com várias camadas.

- <b>1990-2000</b> → as RNAs começaram a ser aplicadas em reconhecimento de voz, escrita e imagem.

- <b>2010 em diante</b> → renascimento do “Deep Learning” com <b>redes neurais profundas</b> (muitas camadas) e <b>grande poder computacional (GPUs).</b>
  Empresas como Google, Meta e OpenAI impulsionaram essa nova era.

### ⚙️ 3. Como funcionam as redes neurais artificiais

De uma forma simples, uma <b>rede neural artificial</b> é um conjunto de <b>camadas de neurônios artificiais</b> (tambêm chamados de nós ou unidades), conectados entre si.
Cada conexão tem um <b>peso</b>, que indica a importância do sinal.

### Processo Básico:

<b>1. Entrada</b> → os dados entram (por exemplo, uma imagem com pixels).
<b>2. Propagação</b> → cada neurônio multiplica o valor de entrada por um peso, soma tudo e aplica uma <b>função de ativação</b> (como ReLU ou Sigmoid).
<b>3. Saída</b> → a rede gera um resultado (ex: “gato” ou “cachorro”).
<b>4. Aprendizado (treinamento)</b> → o sistema compara o resultado com o valor real e ajusta os pesos (via backpropagation e gradiente descendente) para errar menos na próxima vez.

Com muitas iterações, a rede <b>aprende padrões complexos</b> — por exemplo, diferenciar rostos, traduzir textos, ou prever comportamento de clientes.

### 🚀 4. Por que voltaram com tanta força

- Aumento do <b>poder computacional</b> (GPUs e TPUs).
- <b>Big Data</b> (milhoes de exemplos para aprender).
- <b>Novos algoritimos</b> e arquiteturas (como CNNs, RNNs, Transformers).
- <b>Open Source</b> (TensorFlow, PyTorch, etc.).

Hoje, redes neurais estão por trás de:

- Reconhecimento facial
- Tradução automática
- Carros autônomos
- ChatGPT (que usa uma arquitetura derivada: o <b>Transformer</b>)

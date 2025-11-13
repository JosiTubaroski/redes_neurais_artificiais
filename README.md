
<div> 
<p><a href="https://github.com/JosiTubaroski/DataScience/blob/main/README.md">Inteligencia Artificial</a></p>
</div> 

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

### Como é um neurónio, como ele funciona, como foi descoberto?

O <b>neurônio</b> é a <b>unidade básica do sistema nervoso</b>, o tijolo fundamental de tudo que pensamos, sentimos e fazemos.
Vamos ver em tres partes:

### 🧩 1. Como é um neurônio

Um neurônio é uma <b>celula altamente especializada</b> para transmitir sinais elétricos e químicos.
Ele tem uma forma característica - parecida com uma árvore - com três partes principais:

<b>1. Dendritos 🌿</b>

São como "galhos" que recebem sinais de outros neurônios.
Quanto mais dendritos, mais conexões o neurônio pode fazer.

<b>2. Corpo celular (ou soma) ⚙️</b>

É o "centro de controle", onde fica o <b>núcleo</b> e onde o neurônio processa os sinais recebidos.

<b>3. Axônio ⚡</b>

É um "fio longo" que envia impulsos elétricos para outros neurônios, musculos ou glandulas.
Na extremidade do axônio estão os <b>terminais sinápticos</b>, que liberam neurotransmissores nas <b>sinapses.</b>

🔹Alguns axônios têm uma <b>bainha de mielina</b>, uma camada que acelera a transmissão dos impulsos elétricos - como um fio revestido por borracha.

### ⚡ 2. Como o neurônio funciona

O neurônio <b>se comunica por impulsos elétricos</b> chamados <b>potenciais de ação</b>.

Funciona assim:

1. Em repouso, o neurônio tem uma carga elétrica negativa em relação ao ambiente externo.
2. Quando recebe um estímulo suficiente (por exemplo, de outro neurônio), há uma <b>mudança no potencial elétrico da membrana</b>.
3. Essa mudança dispara um <b>impulso elétrico</b> que corre pelo axônio.
4. Ao chegar ao final do axônio, o impulso <b>libera neurotransmissores</b> (dopamina, serotonina, acetilcolina etc.).
5. Esses neurotransmissores atravessam a sinapse e <b>ativam o próximo neurônio</b>.

👉 É como uma rede de bilhetes passando de mão em mão — mas em escala microscópica e em milissegundos.

### 🔬 3. Como o neurônio foi descoberto

A história é fascinante:

- Final do século XIX, os cientistas ainda achavam que o cérebro era uma “massa contínua” de tecido (a teoria reticular de Camillo Golgi).
- Santiago Ramón y Cajal, um médico espanhol, usou uma técnica de coloração desenvolvida por Golgi (a coloração com nitrato de prata) e, ao observar no microscópio, percebeu que o cérebro era, na verdade, feito de células individuais conectadas, mas separadas — os neurônios.
- Ele desenhou à mão milhares de neurônios e formulou a Teoria Neuronal:

  o sistema nervoso é formado por unidades discretas (neurônios) que se comunicam entre si por contatos específicos (as sinapses).

Cajal ganhou o <b>Prêmio Nobel de Fisiologia ou Medicina em 1906</b>, compartilhado com o próprio Golgi — ironicamente, o homem cuja técnica ele usou para provar o contrário do que o outro acreditava.

### 💡 Em resumo

- O <b>neurônio</b>é a célula que processa e transmite informação no cérebro.
- Ele faz isso com sinais elétricos e quimicos
- E foi graças a Cajal que entendemos que o cérebro é uma rede de bilhões de neurônios interligados — a base tanto da mente quanto da inteligência artificial moderna.

  <img width="484" height="275" alt="image" src="https://github.com/user-attachments/assets/52b2fb73-a427-40bd-8821-66cd261fa88f" />

### Condicionamento pavloviano

🧠 O experimento clássico de Pavlov

1. Pavlov estudava a digestão dos cães.

2. Ele notou que os cães salivavam não só ao ver comida, mas também quando viam o pesquisador ou ouviam sons associados à comida.

3. Então ele decidiu investigar:

- Antes do condicionamento:

   - Comida → salivação (resposta natural)

   - Som do sino → nenhuma reação

- Durante o condicionamento:

   - Som do sino + comida → salivação

- Depois de várias repetições:

   - Som do sino → salivação (mesmo sem comida)
 
### 💭 Aplicações e exemplos modernos

- <b>Publicidade:</b> associar uma marca a emoções positivas (música, pessoas bonitas, momentos felizes).

- <b>Fobias:</b> uma pessoa pode associar um estímulo neutro (como um elevador) a algo negativo (pânico).

- <b>Educação e treino animal:</b> sons ou gestos são associados a comportamentos e recompensas.


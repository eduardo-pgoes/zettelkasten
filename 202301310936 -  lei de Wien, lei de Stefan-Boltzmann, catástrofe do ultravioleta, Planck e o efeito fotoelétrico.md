algum dia, cientistas decidiram estudar _quantitativamente_ os corpos que brilham quando você aumenta a temperatura deles. todos já viram um metal brilhando vermelho quando fica quente - isso é qualitativo. os cientistas decidiram estudar as quantidades envolvidas naquela radiação.

pra isso, usaram o corpo negro - que emite e absorve a luz em todo o espectro visível. ele têm esse nome pq não favorece nenhum comprimento de onda na hora de emitir ou absorver - como costumam fazer os corpos "não teóricos".

encontrou-se a lei de Stefan-Boltzmann:
$$
\text{intensidade total da radiação} = \text{cte} * T^4
$$
também encontrou-se a lei de Wien:
$$
T\lambda_\text{max}=\text{cte}
$$

bom, o livro não entra muito em detalhes sobre como foram formuladas e não queremos entrar nesse mérito agora.

de qualquer forma, na física clássica, isso gerava o catástrofe do ultravioleta. se qualquer átomo oscilando gera radiação, então era pro corpo humano brilhar no escuro - isso é absurdo.

o que Planck pensou? bicho, não é possível que tudo que oscile gere radiação. essa troca de energia e radiação precisa ser _quantizada_. um oscilador em frequência $\nu$ só pode trocar energia em forma de radiação com o ambiente se for em pacotes de energia quantizada, energia essa que possui a seguinte fórmula:
$$
E = h\nu
$$
$$
h = \text{constante de Planck}
$$
mas aí... como tu justifica uma mudança tão radical na física? ele conseguiu deduzir as leis de Wien e Stefan-Boltzmann, mas isso não era o suficiente. e aí veio o Nobel do Einstein: o efeito fotoelétrico.

o efeito fotoelétrico consiste na seguinte questão:
- quando você joga radiação em uma placa de metal, ela ejeta elétrons... mas só a partir de uma frequência específica;
- os elétrons são ejetados imediatamente, independendo da intensidade da radiação;
- a energia cinética dos elétrons varia linearmente com a frequência da radiação emitida.

Einstein decidiu formular que a radiação eletromagnética poderia ser descrita como partículas: fótons. por exemplo, um raio de luz vermelha pode ser visto como um fluxo de fótons de mesma energia. daí, $E = h \nu$ formula a energia de _cada um dos fótons_.

bom, como isso explica o efeito fotoelétrico?
- a partir de um threshold de energia necessária para arrancar o elétron da placa (função de trabalho), o fóton consegue arrancar elétrons;
- se o fóton tem a energia necessária, ele arranca o elétron: simples assim (e é por isso que a intensidade da radiação não importa para o tempo de ejeção do elétron)
- a energia cinética do elétron é igual à energia do fóton que bateu nele, subtraída a energia necessária para remover o elétron da placa

ou seja:
$$
\frac{m_ev^2}{2}=h\nu-\phi
$$
$$
\phi = \text{função de trabalho de cada metal}
$$

temos, por fim, a condição limitante de Bohr.
lembra das linhas espectrais? pois bem, a energia da radiação emitida por um elétron quando troca de estado pode ser também descrita da seguinte forma:
$$
h\nu = E_\text{upper} - E_\text{lower}
$$
$$
E_\text{upper} = \text{energia do elétron do nível superior}
$$
$$
E_\text{lower} = \text{energia do elétron do nível inferior}
$$
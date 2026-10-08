# Template e Roteiro de Apresentação: Seminário de Visão Computacional

> **Objetivo:** Estrutura pronta e padronizada para montagem dos slides e ensaio da apresentação oral, cobrindo integralmente as 10 seções obrigatórias exigidas pela banca avaliadora.

---

## ⏱️ Planejamento Geral da Apresentação
* **Tempo Total Recomendado:** 15 a 18 minutos (deixando 5 a 7 minutos para arguição da banca).
* **Distribuição Sugerida por Integrante (Exemplo para Grupo de 3 Pessoas):**
  * **Apresentador 1:** Slides 1 a 3 (Identificação, Objetivo, Introdução e Contexto) ~ 5 min.
  * **Apresentador 2:** Slides 4 a 6 (Metodologia detalhada, Arquitetura e Resultados Empíricos) ~ 7 min.
  * **Apresentador 3:** Slides 7 a 10 (Discussão, Conclusão, Opinião Crítica do Grupo e Referências) ~ 5 min.

---

## 🖥️ Roteiro Slide a Slide (Estrutura Oficial de 10 Slides)

### Slide 1: Identificação do Artigo
* **Layout Visual:** Logo da instituição/universidade no topo; título do artigo em destaque; autores originais; veículo de publicação; nomes dos integrantes do grupo e data.
* **Tópicos na Tela:**
  * **Título Original:** *[Inserir Título do Artigo]*
  * **Autores:** *[Nome dos Autores Principais]* (Instituição de Origem: ex. Google Brain, Stanford, MIT, etc.)
  * **Publicação:** *[Nome da Revista / Conferência]* (ex: CVPR, ICCV, OSDI, IEEE TPAMI) | Ano: *[AAAA]*
  * **Integrantes do Grupo:** *[Nome dos Alunos do Grupo]*
* **Roteiro de Fala:**
  > *"Olá a todos, professor(a) e colegas. Nosso grupo é composto por [Nomes] e hoje apresentaremos o seminário sobre o artigo científico [Título], publicado em [Ano] na conferência/revista [Nome]. Este trabalho é uma referência seminal na área de Visão Computacional porque [citar o principal impacto em uma frase]."*
* **Possível Pergunta da Banca:** *"Qual a relevância dessa conferência/periódico na área de computação?"*  
  *(Dica: pesquise o Qualis da CAPES ou o índice h5 do Google Scholar do veículo antes de apresentar).*

---

### Slide 2: Objetivo do Trabalho
* **Layout Visual:** Dividido em duas colunas: Coluna Esquerda: *A Dor / O Problema*; Coluna Direita: *A Solução Proposta*.
* **Tópicos na Tela:**
  * **Problema Central:** Qual barreira técnica ou prática motivou a pesquisa?
  * **Objetivo Geral:** O que os autores propuseram construir, modelar ou comprovar?
  * **Objetivos Específicos:** Redução de latência? Aumento de acurácia? Portabilidade para novos hardwares?
* **Roteiro de Fala:**
  > *"O objetivo central deste trabalho é resolver o problema de [explicar o problema]. Até a publicação deste artigo, os pesquisadores enfrentavam a dificuldade de [descrever o gargalo]. Para solucionar isso, os autores propuseram [explicar a proposta principal]."*

---

### Slide 3: Introdução e Contextualização
* **Layout Visual:** Linha do tempo ou quadro comparativo mostrando a evolução das técnicas anteriores e onde elas falhavam.
* **Tópicos na Tela:**
  * **Contextualização:** Onde este trabalho se situa na história da Visão Computacional?
  * **Soluções Existentes na Época:** Quais eram os métodos padrões até então?
  * **Limitações das Soluções Existentes:** Por que as ferramentas anteriores não eram suficientes? (ex: alto custo computacional, falta de precisão, rigidez de implementação).
* **Roteiro de Fala:**
  > *"Para contextualizar, na época em que este trabalho foi concebido, o estado da arte utilizava métodos como [Método A e Método B]. No entanto, essas abordagens apresentavam limitações críticas, tais como [Limitação 1] e [Limitação 2]. Era evidente a necessidade de uma abordagem inovadora que superasse essas barreiras."*

---

### Slide 4: Metodologia (Parte 1 - Visão Geral do Pipeline)
* **Layout Visual:** **Obrigatório uso de diagrama de blocos do próprio artigo** (com a citação: *Fonte: Autores, Ano, Fig. X*). Sem parágrafos de texto!
* **Tópicos na Tela:**
  * **Dados Utilizados:** Datasets de teste (ex: ImageNet, COCO, dados próprios), quantidade de imagens, resolução e pré-processamento.
  * **Pipeline de Execução:** Entrada da imagem $\rightarrow$ Transformações/Convoluções $\rightarrow$ Extração de características $\rightarrow$ Saída.
* **Roteiro de Fala:**
  > *"Entrando na metodologia, os autores estruturaram o trabalho nas seguintes etapas. Primeiramente, quanto aos dados, foram utilizadas [X mil imagens do dataset Y], submetidas a pré-processamento de [normalização, redimensionamento]. Como podemos observar na Figura [N], o fluxo de processamento opera da seguinte forma..."*

---

### Slide 5: Metodologia (Parte 2 - Algoritmos e Ferramentas)
* **Layout Visual:** Fórmulas matemáticas essenciais (se houver), arquitetura da rede neural ou pseudocódigo dos algoritmos de visão.
* **Tópicos na Tela:**
  * **Modelos e Algoritmos:** Redes Convolucionais, Filtros espaciais, Algoritmos de Otimização (ex: Adam, SGD), Funções de Perda (Loss Functions).
  * **Softwares e Hardware:** Frameworks utilizados, aceleradores (GPUs, TPUs), configurações de treinamento.
* **Roteiro de Fala:**
  > *"O núcleo algorítmico do trabalho baseia-se em [explicar a técnica de processamento de imagem ou IA]. O aspecto mais engenhoso da metodologia é [destacar a inovação técnica dos autores], implementado através de [ferramentas computacionais utilizadas]."*

---

### Slide 6: Resultados Experimentais
* **Layout Visual:** **Gráficos e tabelas originais do artigo** (com fonte). Destaque em caixas coloridas (boxes) para os números de destaque.
* **Tópicos na Tela:**
  * **Métricas Avaliadas:** Acurácia Top-1/Top-5, mAP, FPS (quadros por segundo), Throughput, Tempo de treinamento.
  * **Comparações:** Como o novo método se saiu frente aos concorrentes anteriores?
  * **Ganhos Comprovados:** Redução de $X\%$ no erro ou aceleração de $Y\times$ no tempo de inferência.
* **Roteiro de Fala:**
  > *"Passando para a validação experimental, os autores submeteram o modelo a baterias de testes rigorosas. Como podemos observar na Tabela [N], o método proposto superou os concorrentes diretos, alcançando [citar a métrica principal]. O gráfico ao lado demonstra claramente o ganho de escalabilidade quando..."*
* **Alerta da Banca:** Não leia apenas os números! Explique o que o resultado significa fisicamente.

---

### Slide 7: Discussão Técnica
* **Layout Visual:** Tabela de Vantagens vs. Desvantagens/Limitações.
* **Tópicos na Tela:**
  * **Interpretação dos Autores:** Como os autores justificam os resultados alcançados?
  * **Principais Vantagens:** Onde a técnica brilha com excelência?
  * **Pontos Fracos e Casos de Falha:** Em quais condições o método falha? (ex: oclusão, ruído, baixa iluminação, alto consumo de memória).
  * **Aplicações Práticas Reais:** Onde essa técnica pode ser aplicada na indústria e na sociedade?
* **Roteiro de Fala:**
  > *"Na seção de discussão, os autores analisam os trade-offs da solução. Entre as grandes vantagens, destacam-se [vantagens]. Por outro lado, o trabalho reconhece limitações importantes: o modelo tem dificuldade em cenários de [casos de falha]."*

---

### Slide 8: Conclusão dos Autores
* **Layout Visual:** 3 ou 4 caixas resumindo as respostas diretas aos objetivos propostos no Slide 2.
* **Tópicos na Tela:**
  * **Objetivo Proposto vs. Alcançado:** O trabalho entregou o que prometeu no início?
  * **Síntese da Contribuição:** O que mudou na área após a publicação deste artigo?
  * **Trabalhos Futuros Indicados:** Quais foram os próximos passos apontados pelos próprios autores?
* **Roteiro de Fala:**
  > *"Os autores concluem que os objetivos propostos foram plenamente alcançados. A principal contribuição consolidada pelo artigo foi [síntese]. Como trabalhos futuros, os pesquisadores apontaram a necessidade de investigar [trabalho futuro]."*

---

### Slide 9: Opinião do Grupo e Análise Crítica
* **Layout Visual:** **Momento mais importante para a nota do grupo!** Divida em: *Pontos Fortes*, *Críticas Metodológicas* e *Nossa Proposta de Melhoria*.
* **Tópicos na Tela:**
  * **Ponto Forte Identificado pelo Grupo:** O que mais impressionou a equipe na abordagem?
  * **Crítica / Limitação Oculta:** O que os autores deixaram de abordar ou facilitaram nos testes? (ex: testaram apenas em dataset ideal; ignoraram o consumo de bateria em celulares; não compararam com o concorrente X).
  * **Ideia Inovadora do Grupo:** Como nós expandiríamos ou aplicaríamos este trabalho em um cenário prático ou na realidade brasileira?
* **Roteiro de Fala:**
  > *"Chegando à análise crítica do nosso grupo: reconhecemos que o artigo é brilhante no aspecto [ponto forte]. Contudo, identificamos que os autores foram conservadores em [ponto fraco/crítica metodológica]. Caso fôssemos desenvolver uma continuação deste trabalho em um TCC ou Iniciação Científica, nossa proposta seria aplicar essa técnica em [ideia inovadora do grupo]."*

---

### Slide 10: Artigos Complementares e Referências
* **Layout Visual:** Lista organizada das referências em formato bibliográfico padronizado (ABNT ou IEEE).
* **Tópicos na Tela:**
  * **Artigos Complementares Utilizados:** Trabalhos usados pelo grupo para contextualizar técnicas ou comparar dados.
  * **Referências Formais:**
    * *[Autor et al. Título. Veículo, Ano.]*
    * *[Autor et al. Título. Veículo, Ano.]*
  * **Agradecimento e Espaço para Perguntas da Banca:** "Obrigado pela atenção! Estamos abertos a dúvidas."
* **Roteiro de Fala:**
  > *"Para embasar nossa apresentação e realizar as comparações críticas, consultamos também os trabalhos complementares [citar 1 ou 2 artigos]. Encerramos nossa apresentação com as referências bibliográficas em tela e ficamos à inteira disposição do professor e da turma para perguntas."*

---

## 🎭 Dicas de Postura e Oratória para Nota 10

1. **Nunca leia os slides:** Os slides são para o público ver; o seu olhar deve estar voltado para a banca e para a turma. Use cartões ou tópicos curtos de apoio.
2. **Cuidado com o jargão não explicado:** Se você disser termos como *"Convolução separable em profundidade"*, *"Quantização INT8"* ou *"Fórmula de Rodrigues"*, esteja preparado para explicar em 1 frase o que significa caso o professor pergunte.
3. **Mantenha a sincronia de grupo:** Todos os membros devem demonstrar domínio do trabalho como um todo. Quando a banca fizer uma pergunta, o grupo deve responder com calma e complementariedade.

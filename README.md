# Introdução às _Graph Neural Networks_ e suas aplicações em tarefas de aprendizado de máquina

# Resumo

O uso de redes neurais em grafos tem sido explorado em aplicações de aprendizado de máquina em diversas áreas como análise de redes sociais, química computacional, recomendações personalizadas e processamento de língua natural. A modelagem de dados sobre grafos é justificada pela possibilidade de utilizar múltiplas modalidades de características para construir uma representação com mais informação sobre dados, bem como incorporar informações sobre os relacionamentos dos dados na própria representação. Neste curso, apresentaremos técnicas para modelagem de dados estruturados e não estruturados sobre grafos, discutiremos sobre os benefícios deste tipo de modelagem e suas aplicações em aprendizado de máquina. Serão introduzidos os conceitos das GNNs, algumas variações como as GCNs e GATs, e demonstração em aplicações práticas que reproduzirão os tópicos abordados no curso.

# Requisitos

Por ser um curso de curta duração, apenas 5 horas, não apresentaremos conceitos básicos sobre programação, linguagem Python, redes neurais e aprendizado de máquina. Os dois primeiros são imprescindíveis para completo entendimento do curso. Nós trabalharemos com dados em formatos de texto e áudio nas atividades práticas. Se isto é novo para você, pesquise sobre extração de características para estes tipos de dados para você ter noção de como estes dados podem ser representados, mas não se preocupe, pois falaremos brevemente. 

Seguem algumas indicações de materiais que podem ser estudados até o curso:
- [Aula sobre redes neurais](https://www.youtube.com/watch?v=rpnEdkvSYj4)
- [Curso sobre aprendizado de máquina](https://www.youtube.com/watch?v=l2ALoe6Yfss&list=PL-K8PmZILhr0w0FH1gZrknk9CLRqXKo-Z&index=1) (focar nos conceitos básicos, tipos de dados, classificação, regressão e agrupamento)
- [Aula sobre programação em Python](https://www.youtube.com/watch?v=CEkHlfVH_Ew) (do zero ao básico de POO; conteúdo imprescindível para compreensão do curso)
- Representação no Espaço Vetorial[Link 1](https://www.youtube.com/watch?v=hivD34b-W5w) [Link 2](https://www.youtube.com/watch?v=OtQr5NkRPdg)
- [Introdução às Medidas de Proximidade](https://www.youtube.com/watch?v=yV26S9Zsq1s)

# Organização

Este curso é oferecido pelo Instituto de Ciências Matemáticas e de Computação da Universidade de São Paulo - ICMC/USP, com organização do Laboratório de Inteligência Computacional - LABIC.
Os ministrantes serão os alunos de doutorado **Marcos Paulo Silva Gôlo** e **Angelo Cesar Mendes da Silva**, com acompanhamento do professor Doutor do ICMC/USP **Ricardo Marcondes Marcacini**. 

# Ministrantes

## Marcos Gôlo

Marcos Gôlo é mestre em ciência da computação pelo Instituto de Ciências Matemáticas e de Computação da Universidade de São Paulo, campus de São Carlos. Marcos explorou o aprendizado de representação multimodal em dados textuais para o aprendizado de uma classe durante seu mestrado com trabalhos publicados em conferências nacionais e revistas internacionais. Além disso, Marcos obteve o prêmio de segunda melhor dissertação de mestrado no concurso de teses e dissertações (CTD) do CSBC 2023 e melhor dissertação do CTD do Webmedia 2023. Atualmente, faz doutorado no mesmo local de seu mestrado e foi premiado com o Latin American Google PhD Fellowship para pesquisar sobre aprendizado de representação em grafos heterogêneos para o aprendizado de uma classe. Marcos tem interesse nas áreas de pesquisa de mineração de dados, mineração de textos, aprendizado de uma classe e aprendizado de representação em grafos. 

<img src="/images/golo.jpg" width="200">

- Lattes: http://lattes.cnpq.br/7402825146038143
- Linkedin: https://www.linkedin.com/in/marcosgolo/
- Email: marcosgolo@usp.br
- Scholar: https://scholar.google.com.br/citations?user=CeyvhM8AAAAJ&hl=pt-BR

## Angelo Mendes

Angelo Mendes é aluno de doutorado do programa de Pós-Graduação em Ciências de Computação e Matemática Computacional no Instituto de Ciências Matemáticas e de Computação da Universidade de São Paulo, ICMC-USP. Sua pesquisa está relacionada ao aprendizado de representações para dados musicais com aplicações em diversas tarefas na área de recuperação de informação musical. O uso de redes neurais em grafos compõe sua pesquisa como parte do processo de modelagem de características músicais, como áudio e letras, em grafos e sua inserção em um modelo de aprendizado para construção de representações capaz de lidar com diversas tarefas.

<img src="/images/angelo.png" width="200">

- Lattes: http://lattes.cnpq.br/9125845204227997
- Linkedin: https://www.linkedin.com/in/angelo-mendes/
- Email: angelo.mendes@usp.br
- Scholar: https://scholar.google.com.br/citations?user=uKaUK48AAAAJ&hl=pt-BR
  
# Objetivo

Prover aos estudantes conhecimento dos conceitos básicos da área de modelagem de dados por meio de grafos homogênos e heterogêneos, da aplicação de _graph neural networks_, bem como apresentar direções para aprofundar o conhecimento conforme a necessidade de cada participante. Ensinar ferramentas básicas para leitura, pré-processamento e modelagem de dados visando oferecer a capacidade de lidar com diferentes tarefas de aprendizado de máquina para grafos. 

# Estrutura do Curso

- **Parte teórica 1:** Introdução aos grafos
- **Parte teórica 2:** Modelagem de dados em grafos
- **Parte teórica 3:** Graph Neural Networks
- **Parte teórica 4:** Contextos de exploração (Aplicações)
- **Parte prática 1:** Reconhecimento de emoções em músicas utilizando Graph Neural Networks
- **Parte prática 2:** Graph neural networks para detecção de notícias falsas por meio do aprendizado de uma classe

# Inscrição (até 18/11/23)

[link para inscrição.](https://bit.ly/inscricaognn)

*A realização da inscrição não garante a presença no curso. A efetivação da inscrição está relacionada ao número de vagas disponíveis. A confirmação será feita após o período de inscrição e via email.

# Certificado

O inscrito deverá participar de no mínimo 75% da carga horária do curso para ter direito ao certificado emitido pelo sistema de inscrição. A presença será computada no decorrer do curso.

# Bibliografia e material de apoio

[1] Wu, Z., Pan, S., Chen, F., Long, G., Zhang, C., & Philip, S. Y. (2020). A comprehensive survey on graph neural networks. IEEE transactions on neural networks and learning systems, 32(1), 4-24.

[2] Silva, A. C. M. D., Gôlo, M. P. S., & Marcacini, R. M. (2022). Unsupervised heterogeneous graph neural network for hit song prediction through one-class learning. Anais do X Symposium on Knowledge Discovery, Mining and Learning.

[3] C. Shi, Heterogeneous Graph Neural Networks. Singapore: Springer Singapore, 2022.

[4] CHEN, F.; WANG, Y.-C.; WANG, B.; KUO, C.-C. J. Graph representation learning: a survey. APSIPA Transactions on Signal and Information Processing, Cambridge University Press. 2020.

[5] CAI, H.; ZHENG, V. W.; CHANG, K. A comprehensive survey of graph embedding: Problems, techniques, and applications. IEEE Transactions on Knowledge & Data Engineering. 2018.

[6] Gôlo, Marcos Paulo Silva, et al. "On the Use of Early Fusion Operators on Heterogeneous Graph Neural Networks for One-Class Learning." Proceedings of the 29th Brazilian Symposium on Multimedia and the Web. 2023.

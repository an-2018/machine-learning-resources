# ML Resources

[Exemplo Pratico](https://towardsdatascience.com/do-you-know-this-flower-image-classifier-using-pytorch-1d45c3a3df1c)

Fazer uma exploração durante um tempo definido das tecnologias na area de Machine learning para classificacao de imagens, terminado o periodo definido para exploracao das tecnologias, finalisar relatorio para parte teorica e passar para implementacao do prototipo, finalizando o prototipo ver opcoes para escalar a solucao e opcionalmente implementar uma solucao na nuvem, terminar com os testes, analise de resultados etc

- Fase 1 - Pesquisa e familiarização com as tecnologias - Definir um tempo para explorar materiais, recursos, documentos etc, usar esses materias para tomar anotacoes sobre o tema, as tecnologias, e escrever parte introdutoria do relatorio, enquadramento, definir objetivos, estado da arte etc
- Fase 2 - Implementação do prototipo - escolher 2 referencias ou guias para parte de implementacao, construir um prototipo em matlab, construir um prototipo em python
- Fase 3 - Escalabilidade em producao - explorar tecnologias como Firebase ML kit, Azure ou outra ferramenta para escalar a solucao num cenario real em producao, como escalar o prototipo a um produto real, ex: construir pequena app web para classificar imagens de platas, utilizando uma ferramenta cloud para ter uma maior precisao dos resultados
- Fase 4 - Testes e conclusao - Finalisar escrita de relatorio, conclusao, testes, analise de resultados, trabalhos futuros

### Resources

- **Matlab** - Intro to Image Processing Toolbox (tentar explorar e implementar os modulos da documentacao seguintes - e fazer anotacoes de conceitos, topicos e referencias para relatorio)
- [https://www.mathworks.com/products/image.html](https://www.mathworks.com/products/image.html)
- [https://www.mathworks.com/help/deeplearning/examples.html?category=getting-started-with-deep-learning-toolbox&s_tid=CRUX_topnav](https://www.mathworks.com/help/deeplearning/examples.html?category=getting-started-with-deep-learning-toolbox&s_tid=CRUX_topnav)
- [https://www.mathworks.com/help/vision/ug/image-category-classification-using-deep-learning.html](https://www.mathworks.com/help/vision/ug/image-category-classification-using-deep-learning.html)
- [https://www.mathworks.com/help/vision/image-category-classification.html?s_tid=CRUX_topnav](https://www.mathworks.com/help/vision/image-category-classification.html?s_tid=CRUX_topnav)
- **kagle** - search similar resources for python - search the geting started material for learning ml, python and datasience
- Passo a passo para iniciar com python para ML
- [https://www.kaggle.com/learn/intro-to-machine-learning](https://www.kaggle.com/learn/intro-to-machine-learning)
- **Datacamp** - curso em datascience e machine learning - explorar e entender os conceitos basicos de ML e aprender python
- [https://www.datacamp.com/courses/machine-learning-for-everyone](https://www.datacamp.com/courses/machine-learning-for-everyone)
- **Cursos**
- https://www.udacity.com/course/intro-to-machine-learning--ud120
- https://www.udacity.com/course/deep-learning-pytorch--ud188
### Advanced Topics

- **Azure Cloud** - para implementacao mais avancada de produtos em ML (explorar depois de passar pelos outros materiais introdutórios)
- [https://azure.microsoft.com/it-it/blog/customvision-ai-code-free-automated-machine-learning-for-image-classification/](https://azure.microsoft.com/it-it/blog/customvision-ai-code-free-automated-machine-learning-for-image-classification/)
- [https://docs.microsoft.com/en-us/learn/paths/create-computer-vision-solutions-azure-cognitive-services/](https://docs.microsoft.com/en-us/learn/paths/create-computer-vision-solutions-azure-cognitive-services/)
- [https://docs.microsoft.com/en-us/azure/architecture/example-scenario/ai/intelligent-apps-image-processing](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/ai/intelligent-apps-image-processing)
- **Google Cloud Platform** - para implementacao mais avancada de produtos em ML (explorar depois de passar pelos outros materiais introdutórios)
- [https://developers.google.com/learn/pathways/get-started-image-classification](https://developers.google.com/learn/pathways/get-started-image-classification?authuser=0)
- [https://developers.google.com/learn/pathways/going-further-image-product-search](https://developers.google.com/learn/pathways/going-further-image-product-search?authuser=0)

### Keey words

- Machine learning for image processing
- supervised learning
- image classification algoritms in machine learning
- **Transfer learning** - tecnica usada em ML para usar algoritimo ja feito ja treinado para usar como base para treinar outros algoritmos, ex: usar um algoritmo treinado para classificar objectos como base para treinar um modelo especifico para plantas - vantagem nao precisa ter conhecimento avançado e tempo para treinar um algoritmo de classificação do zero (requer tempo para treinar um modelo, computacao - GPU e conhecimentos avancados de ML/Analise Matematica)
- **Transfer learning** - ver o conceito e explorar como implementar para o projecto (conceito importante para o que pretende implementar)
- [https://medium.com/@calebkaiser/deep-learning-isnt-hard-anymore-26db0d4749d7](https://medium.com/@calebkaiser/deep-learning-isnt-hard-anymore-26db0d4749d7)

### Notas

- investigar se Ministerio Agricultura tem base de dados de fotos de plantas
- criar dataset tipo do **kagle** como um repositorio de imagens das plantas encontradas e disponibilisar para a implementacao - documentar o processo de catalogacao e classificcao das imagens para o dataset ate a publicacao do dataset - quais plataformas utilizar, quais tecnologias, qual a qualidade e resolucao das imagens?
- Python e outras tecnologias
    - tendo algo feito em matlab e ja ter elaborado uma documentacao do experitmento realisado - tirar conclusoes, metricas de como melhoorar o algoritmo, as metricas chave para ajustar o modelo de aprendizagem,
    - passar entao para a utilizacao de python para construcao do produto - matlab utilizado para investigacao e modelacao do algoritimo - python utilizado para criar um algoritmo direcionado para um produto - ex criar uma api web onde recebe uma imagem e retorna o nome da planta que esta na imagem e a percentagem de precisao do algoritmo de classificacao

### Trabalhos futuros - futuras pesquisas

- reinforcement learning, deep learning algorithms
- [http://introtodeeplearning.com/](http://introtodeeplearning.com/)
- responsible ai - como implementar solucoes de AI para a sociedade etc
- [https://www.microsoft.com/en-us/ai/responsible-ai-resources](https://www.microsoft.com/en-us/ai/responsible-ai-resources)

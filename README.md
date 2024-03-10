<div align = "center">
<h2> Curso Bacharelado em Sistemas de Informação
<br>Processamento digital de imagem 
  
<br>Trabalho final
<br> IFFAKE - Detector de fotos falsas 
</div>


### `📄Resumo:`
### Este artigo explora a detecção de deepfakes, enfatizando abordagens teóricas e práticas, como o uso de Redes Neurais Convolucionais, Inception, Resnet e a técnica Grad-CAM. O projeto culmina em uma aplicação interativa para verificar a autenticidade de imagens, contribuindo para a segurança da informação e atenuando os riscos relacionados aos deepfakes.

### `📚Introdução:`
### Com o avanço veloz da inteligência artificial, várias aplicações surgiram, incluindo os deepfakes, algoritmos de manipulação de mídia baseados em aprendizado profundo. Os deepfakes possibilitam a troca de uma pessoa em uma imagem ou vídeo existente por outra, gerando potencial para enganos e sabotagens.

### `📚Objetivos:`
### Este trabalho busca aprofundar a compreensão dos fundamentos teóricos por trás da criação de deepfakes usando algoritmos CNN. Adicionalmente, visa desenvolver um sistema de reconhecimento de deepfakes por meio de uma rede neural ResNetInception treinada, avaliar a eficácia desse modelo na identificação de deepfakes e criar uma interface amigável utilizando Gradio para simplificar o uso do aplicativo de reconhecimento de deepfakes.

### '🧠Convolutional Neural Network:'
### Uma Convolutional Neural Network (ConvNet / CNN) representa um algoritmo de Aprendizado Profundo. Essas redes são projetadas para processar dados organizados em múltiplas matrizes, como é o caso de uma imagem colorida composta por três matrizes 2D, representando as intensidades de pixel nos três canais de cor. Essa arquitetura é aplicável a diversas modalidades de dados que possuem formato de múltiplas matrizes, como sinais unidimensionais, imagens bidimensionais ou espectrogramas de áudio, bem como dados tridimensionais, como vídeos ou imagens volumétricas.

### As CNNs se destacam por quatro conceitos fundamentais: conexões locais, compartilhamento de pesos, pooling e múltiplas camadas. As camadas convolucionais são responsáveis por extrair características locais, como detalhes faciais em uma imagem, enquanto as camadas de pooling agregam características semanticamente similares, como expressões faciais. Essa abordagem hierárquica é inspirada na organização natural de representações de sinais.

### '👩🏻‍💻Inception e Resnet'
### Dentro das arquiteturas de CNNs (Redes Neurais Convolucionais), encontramos a Inception e a Resnet, amplamente utilizadas no processamento e análise de imagens digitais. A Inception, desenvolvida pela Google, destaca-se pela utilização de módulos de convolução em paralelo, empregando filtros de diferentes tamanhos para capturar características em diversas escalas. Isso permite que a rede aprenda representações mais ricas e robustas das imagens de entrada. Por outro lado, a Resnet é uma arquitetura neural profunda, criada em 2015 para resolver o problema do gradiente desvanecente em redes neurais profundas. Utilizando conexões residuais, ela permite que a rede aprenda em camadas intermediárias, facilitando o treinamento.

### '📷Grad-CAM'
### A técnica Grad-CAM (Gradient-weighted Class Activation Mapping) emerge como uma abordagem para tornar os modelos baseados em Convolutional Neural Networks (CNNs) mais transparentes, oferecendo visualizações das regiões de entrada "importantes" para as previsões desses modelos, ou seja, explicações visuais. Essas visualizações são de alta resolução, identificando características específicas da classe de interesse, e discriminativas em relação às classes, destacando a classe de interesse sem incluir outras classes irrelevantes.

### '🛠Materiais e Métodos'
### O projeto foi elaborado utilizando a plataforma Google Colab e diversas bibliotecas essenciais, incluindo Gradio, torch, os, numpy, PIL, zipfile, cv2 e pytorch. Adicionalmente, foi incorporado um modelo pré-treinado, o InceptionResnetV1, disponível na plataforma HuggingFace [4], contribuindo para a eficácia e robustez do sistema.

### '📚Desenvolvimento'
### Inicialmente, um modelo previamente treinado foi empregado, utilizando a arquitetura InceptionResnetV1 devido à sua capacidade de discernir padrões complexos em imagens faciais. A escolha de um modelo pré-treinado, proveniente de uma fonte confiável, assegurou que o sistema começasse com um conhecimento sólido, fundamentado em uma ampla gama de dados.

### '🖥️:Pré-processamento'
### Antes de serem inseridas no modelo de classificação, as imagens passaram por processos cruciais de pré-processamento:
<div align = "center">
<img src="https://github.com/marizzxxxx/PDI-IFFAKE/blob/main/assets/1.png?raw=true">
</div>

<div align = "center">
<h3> Desenvolvido por:
  
<br> 👨🏽‍💻 Marcos Willian
<br> 👩🏻‍💻 Maria Eduarda Aires
</div>

# contagem-de-plantas
Este projeto visa aplicar operações morfológicas no processamento de imagens para detectar e contar plantas em imagens capturadas por drones.

Pré-processamento da Imagem: Inicia-se com a aplicação de filtros de suavização para reduzir ruídos e melhorar a qualidade da imagem. Em seguida, é realizada a segmentação para destacar as regiões de interesse, como as plantas.

Binarização: A imagem é convertida para um formato binário, onde os objetos de interesse (plantas) são representados em pixels brancos, e o fundo em pixels pretos. Isso é feito usando métodos como o de Otsu ou um limiar fixo, dependendo das características da imagem.

Operações Morfológicas: São aplicadas operações como erosão e dilatação para refinar a segmentação. A erosão remove pequenos ruídos e detalhes desnecessários, enquanto a dilatação amplia as plantas, preenchendo lacunas e conectando partes desconexas.

Detecção e Contagem de Plantas: Após a aplicação das operações morfológicas, é realizada a detecção das plantas. Técnicas de rotulagem de componentes conectados e algoritmos de contagem de objetos são usados para identificar e contar as plantas na imagem binária resultante.

# PRO-C10

- O aprendizado de máquina ensina os computadores a
pensar como os humanos.

Resumindo, o cérebro humano:
- Recebe dados/informações brutas.
- Treina a si próprio com os dados
- Age (tomando decisões) com base nos dados
aprendidos.

- O cérebro humano recebe muitas informações de entrada
diariamente, por isso ele não retém tudo o que chega a
ele. É, por isso, que esquecemos e precisamos aprender
algo novamente.

- Mostrar PDF com imagens, ah que é dificil de reconhecer é um tipo de coral

- Dados: os dados são as informações usadas como
entrada para ensinar (ou treinar) as máquinas.

- Algoritmo: o algoritmo é um conjunto de regras ou
procedimentos aplicados aos dados para criar um modelo
de aprendizado de máquina. Os algoritmos são escritos
para identificar os padrões nos dados de entrada. Os
dados podem estar em qualquer formato, texto, imagem
ou som.


- Modelo: o resultado que obtemos após aplicar os
algoritmos aos dados. O modelo pode ser salvo como um
arquivo e usado posteriormente para reconhecer/prever o
novo padrão em novos dados e ver quanto o modelo
consegue identificar o novo padrão.

- https://teachablemachine.withgoogle.com/

- O Teachable Machine usa o Tensorflow e o Keras para
aplicar algoritmos de aprendizado de máquina ao
conjunto de dados de imagem de entrada.

- Treinar 2 objetos ou sorrindo e séria
- exportar modelo, tensorflow, keras, trasnferir meu modelo, pode demorar mas será gerado um arquivo .zip
- descompactar, abrir o arquivo do código e colocar os arquivos tudo na mesma pasta no vsCode

- Criar ambiente virutal para python:
- abra o CMD no windows: python -m venv face_detection_env
- face_detection_env\Scripts\activate
- python.exe -m pip install --upgrade pip
- pip install tensorflow
- pip install opencv-python

- normalmente A webcam captura a imagem em formato 32x640x3como um array tridimensional.
- O formato esperado do quadro da imagem de entrada a ser usado no método predict() é 224x224x3 como uma array de 4 dimensões.

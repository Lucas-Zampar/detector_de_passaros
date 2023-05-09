# Detector de Pássaros

Neste repositório, constam os códigos utilizados no desenvolvimento do meu trabalho de conclusão de curso. Sua proposta foi a de empregar o aprendizado profundo na tarefa de detectar espécies de pássaros que frequentam comedouros residenciais. Para tanto, os pássaros que frequentam o comedouro localizado no jardim da minha residência foram registrados por meio de 3 webcams. A partir disso, frames foram selecionados por meio de uma ferramenta desenvolvida em streamlit, sendo anotados na plataforma [RoboFlow](https://roboflow.com/) a fim de formarem o conjunto de dados do projeto. Por fim, foi decidido utilizara o modelo Faster R-CNN o qual foi treinado por meio da _framework_ [IceVision](https://airctic.com/0.12.0/) com o conjunto construído. 

A estrutura de diretórios do projeto está organizado da seguinte forma:

- __códigos__: contem os notebooks e módulos implementados para o treinamento, avaliação e visualização dos modelos. 
- __dataset__: contem o conjunto de dados do projeto constituído por 940 imagens e 1.836 anotações no formato VOC PASCAL. Por limitação de espaço, o diretório é compartilhado pelo seguinte link: https://drive.google.com/drive/folders/1-x2uKuEYAwKtaDEuRBEKtW2e7KZM3ro3?usp=sharing
- __faster_rnn__ : contem os modelos treiandos, bem como arquivos que documentam seus desempenhos. Por limitação de espaço, o diretório é compartilhado pelo seguinte link: https://drive.google.com/drive/folders/1IYz9JtP0-gcLHHdla_88ZsJfrTWDbWtf?usp=sharing
- __streamlit_app__: contem a implementação da ferramenta desenvolvida em streamlit para a extração dos frames das gravações. 

O ambiente virtual utilizado para o desenvolvimento do projeto pode ser recriado por meio do arquivo _environment.yml_. 

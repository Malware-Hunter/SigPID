## SigPID WEB API

![Latest Stable Version](https://img.shields.io/badge/SigPID-V1.0-blue)


# Overview

O SigPID WEB API é uma ferramenta desenvolvida em Python para verificar se o aplicativo possui malware. Sua predição é baseada em analise estática e aprendizado de maquina, por meio da analise de permissões do Android. Seu uso consiste em fazer o upload de um aplicativo ( APK ) onde a ferramenta retornara a predição em forma de arquivo JSON (JavaScript Object Notation).

## Requisitos
Tecnologia | Versão
------------ | -------------
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> |3.7.6
<img src ="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/> |7.12.0

##  Bibliotecas utilizadas

<img src="https://img.shields.io/static/v1?message=1.20.1&color=<COLOR>color=blue&label=Numpy&logo=numpy&style=for-the-badge&url=Python-3776AB?">
<img src="https://img.shields.io/static/v1?message=1.2.4&color=<COLOR>color=blue&label=Pandas&logo=pandas&style=for-the-badge&url=Python-3776AB?">
<img src="https://img.shields.io/static/v1?message=3.3.5&color=<COLOR>color=blue&label=Androguad&logo=android&style=for-the-badge&url=Python-3776AB?">
<img src="https://img.shields.io/static/v1?message=0.22.1&color=<COLOR>color=blue&label=Scikit_learn&logo=scikit-learn&style=for-the-badge&url=Python-3776AB?">
<img src="https://img.shields.io/static/v1?message=3.10.0&color=<COLOR>color=blue&label=Pickle&logo=&style=for-the-badge&url=Python-3776AB?">
<img src="https://img.shields.io/static/v1?message=0.9&color=<COLOR>color=blue&label=Flask&logo=apache&style=for-the-badge&url=Python-3776AB?">

##  Instalação

Para instalar a ferramenta basta fazer o [download](https://github.com/Malware-Hunter/SigPID.git) descompactar em um diretório de sua preferencia. Antes de executar baixe o Python e instale as bibliotecas necessárias.

##  Uso
Com o ambiente pronto basta acessar o diretório raiz do SigPID e executar via terminal o comando.   
~~~html
python app.py
~~~
Então basta acessar o endereço URL informado pelo serviço Flask.
Ex.:http://127.0.0.1:5000/
~~~python
 Serving Flask app 'app' (lazy loading)Running on
 http://127.0.0.1:5000/ (Press CTRL+C to quit)
~~~
Agora na tela inicial basta clicar em selecionar um arquivo, apos seu carregamento clique em Analisar. A analise é retornada em formato JSON contendo a predição se é (Malware ou Benigno), nome do aplicativo, versão da API e versão mínima de API. Também a lista de permissões do aplicativo analisado.

##  Ambientes de execução testado
Para execução foi utilizado um notebook com processador Intel Celeron 1007U (1.5GHz, Dual Core, 2MB L2), 4GB DDR3 1.600MHz, disco rígido de 320GB (SATA - 5.400rpm), Windows 10 Home Single Language, compilação 19042.1110.
## Créditos
- Joner Mello
- Diego Kreutz
- Gustavo Cardozo
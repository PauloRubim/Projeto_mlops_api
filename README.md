# Projeto de Machine Learning Model Deployment

# Sobre o projeto
Este projeto foi desenvolvido no curso MLOps: Machine Learning e APIs da Alura. Este projeto consiste em fazer um deployment de um modelo de machine learning como API. Desse modo conseguimos disponibilizar o modelo em produção. 


# Tecnologias utilizadas
- Flask (Para desenvolvimento da aplicação web)
- Jupyterlab (Ambiente de desenvolvimento)
- Python (libs: Flask, flask_basicauth, TextBlob, LinearRegression, pickle)

# Entendendo os arquivos  
- requests.ipynb (notebook para testar a rota cotação)
- House_Prices.ipynb (notebook para criação do modelo de regressão)
- analise_de_sentimento.ipynb (notebook para criação do modelo de PLN)
- main.py (código da API)
- casas.csv (banco de dados para o modelo de regressão)
- requirements.txt (relatório das libs instaladas na máquina virtual)
- mlops_api (Máquina virtual)


# Como executar o projeto
Foi criado um ambiente virtual no python com todas as dependências utilizadas. Você pode pode inicializar o ambiente virtual na sua máquina que já tem todas as dependências instaladas.


Como inicializar:   
- No seu prompt (windows), caminhe até a pasta do projeto e utilize o comando: venv\Scripts\activate para ativar o ambiente virtual.  
- Outra alternativa seria criar um novo ambiente virtual e instalar as dependências por meio do arquivo requirements.txt com o comando: pip install -r requirements.txt


Testando o projeto:  
- Para inicializar a página web, no prompt, na pasta do projeto, digitaremos: python main.py  
- Copiaremos o endereço web mostrado no prompt e colaremos no buscador do navegador. Acrescentando ao endereço web /sentimento/Python is a great language, conseguimos testar nossa rota em que utilizamos um modelo de processamento de linguagem natural para análise de sentimentos em texto. Quanto mais próximo de 1 mais positivo e quanto mais próximo de -1 mais negativo é aquele texto.  
- Para testarmos o modelo de regressão utilizaremos o notebook: requests.ipynb. 

OBS: É interessante não ter nenhum caractere especial ou espaços entre nomes no caminho em que você for inicializar o ambiente virtual, pode ser que dificulte a inicialiação. 


# Autor

Paulo César Souza Rubim Filho

https://www.linkedin.com/in/paulorubimf/

# Checkpoint #1 - dDeploy de Função Serverless respondendo requisições HHTPP
  
o projeto tem o objetivo de subir uma aplicação que envia imagens para um repositório do tipo object storage, e envia e-mail confirmando a operação.  

## Provedor Utilizado  
* Azure (App Services)  
  
## Como rodar localmente  
  
No diretório da aplicação, em um console linux ou CLoud Shell, rodar o comando: `python3 app.py`  
  
## Pré requisitos  
  
Flask  
azure-storage-blob  
python-dotenv  
gunicorn  
  
### Passo a passo  
  
1. CLone o repositório para sua máquina:  
`git clone https://github.com/seu-usuario/pucminas-serverless-checkpoint1.git  
  
2. Entre na pasta do projeto  
  
  `cd pucminas-serverless-checkpoint1`  
    
3. Instale as dependências:  
  
pip install flask azure-storage-blob python-dotenv gunicorn  
  






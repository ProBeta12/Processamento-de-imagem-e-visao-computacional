# Projeto de Reconhecimento de Imagens

Este repositório contém um projeto de reconhecimento de imagens, treinado para identificar 5 objetos diferentes usando a ferramenta [Teachable Machine](https://teachablemachine.withgoogle.com/train/image).

## Descrição do Projeto

Utilizamos o Teachable Machine para treinar um modelo de aprendizado de máquina capaz de reconhecer 5 categorias distintas de objetos. A ferramenta nos permitiu coletar imagens de cada objeto, treinar o modelo diretamente no navegador e gerar os arquivos `labels.txt` e `keras.model.h5`, que são utilizados no processo de classificação.

## Ferramentas Utilizadas

- **Teachable Machine**: Para o treinamento do modelo de aprendizado de máquina e geração dos arquivos `labels.txt` e `keras.model.h5`.
- **Anaconda Navigator**: Usado para gerenciar pacotes e criar um ambiente virtual utilizando o arquivo `clone_env_teste.yaml`, que contém todas as dependências necessárias para o projeto.
- **Jupyter Notebook**: Utilizado para rodar o código de classificação (`classificacao_5_objetos-v4.ipynb`), que identifica os objetos nas imagens e exibe a porcentagem de acerto de cada categoria.

## Estrutura do Projeto

- `labels.txt`: Arquivo contendo as categorias de objetos reconhecidos pelo modelo.
- `keras.model.h5`: Arquivo contendo o modelo treinado para reconhecimento de imagens.
- `clone_env_teste.yaml`: Arquivo de ambiente do Anaconda contendo todas as dependências do projeto, incluindo pacotes necessários para a execução do código.
- `classificacao_5_objetos-v4.ipynb`: Jupyter Notebook com o código responsável por identificar os objetos e suas respectivas porcentagens de confiança.


## Guia de Configuração e Execução do Projeto

### Passo a Passo

### 1. Baixar o Anaconda Navigator

- Acesse o site oficial do [Anaconda](https://www.anaconda.com/products/distribution).
- Baixe e instale o **Anaconda Navigator** em seu sistema.

### 2. Importar o Arquivo de Ambiente

- Após instalar o Anaconda, abra o **Anaconda Navigator**.
- Importe o ambiente usando o arquivo `clone_env_teste.yaml`:
### 3. Organizar os Arquivos
### Coloque os seguintes arquivos em uma única pasta:

- labels.txt: Arquivo contendo as categorias de objetos reconhecidos.
- keras.model.h5: Modelo de aprendizado de máquina treinado.
- classificacao_5_objetos-v4.ipynb: Jupyter Notebook com o código de identificação dos objetos.

### 4. Executar o Código no Jupyter Notebook
- No Anaconda Navigator, inicie o Jupyter Notebook.
- Navegue até a pasta onde os três arquivos estão armazenados.
- Abra o arquivo classificacao_5_objetos-v4.ipynb e execute todas as células.
- Certifique-se de que o arquivo keras.model.h5 está na mesma pasta, pois o notebook irá carregá-lo para realizar a classificação dos objetos.

## Exemplos de Resultados

### Imagem 1
![WhatsApp Image 2024-10-22 at 17 08 05 (1)](https://github.com/user-attachments/assets/8b16291e-0445-471d-8893-2100e010b39f)  
*Descrição: Resultado do reconhecimento do objeto 1 utilizando o modelo treinado.*

### Imagem 2
![WhatsApp Image 2024-10-22 at 17 08 06 (1)](https://github.com/user-attachments/assets/24e6516e-a88e-40ce-8c73-89b805c2751a)  
*Descrição: Resultado do reconhecimento do objeto 2 utilizando o modelo treinado.*

### Imagem 3
![WhatsApp Image 2024-10-22 at 17 08 06](https://github.com/user-attachments/assets/e8e3950c-3951-4b65-8e43-f51289ec3e51)  
*Descrição: Resultado do reconhecimento do objeto 3 utilizando o modelo treinado.*

### Imagem 4
![WhatsApp Image 2024-10-22 at 17 08 06 (2)](https://github.com/user-attachments/assets/a5a7fb1c-98d3-4bdd-9c94-9ec7db45de52)  
*Descrição: Resultado do reconhecimento do objeto 4 utilizando o modelo treinado.*

### Imagem 5
![WhatsApp Image 2024-10-22 at 17 08 05](https://github.com/user-attachments/assets/44d244b7-038b-4f75-a953-c8b996d1cd91)  
*Descrição: Resultado do reconhecimento do objeto 5 utilizando o modelo treinado.*

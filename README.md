........................................<img width="512" height="512" alt="Lenna" src="https://github.com/user-attachments/assets/087dd570-ec93-4296-8cbc-d4862b222e7a" />........................................

---

# 💻 ML - Redução de Dimensionalidade em Imagens para Redes Neurais

[![Python](https://img.shields.io/badge/Python-3.12.6-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

---

## 📋 - Descrição 
Este projeto é uma tarefa dada aos estudantes do BairesDev - Machine Learning Training, um bootcamp da plataforma [DIO](https://www.dio.me/).

## 🎯 - Sobre o Projeto de Redução de Dimensionalidade
O projeto de Redução de Dimensionalidade -  o projeto implementa técnicas de **redução de dimensionalidade** em imagens como etapa de pré processamento. O sistema processa imagens RGB convertendo-as para tons de cinza e porteriormente para binário, aplicando conceios fundamentais de processamento de imagens para machine learning.

Imagem Lena - foi o nome atribuído a uma imagem amplamente utilizada no campo de processamento de imagens desde o ano 1973. A imagem consiste em uma fotografia da modelo Lena Forsén, rotulada como “o pecado original da tecnologia”, publicada na Playboy de 1972. Após este primeiro uso, a imagem de Lena se tornou a imagens mais utilizadas dentro das pesquisas, artigos, livros e documentários da área. Em uma edição de 1999 do IEEE Transactions on Image Processing, a imagem foi utilizada em três artigos separados. O uso da imagem de Forsen cresceu como uma bola de neve.

---

## 🚀 Funcionalidades

* ✅ Suporte a imagens PNG, JPG, JPEG, BMP
* ✅ Conversão RGB → Grayscale com pesos perceptuais (0.299R + 0.587G + 0.114B)
* ✅ Binarização adaptativa com média dos pixels
* ✅ Visualização lado a lado das transformações
* ✅ Exportação da análise final como PNG
* ✅ Interface gráfica via Tkinter

---

## 🛠️ Tecnologias Utilizadas

* Python 3.12.6
* NumPy
* Matplotlib
* Tkinter
* Vscode
* Google Collab

---

## 📦 Instrução de Instalação e dependências

```bash
python --version  # Requer Python 3.12.6 se não estiver no Collab
```

```bash
pip install numpy matplotlib
```

```bash
(opcional) baixar a imagem lenna disponibilizada aqui para teste 
```

---

## 📁 Instrução de Uso Google Collab

1. **Seleção da imagem**: Interface gráfica para escolher o arquivo Google collab

<img width="872" height="109" alt="Explicando01" src="https://github.com/user-attachments/assets/feb90cae-6fa1-43b9-920b-4115295f38bf" />

2. **Processamento automático**:

   * Carregamento da imagem RGB
   * Conversão para escala de cinza
   * Binarização com threshold adaptativo

<img width="2400" height="1200" alt="resultado" src="https://github.com/user-attachments/assets/788ed758-744f-464d-bfe5-d60f4909a7d7" />

3. **Visualização comparativa** das representações com legendas em Pt-Br e EN
   
4. **Exportação** (opcional): Salvamento dos resultados

---

## 📁 Instrução de Uso Visual Studio Code

1. **Seleção da imagem**: Interface gráfica para escolher o arquivo Visual Studio Code, basta rodar o código e aparece a janela para selecionar a imagem automaticamente.

<img width="1911" height="969" alt="explicando02" src="https://github.com/user-attachments/assets/3173b5ca-4d1c-4ea2-8431-a9cc817811d1" />


2. **Processamento automático**:

   * Carregamento da imagem RGB
   * Conversão para escala de cinza
   * Binarização com threshold adaptativo

<img width="1910" height="1043" alt="resultado01" src="https://github.com/user-attachments/assets/aac4e83e-6ac3-43c0-99c3-51a81746d208" />


3. **Visualização comparativa** das representações com legendas em Pt-Br e EN
   
4. **Exportação** (opcional): Salvamento dos resultados

---

## 📁 Estrutura do Projeto

```text
projeto-imagempb.py
├── carregar_imagem()          # Interface de seleção
├── ler_imagem()               # Carregamento e normalização
├── converter_para_cinza()     # Conversão RGB → Grayscale
├── binarizar()                # Threshold adaptativo
└── exibir_e_salvar()          # Visualização e exportação
```

---

## ⚙️ Parâmetros Configuráveis

* Pesos RGB (`w_r`, `w_g`, `w_b`)
* Threshold adaptativo
* Resolução de exportação (DPI)
* Formatos suportados (em `filedialog.askopenfilename()`)

---

## 📊 Aplicações em Machine Learning

* Pré-processamento de dados visuais
* Extração de características visuais (feature extraction)
* Redução de dimensionalidade
* Preparação para CNNs e outras arquiteturas

---

# Patrocinadores ou Afins
Estes são os *links* das empresas que estão de alguma forma ligadas a este projeto.
- [DIO](https://www.dio.me/): plataforma de cursos e bootcamps online.
- [Baires Dev](https://www.bairesdev.com/): A BairesDev é uma empresa multinacional americana de outsourcing de TI e desenvolvimento de software
- [Google Collab](https://colab.google/): O Google Colab (ou Colaboratory) é um ambiente de desenvolvimento integrado (IDE) gratuito e baseado em nuvem que permite escrever e executar código Python diretamente no navegador, sem necessidade de instalação ou configuração.
- [Visual Studio Code](https://code.visualstudio.com/): É um editor de código-fonte gratuito e poderoso, desenvolvido pela Microsoft, que é leve, mas altamente personalizável, e está disponível para Windows, macOS e Linux. Ele suporta nativamente linguagens como JavaScript, TypeScript e Node.js, e possui um vasto ecossistema de extensões para outras linguagens e tecnologias, tornando-se uma ferramenta versátil para desenvolvedores. 
- [Lenna]: É uma imagem de teste padrão amplamente utilizada no campo de processamento de imagens desde 1973. É uma foto da modelo sueca Lena Forsén, tirada pelo fotógrafo Dwight Hooker, cortada da página central da edição de novembro de 1972 da revista Playboy.

### Dashboard da tabela, já com os dados tratados, segmentados e legíveis

# Contribuição

Contribuições são bem-vindas!\
Se você encontrar algum problema ou tiver sugestões de melhorias, por favor abra uma **issue** ou envie um **pull request** para o repositório.\
Ao contribuir para este projeto, siga o layout existente na tabela, as convenções de commits e envie suas alterações em um **branch** ou **file** separado.\
Saiba mais sobre o código de conduta acessando o link: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

# Licença

Este repositório possui licença [MIT](https://github.com/MARSELO10/ReducaoDimensionalidadeImagens)




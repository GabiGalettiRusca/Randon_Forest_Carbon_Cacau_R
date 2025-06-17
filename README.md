# 🌱 Modelagem Preditiva do Estoque de Carbono em Sistemas Agroflorestais com Cacau

Este repositório contém os scripts e documentos associados ao trabalho de modelagem preditiva com **Random Forest**, com foco no **estoque de carbono (tC/ha)** em sistemas agroflorestais tropicais consorciados com cacau. Foram utilizados dados reais do projeto RESTORE+ (IIASA, 2023), oriundos da Indonésia.

O trabalho contempla dois modelos principais:

- **Modelo 1**: Classificação do estoque de carbono (baixo, médio, alto)  
- **Modelo 2**: Regressão contínua do estoque de carbono

Este projeto foi desenvolvido na disciplina *Introdução ao Machine Learning (CAM 413)* na Universidade Federal de São Carlos (UFSCar).

**Autora**: Gabriela Galetti Rusca  
📧 **Contato**: ggrusca@ufscar.estudante.br  
📘 **Programa**: Pós-Graduação em Ciências Ambientais – UFSCar  
👨‍🏫 **Professor**: Dr. Marcos Roberto Benso

## 📁 Estrutura do Repositório

├── dados/        → Arquivo .csv ou .rds com a amostra utilizada  
├── figuras/      → Gráficos e visualizações  
├── scripts/      → Código-fonte em R (.R)  
├── relatorio/    → Relatório final em PDF  
├── README.md     → Este documento

## ⚙️ Requisitos

Para reproduzir os resultados, é necessário ter o R instalado com os seguintes pacotes:

```r
install.packages(c("caret", "randomForest", "pdp", "tidyverse", "dplyr"))



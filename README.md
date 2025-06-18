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

├── scripts/      → Código-fonte em R (.R)  
├── relatorio/    → Relatório final em PDF  
├── README.md     → Este documento

Link para base de dados: https://zenodo.org/records/7937135

## ⚙️ Requisitos

Para reproduzir os resultados, é necessário ter o R instalado com os seguintes pacotes:

```r
install.packages(c("caret", "randomForest", "pdp", "tidyverse", "dplyr"))
```
## ▶️ Como Executar
1 - Clone o repositório:
```
git clone https://github.com/seuusuario/Randon_Forest_Carbon_Cacau_R.git
```
2 - Abra o script em RStudio (scripts/modelo_carbono.R)
3 - Execute as células sequencialmente para:
4 - Carregar os dados
5 - Treinar os modelos de classificação e regressão
6 - Gerar as visualizações e resultados

## 🧠 Observações
Os dados utilizados são originários da Indonésia, com sistemas consorciados de cacau com café, dendê e coco.

## 📚 Referências
BREIMAN, L. Random Forests. Machine Learning, v. 45, n. 1, p. 5–32, 2001. DOI: 
https://doi.org/10.1023/A:1010933404324. Acesso em: 15 jun. 2025. 

GREENWELL, B. M. et al. pdp: Partial Dependence Plots. R package version 0.7.0, 2023. 
Disponível em: https://cran.r-project.org/package=pdp. Acesso em: 15 jun. 2025. 

KONGOR, J. E.; GOCKOWSKI, J.; WESSEL, M.; ASARE, R.; BESSEAU, P.; WEISE, S. Cocoa 
agroforestry systems for sustainable development: A global review. Sustainability, v. 16, n. 2, p. 
750, 2024. DOI: https://doi.org/10.3390/su16020750. Acesso em: 15 jun. 2025. 

KUHN, M. et al. caret: Classification and Regression Training. R package version 6.0-94, 2024. 
Disponível em: https://cran.r-project.org/package=caret. Acesso em: 15 jun. 2025. 

RESTORE+. Tree Productivity and Carbon in Agroforestry Systems – RESTORE+ Dataset 
Technical Note. IIASA, 2023. Disponível em: https://www.restoreplus.org. Acesso em: 15 jun. 
2025. 



# 🌱 Desafio 6 – Lixo Eletrônico na Amazônia  

Este repositório contém a solução do **Desafio VI** do programa I2A2 Academy, cujo objetivo é analisar dados fictícios de descarte de lixo eletrônico na Amazônia.  

O trabalho faz parte da trilha de **Manipulação e Visualização de Dados (Bloco 4)** e explora habilidades práticas em **Pandas, Matplotlib e Seaborn** para tratar, explorar e comunicar insights ambientais.  

---

## 📂 Estrutura do Repositório

- `I2A2_TAREFA6_GRUPOX.ipynb` → Notebook com a solução completa do desafio.  
- `desafio6_lixo_eletronico.csv` → Base de dados fictícia utilizada na análise (150 registros).  

---

## 📝 Descrição do Desafio

O descarte inadequado de resíduos eletrônicos é um problema crescente, especialmente na região amazônica, onde a logística e a falta de infraestrutura agravam a situação.  
Neste desafio, o papel dos **Tecnoguardas da Amazônia** é investigar a base de dados, encontrar padrões e propor soluções práticas.  

As etapas desenvolvidas foram:  

1. **Exploração inicial (EDA):** inspeção de estrutura, valores ausentes e duplicados.  
2. **Limpeza e padronização:** correção de inconsistências, remoção de duplicatas e tratamento de missing values.  
3. **Distribuições e frequências:** identificação dos tipos de eletrônicos mais descartados e suas origens.  
4. **Análise temporal:** evolução mensal do volume de descartes.  
5. **Agregação por município:** totais, peso médio e proporção de destinos formais vs. informais.  
6. **Cruzamentos:** análise entre tipo de eletrônico × destino (heatmap).  
7. **Impacto do peso:** estatísticas, boxplots, histograma e detecção de outliers.  
8. **Educação ambiental:** relação entre programas locais e destino do resíduo.  
9. **Correlação:** teste qui-quadrado entre origem × tipo de eletrônico.  
10. **Insight final:** integração dos resultados e proposta estratégica para a região.  

---

## ⚙️ Como Executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/desafio6-lixo-eletronico.git
   cd desafio6-lixo-eletronico
    ```

2. Abra o notebook no Jupyter ou Google Colab:
    - Google Colab → upload do arquivo .ipynb.
    - Ou rode localmente com:
    ``` bash
    jupyter notebook I2A2_TAREFA6_GRUPOX.ipynb
    ````

3. Certifique-se de que o arquivo desafio6_lixo_eletronico.csv esteja na mesma pasta.

---

## Tecnologias Utilizadas
- Python 3.10+
- Pandas
- Matplotlib
- Seaborn
- SciPy

---

## 🌍 Insight e Proposta
Os resultados mostram padrões críticos de descarte, tanto em termos de peso quanto de origem/destino.
A proposta final envolve:
- Pontos de coleta em municípios estratégicos,
- Campanhas de educação ambiental direcionadas, e
- Logística reversa fluvial para áreas de difícil acesso.

### Autora: Polyana – Graduanda em Biotecnologia / Cientista de Dados em formação.
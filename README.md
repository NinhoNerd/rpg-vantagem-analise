# Vantagem e Desvantagem no D&D 5e - Análise Matemática

Este repositório acompanha o vídeo publicado no canal [Ninho Nerd no YouTube](https://www.youtube.com/@ninhonerd), onde exploramos de forma prática e didática a mecânica de **vantagem e desvantagem** em testes com 1d20, utilizados no sistema **Dungeons & Dragons 5ª Edição**.

Se você já se perguntou **"quão melhor é rolar com vantagem?"**, ou **"quanto isso realmente aumenta a chance de sucesso?"**, este material é para você.

---

## Sobre o Notebook

O notebook `MatematicaVantagem.ipynb` implementa uma análise estatística completa da rolagem de dados no D&D 5e, cobrindo os seguintes pontos:

- **Cálculo da probabilidade de sucesso com rolagem normal (1d20)**  
  Para diferentes Classes de Dificuldade (CD), calculamos a chance exata de obter sucesso em uma jogada sem modificadores.

- **Cálculo da probabilidade com vantagem (rolar 2d20 e manter o maior valor)**  
  Utilizamos o conceito de **probabilidade complementar** para calcular a chance de sucesso ao rolar com vantagem.

- **Comparação direta entre os dois cenários**  
  Tabela e gráfico mostrando o quanto a vantagem aumenta (ou não) sua chance de sucesso em cada CD.

- **Visualização gráfica das distribuições**  
  Geração de gráficos com barras mostrando a diferença visual entre rolagens normais e com vantagem.

- **Cálculo do bônus equivalente da vantagem**  
  Estimamos qual seria o bônus numérico (como se fosse um modificador de +1, +2, etc.) que equivale ao benefício de ter vantagem. Esse valor varia com a CD.

---

## Como visualizar

Você pode:

- **Visualizar diretamente no GitHub** (sem execução, apenas o código e gráficos já gerados)
- **Executar no Google Colab**

---

## Requisitos

Para executar o notebook localmente, você precisa ter o Python instalado e as bibliotecas abaixo disponíveis:

```bash
pip install numpy pandas matplotlib

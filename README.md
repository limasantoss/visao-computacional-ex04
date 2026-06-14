# Atividade 04 — Pipeline de Visão Computacional

Projeto desenvolvido para a Atividade 04 da disciplina de Visão Computacional.

## Objetivo

Implementar um pipeline completo de processamento de imagens contendo:

* Aquisição da imagem
* Segmentação por limiarização de Otsu
* Operações morfológicas
* Identificação de objetos
* Extração de características
* Análise dos resultados

## Tecnologias Utilizadas

* Python 3
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Scikit-Image

## Estrutura do Projeto

```text
visao-computacional-ex04/
├── atividade04_visao_computacional.ipynb
└── imagens/
    └── imagem_atividade04.jpg
```

## Como Executar

1. Abra o notebook no Google Colab.
2. Execute todas as células.
3. A imagem será carregada automaticamente a partir do repositório.
4. O pipeline realizará a segmentação, identificação dos objetos e extração das características.

## Resultados

A imagem utilizada contém feijões distribuídos sobre um fundo claro.

O pipeline realiza:

* Conversão para escala de cinza
* Suavização Gaussiana
* Segmentação por Otsu
* Operações de abertura e fechamento
* Rotulagem de componentes conectados
* Extração de área, perímetro e centroide

## Autor

Igor Lima

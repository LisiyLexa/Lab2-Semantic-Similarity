# Семантическая схожесть предложений с использованием векторного представления

## Описание

Этот проект сосредотачивается на измерении семантической схожести между предложениями с использованием векторного представления. В проекте используются предварительно обученная модель векторного представления слов для создания векторов слов и предложений ([en_core_web_md](https://spacy.io/models/en#en_core_web_md)). Вектор предложения вычисляется как средний вектор его токенов. Схожесть вычисляется с помощью [косинусового коэффициента](https://en.wikipedia.org/wiki/Cosine_similarity).

## Запуск кода

Скачайте файл **similarity.ipynb** и запустите его с использованием python-ноутбука ([Jupyter](https://jupyter.org), [Google Colab](https://colab.research.google.com/), [Kaggle](https://www.kaggle.com/) или другие).

Или можете открыть его сразу в Colab:
<br><br>
<a target="_blank" href="https://colab.research.google.com/github/LisiyLexa/Lab2-Semantic-Similarity/blob/main/similarity.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

В данном файле есть форма для проверки текстов:
![form](https://github.com/LisiyLexa/Lab1-Semantic-Similarity/assets/81087786/25d8a7b9-f243-42f4-ab67-86d36a0476e9)

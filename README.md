# Curso NLP ISCTE 2021.4
Repositório com códigos relacionados ao mini-curso de NLP do ISCTE, realizado em abril de 2021.

*Importante*: Pressupõe-se que você já tenha instalado Python>=3.6, pip e consiga instanciar jupyter notebooks.

Para executar os notebooks, instale a bibliotecas listadas em requirements:

```
pip install -r requirements.txt
```

Após instalar as bibliotecas, baixe os modelos de linguagem para português e inglês:

```
python3 -m spacy download en_core_web_lg
python3 -m spacy download pt_core_news_lg
```
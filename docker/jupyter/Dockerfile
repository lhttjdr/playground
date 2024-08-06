FROM almondsh/almond:0.14.0-RC15-scala-3.3.3


RUN pip install ipywidgets \
    jupyterlab-lsp \
    "python-lsp-server[all]" \
    black \
    ruff \
    python-lsp-ruff \
    jupyterlab-code-formatter

RUN pip install langchain \
    langchain_core \
    langchain_community \
    langchain_openai \
    langchain_text_splitters \
    "unstructured[md]" \
    rank_bm25 \
    langchain_visualizer \
    sudachipy \
    sudachidict_full



# Introduction

馬場 真哉 著 『Pythonではじめる時系列分析入門』のサンプルコードをorg-modeで実行するためのforkです。


# 環境構築

    ls

pythonのインストール

    pyenv install 3.12
    pyenv local 3.12

仮想環境の作成

    python -m venv py_tsa_venv
    source py_tsa_venv/bin/activate
    python -m pip install --upgrade pip
    pip install -r 環境構築用資料/requirements.txt

jupyter kernelの作成

    python -m ipykernel install --user --name=py_tsa


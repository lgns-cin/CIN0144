# Setup
Recomendo instalar o [uv](https://docs.astral.sh/uv/getting-started/installation/) pra gerenciar o ambiente virtual do Python e todas as dependências, mas se não quiserem, vocês podem fazer na mão com o [requirements.txt](./requirements.txt).

### Instalação de dependências:

* **Com uv**:
```sh
uv sync
```

* **Sem uv**:

1. Crie o ambiente virtual

```sh
python -m virtualenv venv .venv
```

2. Ative o ambiente virtual (varia de plataforma a plataforma)
    * `.\.venv\Scripts\activate` no Windows Powershell, exemplo

3. Instale as dependências

```sh
pip install -r requirements.txt
```

# Importante

Os dados TÊM QUE ESTAR no diretório `data/`. Esse diretório TEM que ser ignorado pelo Git.
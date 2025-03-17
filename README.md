# estoque_python
Controle de estoque em Python

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```bash
git clone https://github.com/GabrielSellan/estoque_python.git
cd estoque_python
python3 -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

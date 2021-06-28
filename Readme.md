# Projeto E-commerce 
Um projeto extremamente simples de e-commerce (ainda incompleto) feito com 
Django 3.2.4 e Python 3.9.2.

### Conteúdo educacional
Este conteúdo foi criado no [Curso de Python 3 - Do Básico Ao Avançado (Completo)](https://www.udemy.com/course/python-3-do-zero-ao-avancado/).
Projeto para fixação do conteúdo ensinado no curso e outros conhecimentos que serão pesquisados.

### TODOs
Abaixo uma lista do que adicionei ou ainda pretendo adicionar.

- [ ] Model produtos
- [ ] Model variações
- [ ] Listagem e detalhes de produtos e variações
- [ ] Carrinho de compras baseado em session
- [ ] Remover produtos do carrinho
- [ ] Model perfil (criar e atualizar)
- [ ] Login e Logout do cliente
- [ ] Registrar pedido do cliente
- [ ] Cupons de desconto no carrinho de compras
- [ ] Cálculo de frete
- [ ] Página de pagamento
- [ ] Métodos de pagamento

### Tutorial para iniciantes
Abaixo uma lista de comandos para clonar e configurar este projeto na sua 
máquina local:

- Instalar git (Windows, Linux e Mac) e depois:

```
git clone https://github.com/JonathaCnB/ecommerce.git
```

- Para **Windows**:

```
cd ecommerce
python -m venv venv
venv\Scripts\activate.bat
python -m pip install --upgrade pip setuptools wheel --user
python -m pip install django django-debug-toolbar django-crispy-forms pillow
python manage.py migrate
```

- Para **Linux**:

```
cd ecommerce
python3.9 -m venv venv
. venv/bin/activate
pip install django django-debug-toolbar django-crispy-forms pillow
python manage.py migrate
```

- Para **Mac**

```
cd ecommerce
python -m venv venv
. venv/bin/activate
pip install django django-debug-toolbar django-crispy-forms pillow
python manage.py migrate
```

Pronto!

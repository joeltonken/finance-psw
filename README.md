# FI.NANCE
O projeto trata-se de um gerenciador de finanças pessoais desenvolvido durante o evento da PSW 7 da Pythonando. O objetivo é ajudar os usuários a acompanhar suas receitas, despesas e orçamentos de forma fácil e eficiente.

## Tecnologias utilizadas
- Python
- Django Framework
- HTML, CSS, JavaScript
- Bootstrap
- SQLite

## Funcionalidades
- Registro de Receitas: O usuário poderão cadastrar suas receitas, especificando o valor, a descrição e a data.
- Registro de Despesas: O usuário poderão registrar suas despesas, informando o valor, a descrição e a data.
- Categorias: As transações financeiras poderão ser categorizadas em essenciais e não essenciais.
- Relatórios: Os usuários terão acesso a relatórios detalhados, que exibirão as transações agrupadas por categoria e período.
- Saldo Disponível: O sistema calculará e exibirá o saldo disponível com base nas receitas e despesas registradas.

## Link do Figma
Acesse o [link do Figma](https://www.figma.com/file/9GhGdXv0fQyrT5ONvJoTGo/psw-7.0?type=design&node-id=0-1&mode=design) para visualizar o design do projeto.

## Instrução

### Clonar o repositório do projeto:
```
git clone https://github.com/joeltonken/finance-psw.git
```
### Criar o ambiente virtual
```
python -m venv venv
```
### Ative o venv
```bash
# linux: 

source venv/bin/activate

```

```bash
# windows: 

.\vevn\Scripts\activate

```

### Instale as dependências 
```
pip install -r requirements.txt
```
### Execute as migrações
```
./manage.py migrate
```
### Rode a aplicação
```
./manage.py runserver
```
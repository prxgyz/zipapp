cat << 'EOF' > README.md
# ZipApp - Sistema de Atendimento Online

Sistema automatizado para atendimento e vendas com:
- Gerenciamento de produtos e pedidos
- Autenticação de usuários
- Carrinho de compras
- Integração com sistemas de pagamento
- Controle de horário de funcionamento

## Instalação

1. Clone o repositório:
```bash
git clone [URL_DO_SEU_REPOSITORIO]
cd zipapp
```

2. Crie e ative o ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Configure as variáveis de ambiente:
```bash
cp .env.example .env
# Edite o arquivo .env com suas configurações
```

5. Inicialize o banco de dados:
```bash
python init_db.py
```

6. Execute a aplicação:
```bash
python app.py
```

## Uso no Google Colab

1. Monte o Google Drive
2. Clone este repositório na pasta desejada
3. Execute o notebook `zipapp_colab.ipynb`

## Estrutura do Projeto

```
zipapp/
├── templates/         # Templates HTML
├── static/           # Arquivos estáticos (CSS, JS)
├── database/         # Banco de dados SQLite
├── logs/            # Logs da aplicação
├── app.py           # Aplicação principal
├── models.py        # Modelos do banco de dados
├── config.py        # Configurações
└── requirements.txt # Dependências
```

## Contribuição

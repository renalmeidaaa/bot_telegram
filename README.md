# 🤖 Bot Telegram – Controle de Meta Diária

Bot em Python para **definir, registrar e acompanhar metas diárias diretamente pelo Telegram**, sem dependência de sistemas externos. Ideal para controle simples de produção, atendimentos, vendas ou qualquer contagem diária.

---

## 📌 Funcionalidades

- ✅ Definir meta diária  
- ➕ Registrar produção diária (+1)  
- 📊 Consultar status do dia  
- 👀 Visualizar meta configurada  
- 💾 Armazenamento local em arquivo `.json`  
- 🚀 Simples, leve e fácil de adaptar  

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10+  
- python-telegram-bot  
- JSON  
- Telegram Bot API  

---

## 📂 Estrutura do Projeto

```
bot-telegram-meta-diaria/
├── bot_diario.py
├── dados_diarios.json
└── README.md
```

---

## ⚙️ Pré-requisitos

- Python 3.10 ou superior  
- Conta no Telegram  
- Bot criado via **@BotFather**  

---

## 🚀 Instalação

Clone o repositório:

```bash
git clone https://github.com/seuusuario/bot-telegram-meta-diaria.git
cd bot-telegram-meta-diaria
```

Instale as dependências:

```bash
pip install python-telegram-bot
```

Edite o arquivo `bot_diario.py` e informe o token do bot:

```python
TOKEN = "SEU_TOKEN_DO_BOT"
```

Execute o bot:

```bash
python bot_diario.py
```

---

## 📲 Comandos do Bot

| Comando | Função |
|------|------|
| /menu | Exibe o menu |
| /setdiaria 10 | Define a meta diária |
| /registrar | Soma +1 no dia |
| /status | Mostra progresso diário |
| /verdiaria | Mostra a meta atual |

---

## 🧠 Exemplo de Uso

```
/setdiaria 20
/registrar
/status
```

Resposta:

```
📅 Data: 2026-02-05
✔️ Feito hoje: 1
🎯 Meta diária: 20
```

---

## 💾 Armazenamento

Os dados são salvos localmente no arquivo:

```
dados_diarios.json
```

Exemplo:

```json
{
  "meta": 20,
  "producao": {
    "2026-02-05": 1
  }
}
```

---

## 🔧 Melhorias Futuras

- Meta por usuário  
- Relatório semanal/mensal  
- Alerta ao atingir a meta  
- Banco de dados (SQLite/MySQL)  
- Execução automática no Windows  
- Hospedagem 24/7  

---

## 📄 Licença

Projeto livre para uso, estudo e adaptação.

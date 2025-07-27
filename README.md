# 📧 Email Automation com Python

Este projeto realiza o envio automático de e-mails usando Python e a biblioteca `schedule` para repetir a tarefa a cada 5 minutos.

## 🚀 Funcionalidades

- Envia e-mail automaticamente com corpo e assunto personalizados.
- Utiliza o Gmail com senha de aplicativo.
- Executa o envio a cada 5 minutos de forma contínua.

## 🛠️ Tecnologias Utilizadas

- Python 3
- `smtplib` e `email` (bibliotecas padrão do Python)
- `schedule` (para agendamento de tarefas)

## 🔐 Segurança

⚠️ **Nunca compartilhe sua senha de aplicativo publicamente!**  
Crie um arquivo `.env` ou outra solução segura para uso em produção.

## ▶️ Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ElvysSergioPascoal1425/email_automation.git
   cd email_automation
Instale a biblioteca necessária:
pip install schedule
Edite o arquivo envio_email_automatico.py e insira:

Seu e-mail do Gmail

Sua senha de aplicativo (gerada em https://myaccount.google.com/apppasswords)

Execute o script:

bash
Copiar
Editar

python envio_email_automatico.py


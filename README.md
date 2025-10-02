# 📩 Projeto: Workflow N8N - Captura Automática de Leads e Envio de E-mails  

## 📌 Descrição  
Este projeto implementa um **fluxo automatizado de geração e nutrição de leads** utilizando o **N8N**.  
O workflow captura dados de formulários preenchidos (armazenados em **Google Sheets**) e, em seguida, utiliza o **Google Gemini Chat Model** para analisar as informações e personalizar a comunicação com o lead.  
Após o processamento, o sistema dispara automaticamente um **e-mail personalizado via Gmail**, garantindo agilidade e escalabilidade no processo de follow-up.  

### Funcionalidades principais:  
- 📝 Captura automática de leads a partir de formulários  
- 📊 Armazenamento dos dados em Google Sheets  
- 🧠 Personalização da comunicação com IA (Google Gemini)  
- 📩 Envio automático de e-mails via Gmail  
- 🔄 Processo 100% automatizado, sem intervenção manual  

---

## 🛠️ Tecnologias utilizadas  
- [N8N](https://n8n.io/) – Automação de fluxos  
- [Google Sheets](https://www.google.com/sheets/) – Armazenamento de leads  
- [Google Gemini](https://ai.google/) – Inteligência artificial para personalização das mensagens  
- [Gmail API](https://developers.google.com/gmail) – Envio automatizado de e-mails  

---

## ⚙️ Estrutura do Workflow  
1. **On form submission** → Captura o envio de formulários  
2. **Append row in sheet** → Registra os dados no Google Sheets  
3. **AI Agent (Google Gemini Chat Model)** → Analisa e gera mensagem personalizada  
4. **Send a message (Gmail)** → Envia automaticamente o e-mail para o novo lead  

---

## 📷 Captura do Workflow  
![GERACAODELEADS](https://github.com/user-attachments/assets/80a2adef-4b3b-41bc-b6b3-ba047019a8c1)

---

## 🚀 Como usar  
1. Configure sua instância do **N8N**  
2. Conecte sua conta do **Google Sheets** para salvar os leads  
3. Configure o **Google Gemini Chat Model** como modelo de IA  
4. Configure as credenciais do **Gmail** para disparo de e-mails  
5. Ative o workflow e colete leads automaticamente  

---

## 📌 Autor  
Projeto desenvolvido por **Heytor Alves**

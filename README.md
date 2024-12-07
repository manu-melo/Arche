## Arche Bot - Gestão Administrativa do Projeto Nexus

**Bem-vindo ao repositório oficial do Arche Bot!**  
Arche é o bot desenvolvido para auxiliar as secretarias do **Projeto Nexus** em tarefas administrativas, simplificando processos como cadastros, registros e monitoramento de atividades cotidianas.  

---

## **Funcionalidades Principais**

### **1. Gerenciamento de Projetos**
- Cadastro de projetos em andamento, pausados ou concluídos.
- Detalhamento de responsáveis, verba pública e prazos.
- Comando:  
  `/projetos [órgão responsável] [status] [responsável 1] [responsável 2] [responsável 3] [data de início] [data de fim] [verba pública]`

### **2. Registro de Instituições**
- Cadastro de instituições públicas, financeiras e sociais.
- Categorização por tipo e status.  
- Comando:  
  `/instituto [nome] [órgão responsável] [status] [responsável] [tipo] [categoria] [verba pública]`

### **3. Registro de Ocorrências**
- Registra denúncias e investigações para acompanhamento.  
- Comando:  
  `/ocorrencia [órgão responsável] [status] [denunciante] [denunciado] [data da denúncia]`

### **4. Cadastro de Produtores**
- Armazena informações sobre produtores e suas atividades.  
- Comando:  
  `/produtores [órgão responsável] [status] [produtor] [cdn] [atividade]`

### **5. Emissão de Alvarás**
- Gera e monitora alvarás para empresas e negócios.  
- Comando:  
  `/alvara [órgão responsável] [status] [responsável 1] [responsável 2] [CNAE principal] [CNAE secundária] [nome da empresa] [data de registro] [data de validade]`

### **6. Registro de Empresas**
- Cadastro completo de empresas, áreas de atuação e dados de contato.  
- Comando:  
  `/empresa [órgão responsável] [status] [alvará] [responsável 1] [responsável 2] [CNAE principal] [nome da empresa] [data de registro] [data de validade]`

### **7. Gerenciamento de Funcionários Públicos**
- Cadastro de funcionários e controle de status (ativo, afastado, férias).  
- Comando:  
  `/funcionario [órgão responsável] [status] [nome] [cdn] [cargo] [data de registro]`

---

## **Pré-requisitos**
Antes de rodar o Arche Bot, certifique-se de ter:  
- **Node.js** (v16 ou superior).  
- **Discord.js** (v14 ou superior).  
- **Banco de Dados** (ex. MongoDB) configurado para armazenar os cadastros e logs.  
- **Acesso de administrador** ao servidor Discord onde o bot será implementado.

---

## **Instalação**
1. Clone este repositório:
   ```bash
   git clone https://github.com/manu-melo/Arche.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Configure o arquivo `.env` com os seguintes dados:
   ```
   DISCORD_TOKEN=seu_token_do_discord
   DATABASE_URL=sua_url_de_banco_de_dados
   PREFIX=/
   ```
4. Inicie o bot:
   ```bash
   npm start
   ```
---

## **Licença**
Este projeto está licenciado sob a **MIT License**. Consulte o arquivo `LICENSE` para mais informações.  


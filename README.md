# 📝 App de Lista de Tarefas

Aplicação web **full stack** para gerenciamento de tarefas, com autenticação de usuários e controle individual de dados.  
O projeto é focado em funcionalidades essenciais, com arquitetura preparada para **expansão futura**.

---

## 🎯 Escopo do Projeto

Permitir que usuários gerenciem suas próprias tarefas de forma simples, segura e organizada, garantindo que cada usuário visualize apenas os seus dados.

---

## ✅ Funcionalidades

- ✔ Cadastro de usuário  
- ✔ Login  
- ✔ Cada usuário visualiza apenas as suas próprias tarefas  
- ✔ Criar tarefa  
- ✔ Editar tarefa  
- ✔ Concluir tarefa  
- ✔ Excluir tarefa  

---

## 🧰 Tecnologias Utilizadas

### 📚 Documentação
- ✔ Astah  
- Diagramas:
  - Casos de uso  
  - Classes  
  - Sequência  

### 🗄 Banco de Dados
- ✔ SQLite3  

### 🎨 Design das Telas
**Responsável:** Débora  
- ✔ Figma  

### 💻 Front-end
**Responsável:** Débora  
- ✔ React  
- ✔ TypeScript  
- ✔ Ant Design  

### 🔙 Back-end
**Responsável:** Denilo  
- ✔ Python  
- ✔ Flask  

### ☁️ Deploy / Nuvem
**Responsáveis:** Ambos  
- 🔧 Vercel *(em estudo para deploy)*

---

## ▶️ Como Executar o Projeto

### Pré-requisitos
- Node.js  
- Python 3.x  
- Git  

### 🔙 Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
flask run

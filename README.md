# Projeto IaC – Deploy Automático de Site com Apache (Linux)

Este repositório contém um script **Bash** para automatizar a atualização do servidor Linux, instalação do Apache e publicação automática de um site estático utilizando **Infrastructure as Code (IaC)**.

---

## 📌 Descrição

O script realiza as seguintes etapas automaticamente:

1. Atualiza os pacotes do sistema
2. Instala o servidor web **Apache**
3. Instala a ferramenta **unzip**
4. Faz o download de um site hospedado no GitHub
5. Descompacta os arquivos
6. Copia o conteúdo para o diretório padrão do Apache (`/var/www/html`)
7. Publica o site imediatamente no servidor

---

## 🛠️ Tecnologias Utilizadas

- **Linux (Debian/Ubuntu)**
- **Bash Script**
- **Apache HTTP Server**
- **wget**
- **unzip**
- **GitHub (repositório de origem do site)**

---

## 📂 Estrutura do Projeto

```text
.
├── script-iac2.sh
└── README.md

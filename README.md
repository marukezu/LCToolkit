# 🛠️ LC Toolkit

LC Toolkit é uma ferramenta interna desenvolvida para otimizar e padronizar o suporte técnico em ambientes Windows.

O objetivo do projeto é centralizar ações recorrentes do dia a dia, reduzir tempo de atendimento e minimizar erros operacionais.

---

## 🚀 Principais funcionalidades

### 🔧 Ações rápidas do sistema
- Abrir CMD, PowerShell e Executar com privilégios de administrador
- Acesso rápido a ferramentas do Windows
- Execução de comandos automatizados (ex: reset de spooler)

---

### 📦 Instalação de softwares
- Download e execução de instaladores diretamente pelo app
- Suporte a links diretos e catálogo remoto
- Base preparada para instalação silenciosa

---

### 🌐 Catálogo remoto (GitHub)
- Lista de aplicações gerenciada via JSON
- Atualizações sem necessidade de recompilar o sistema
- Separação entre lógica (C#) e dados (JSON)

---

### 🏢 Suporte por empresa
- Estrutura para cadastro de múltiplas empresas
- Carregamento dinâmico de informações (logo, links, agentes, etc)
- Base para padronização de ambientes por cliente

---

### 🖼️ Carregamento dinâmico de assets
- Logos das empresas carregadas diretamente do GitHub
- Integração via URLs públicas (raw)

---

### 📊 Sistema de logs
- Registro centralizado de ações
- Exibição em tempo real no aplicativo
- Estrutura preparada para expansão (arquivo, API, etc)

---

## 🧠 Arquitetura

O projeto segue uma organização baseada em separação de responsabilidades:

- **Forms** → Interface do usuário
- **Actions** → Execução de tarefas
- **Services** → Comunicação externa (HTTP / JSON)
- **Statics** → Configurações globais
- **JSON Models** → Estrutura de dados

---

## 🔄 Estrutura baseada em dados

O LC Toolkit utiliza arquivos JSON hospedados no GitHub para controle dinâmico:

- `catalog.json` → aplicações
- `companies.json` → empresas

Isso permite:

- Atualizações remotas
- Escalabilidade
- Flexibilidade na manutenção

---

## ⚙️ Tecnologias utilizadas

- C# (.NET / Windows Forms)
- PowerShell (execução de comandos do sistema)
- JSON (configuração dinâmica)
- HTTP (consumo de dados remotos)

---

## 📌 Objetivo do projeto

O LC Toolkit não é apenas um conjunto de atalhos, mas uma base para evolução de uma central de suporte mais inteligente, podendo futuramente incluir:

- Atualização automática do sistema
- Execução remota de tarefas (agent)
- Integração com APIs externas
- Padronização completa do ambiente de clientes

---

## 🧪 Status

🚧 Em desenvolvimento ativo

---

## 👨‍💻 Autor

Desenvolvido como ferramenta interna para otimização de processos de suporte técnico.

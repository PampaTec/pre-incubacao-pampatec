# 🚀 PampaTec - Jornada do BMC ao MVP

Bem-vindo à jornada de pré-incubação do **PampaTec**! Este repositório é o template base para times de empreendedores validarem seus modelos de negócio utilizando o **Business Model Canvas (BMC)** com o apoio de um consultor de IA.

---

## 📋 Como Começar (Para Empreendedores)

> 📖 **Primeira vez usando GitHub ou Antigravity?** Siga o [Tutorial do GitHub e Antigravity](Tutorial_GitHub_Antigravity.md) com o passo a passo completo para iniciantes.

### 1. Pré-requisitos
- [Google Antigravity](https://gemini.google.com/antigravity) instalado no seu computador
- Git instalado no seu computador
- Conta no GitHub

### 2. Clone o repositório do seu time
```bash
# Exemplo de URL de um time dentro da organização
git clone https://github.com/pampatec/nome-da-sua-startup.git
cd nome-da-sua-startup
```

### 3. Abra no Antigravity
Abra a pasta clonada como **workspace** no Antigravity.

---

## 👥 Gestão e Acompanhamento (Para Mentores)

Para gerenciar múltiplos times de forma profissional e centralizada, recomendamos o uso de uma **Organização no GitHub** (ex: `github.com/pampatec-incubadora`).

### 📐 Por que usar uma Organização?
1. **Centralização:** Todos os projetos de todos os times ficam em um único lugar.
2. **Visibilidade:** Mentores podem ver o arquivo `PROGRESSO_BMC.md` de qualquer time clicando no repositório correspondente.
3. **Controle de Acesso:** Você pode dar permissão de "Escrita" para os empreendedores e manter os mentores como "Admins" ou "Maintainers".
4. **Fácil escala:** Quando um novo ciclo de pré-incubação começar, basta criar novos repositórios dentro da mesma organização.

### 🏗️ Como Configurar a Estrutura

#### Passo 1 — Criar a Organização (Só uma vez)
1. No GitHub, clique no seu perfil e vá em **Settings** → **Organizations** → **New organization**.
2. Escolha o plano "Free" e dê um nome (ex: `pampatec-incubadora`).

#### Passo 2 — Subir o Template na Organização
1. Crie um repositório chamado `jornada-bmc-template` dentro da organização.
2. Ative a opção **"Template repository"** nas configurações (Settings → General) para facilitar o fork pelos times.

#### Passo 3 — Criar o Repositório de cada Time
1. No repositório template, clique em **"Use this template"** → **"Create a new repository"**.
2. Selecione a organização como proprietária e coloque o nome do time/startup.
3. Em **Settings** → **Collaborators and teams**, adicione os membros do time.

---

## 📊 Acompanhamento do Progresso

O arquivo **`PROGRESSO_BMC.md`** é atualizado automaticamente pelo consultor de IA a cada etapa concluída.

**Mentores:**
- Acesse a página da Organização no GitHub.
- Clique no repositório do time que deseja revisar.
- Abra o arquivo `PROGRESSO_BMC.md` para ver o status atual (etapa X de 9) e as decisões tomadas.

---

## 📂 Estrutura do Repositório

```
📦 seu-repositorio/
├── 📄 README.md               ← Instruções gerais
├── 📄 PROGRESSO_BMC.md         ← Checklist de evolução (IA atualiza)
└── 📂 .agent/
    └── 📂 skills/
        └── 📄 skill_consultor_pampatec.md  ← Cérebro do consultor
```

---

## 🤝 Mentoria PampaTec

Este projeto faz parte do programa de pré-incubação do **PampaTec - Incubadora Tecnológica da Unipampa**. Os mentores acompanham o progresso de cada time pelo GitHub.

**Dúvidas?** Fale com seu mentor ou abra uma **Issue** no repositório do seu time.

---

> *"A melhor maneira de prever o futuro é criá-lo."* — Peter Drucker

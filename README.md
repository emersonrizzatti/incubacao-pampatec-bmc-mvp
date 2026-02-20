# 🚀 PampaTec - Jornada do BMC ao MVP

Bem-vindo à jornada de pré-incubação do **PampaTec**! Este repositório é o template base para times de empreendedores validarem seus modelos de negócio utilizando o **Business Model Canvas (BMC)** com o apoio de um consultor de IA.

---

## 📋 Como Começar (Para Empreendedores)

> 📖 **Primeira vez usando GitHub ou Antigravity?** Siga o [Tutorial do GitHub e Antigravity](Tutorial_GitHub_Antigravity.md) com o passo a passo completo para iniciantes.

### 1. Pré-requisitos
- [Google Antigravity](https://gemini.google.com/antigravity) instalado no seu computador
- Acesso ao [GitHub do PampaTec](https://github.com/emersonrizzatti)
- Git instalado no seu computador

### 2. Clone o repositório do seu time
```bash
git clone https://github.com/emersonrizzatti/incubacao-pampatec-bmc-mvp.git
cd incubacao-pampatec-bmc-mvp
```

### 3. Abra no Antigravity
Abra a pasta clonada como **workspace** no Antigravity.

### 4. Inicie a Consultoria
Na conversa com o Antigravity, digite:

> **"Sou empreendedor e quero validar minha startup. Use o skill de Consultor PampaTec para me guiar pelas 9 etapas do BMC."**

O Antigravity assumirá o papel de consultor e guiará você por todas as etapas!

---

## 📂 Estrutura do Repositório

```
📦 seu-repositorio/
├── 📄 README.md               ← Você está aqui
├── 📄 PROGRESSO_BMC.md         ← Progresso do time (atualizado automaticamente)
└── 📂 .agent/
    └── 📂 skills/
        └── 📄 skill_consultor_pampatec.md  ← Skill do consultor de IA
```

---

## 📊 Acompanhamento do Progresso

O arquivo **`PROGRESSO_BMC.md`** é atualizado automaticamente pelo consultor a cada etapa concluída. Nele você encontra:

- ✅ Status de cada uma das 9 etapas do BMC
- 📅 Datas de conclusão
- 📝 Resumo das decisões tomadas em cada etapa
- 🔍 Análise Crítica Final com diagnóstico do modelo

**Mentores:** Acesse o `PROGRESSO_BMC.md` de cada time diretamente no GitHub para acompanhar o progresso.

---

## 👥 Gestão de Times no GitHub

Este repositório funciona como **template**. Cada time recebe uma cópia independente (fork) para trabalhar.

### 📐 Estrutura no GitHub

```
github.com/emersonrizzatti/
├── 📦 incubacao-pampatec-bmc-template       ← este repositório (template base)
├── 📦 time-startup-alpha                    ← fork do template
├── 📦 time-startup-beta                     ← fork do template
├── 📦 time-startup-gamma                    ← fork do template
└── ...
```

### 🏗️ Como Criar o Repositório de um Novo Time (Para Mentores)

#### Passo 1 — Hospedar o template (só na primeira vez)
1. Acesse [github.com/new](https://github.com/new)
2. Nome: `incubacao-pampatec-bmc-template`
3. Visibilidade: **Public** ou **Private**
4. Faça push de todos os arquivos deste repositório para lá:
   ```bash
   cd <pasta-deste-projeto>
   git init
   git remote add origin https://github.com/emersonrizzatti/incubacao-pampatec-bmc-template.git
   git add .
   git commit -m "Template inicial BMC"
   git push -u origin main
   ```

#### Passo 2 — Criar o repositório de cada time
1. Acesse o projeto template no GitHub.
2. Clique em **"Fork"** (botão no canto superior direito)
3. Em **"Repository name"**, coloque o nome do time (ex: `time-startup-alpha`)
4. Clique em **"Create fork"**
5. No projeto criado, vá em **Settings** → **Collaborators** → adicione os membros do time.

#### Passo 3 — Acompanhar o progresso dos times
- **Direto no GitHub:** Acesse `PROGRESSO_BMC.md` de cada projeto do time pelo navegador.
- **Visão geral:** Na página do perfil ou organização, você vê todos os projetos e atividades recentes.

---

## 🗺️ As 9 Etapas do BMC

| # | Etapa | O que você vai definir |
|---|-------|-----------------------|
| 1 | **Proposta de Valor** | O valor que sua solução entrega ao cliente |
| 2 | **Segmento de Clientes** | Quem são seus clientes ideais |
| 3 | **Relacionamento** | Como atrair, engajar e manter clientes |
| 4 | **Canais** | Como o cliente conhece e recebe seu produto |
| 5 | **Fontes de Receita** | Como gerar receita sustentável |
| 6 | **Parcerias** | Parceiros estratégicos do negócio |
| 7 | **Recursos** | Ativos críticos para o funcionamento |
| 8 | **Atividades-Chave** | O que fazer bem para o modelo funcionar |
| 9 | **Estrutura de Custos** | Principais custos da operação |

Ao final, o consultor realizará uma **Análise Crítica Final** com diagnóstico do modelo e sugestão de MVP.

---

## 🤝 Mentoria PampaTec

Este projeto faz parte do programa de pré-incubação do **PampaTec - Incubadora Tecnológica da Unipampa**. Os mentores acompanham o progresso de cada time pelo arquivo `PROGRESSO_BMC.md` e pelo painel do GitHub.

**Dúvidas?** Fale com seu mentor ou abra uma **Issue** no repositório do seu time.

---

> *"A melhor maneira de prever o futuro é criá-lo."* — Peter Drucker

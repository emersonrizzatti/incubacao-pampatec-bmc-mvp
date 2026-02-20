# 🚀 PampaTec - Jornada do BMC ao MVP

Bem-vindo à jornada de pré-incubação do **PampaTec**! Este repositório é o template base para times de empreendedores validarem seus modelos de negócio utilizando o **Business Model Canvas (BMC)** com o apoio de um consultor de IA.

---

## 📋 Como Começar (Para Empreendedores)

> 📖 **Primeira vez usando GitLab ou Antigravity?** Siga o [Tutorial do GitLab e Antigravity](Tutorial_GitLab_Antigravity.md) com o passo a passo completo para iniciantes.

### 1. Pré-requisitos
- [Google Antigravity](https://gemini.google.com/antigravity) instalado no seu computador
- Acesso ao [GitLab do PampaTec](https://gitlab.unipampa.edu.br/pampatec)
- Git instalado no seu computador

### 2. Clone o repositório do seu time
```bash
git clone https://gitlab.unipampa.edu.br/pampatec/<nome-do-seu-time>.git
cd <nome-do-seu-time>
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

**Mentores:** Acesse o `PROGRESSO_BMC.md` de cada time diretamente no GitLab para acompanhar o progresso.

---

## 👥 Gestão de Times no GitLab

Este repositório funciona como **template**. Cada time recebe uma cópia independente (fork) para trabalhar.

### 📐 Estrutura no GitLab

```
gitlab.unipampa.edu.br/pampatec/
├── 📦 bmc-template              ← este repositório (template base)
├── 📦 time-startup-alpha         ← fork do template
├── 📦 time-startup-beta          ← fork do template
├── 📦 time-startup-gamma         ← fork do template
└── ...
```

### 🏗️ Como Criar o Repositório de um Novo Time (Para Mentores)

#### Passo 1 — Hospedar o template (só na primeira vez)
1. Acesse [gitlab.unipampa.edu.br/pampatec](https://gitlab.unipampa.edu.br/pampatec)
2. Clique em **"New project"** → **"Create blank project"**
3. Nome: `bmc-template`
4. Visibilidade: **Internal** (visível para membros da instituição)
5. Faça push de todos os arquivos deste repositório para lá:
   ```bash
   cd <pasta-deste-projeto>
   git init
   git remote add origin https://gitlab.unipampa.edu.br/pampatec/bmc-template.git
   git add .
   git commit -m "Template inicial BMC"
   git push -u origin main
   ```

#### Passo 2 — Criar o repositório de cada time
1. Acesse o projeto template: [gitlab.unipampa.edu.br/pampatec/bmc-template](https://gitlab.unipampa.edu.br/pampatec/bmc-template)
2. Clique em **"Fork"** (botão no canto superior direito)
3. Em **"Project name"**, coloque o nome do time (ex: `time-startup-alpha`)
4. Em **"Namespace"**, selecione **pampatec**
5. Clique em **"Fork project"**
6. No projeto criado, vá em **Settings** → **Members** → adicione os membros do time como **Developer**

#### Passo 3 — Acompanhar o progresso dos times
- **Direto no GitLab:** Acesse `PROGRESSO_BMC.md` de cada projeto do time pelo navegador
- **Visão geral:** Na página do grupo [pampatec](https://gitlab.unipampa.edu.br/pampatec), você vê todos os projetos e atividades recentes

> [!TIP]
> **Dica:** Use **Issues** no GitLab para marcar milestones de cada time. Crie labels como `etapa-1`, `etapa-2`, etc., para filtrar o progresso visualmente.

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

Este projeto faz parte do programa de pré-incubação do **PampaTec - Incubadora Tecnológica da Unipampa**. Os mentores acompanham o progresso de cada time pelo arquivo `PROGRESSO_BMC.md` e pelo painel do GitLab.

**Dúvidas?** Fale com seu mentor ou abra uma **Issue** no repositório do seu time.

---

> *"A melhor maneira de prever o futuro é criá-lo."* — Peter Drucker

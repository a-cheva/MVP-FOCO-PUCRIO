

```markdown
# Foco — Aplicativo Mobile de Produtividade

> MVP — Pós-Graduação em Interação Humano-Computador | PUC-Rio | 2026

---

## Sobre o Projeto

**Foco** é um aplicativo mobile de produtividade projetado para pessoas que enfrentam dificuldades de organização e procrastinação no dia a dia. Diferente de ferramentas tradicionais, o Foco é construído sobre um princípio de simplicidade intencional: menos funcionalidades, mais direcionamento.

O app combina classificação automática de tarefas por urgência e importância, três categorias de vida fixas (Trabalho, Casa e Estudos) e um Modo Foco Total com bloqueio seletivo de aplicativos distratores durante sessões de concentração.

O projeto foi desenvolvido como MVP no contexto da disciplina de Projeto de Interação, com foco em pesquisa de usuário, modelagem de interação (MoLIC) e prototipagem de alta fidelidade no Figma com Material Design 3.

---

## Personas

| Persona | Perfil |
|---|---|
| **Mariana Santos** | 28 anos, analista de RH, home office integral. Padrão de procrastinação: dispersão por início — começa várias tarefas ao mesmo tempo mas não termina nenhuma. |
| **Rafael Hoseok** | 32 anos, eletricista autônomo + universitário + entregas noturnas. Padrão de procrastinação: evitação seletiva — está sempre ocupado, mas nunca com o que precisa. |

---

## Objetivos de Interação (MoLIC)

- **Objetivo 1 — Mariana:** Adicionar e classificar uma tarefa (modo rápido ou detalhado → classificação automática por prioridade)
- **Objetivo 2 — Rafael:** Configurar e iniciar uma sessão de Modo Foco Total (via lembrete 19h → escolher tarefa → configurar sessão → sessão em andamento → conquista)

---

## Fluxo do Protótipo (Objetivo 2 — Rafael)

```
Ver tarefas do dia
  ↓
Escolher tarefa  →  [2.1] Ver aviso de tarefa indisponível
  ↓
Focar em uma tarefa
  ↓
Configurar sessão  →  [4.1] Ver erro de bloqueio
  ↓        ↓
  ↓    Configurar recorrência
  ↓
Sessão em andamento  →  [6.1] Sessão sem bloqueio
  ↓
Ver conquista
```

---

## Protótipo Figma

🔗 [Acessar protótipo no Figma] https://www.figma.com/proto/1JznLsYo0QxFU40GqzPIjR/MVP---Foco---Andrieli-Cheva?node-id=182-1414&viewport=755%2C25%2C0.04&t=SLNnjMXVz1J00ChY-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=182%3A1414&show-proto-sidebar=1&page-id=0%3A1)

O arquivo contém:
- Personas e diagrama MoLIC
- Style Guide (tipografia, paleta de cores)
- Biblioteca de componentes Material Design 3
- 10 telas do fluxo completo com labels MoLIC
- Seção de componentes organizados por grupo

---

## Estrutura do Repositório

```
foco-app-mvp/
├── README.md
├── relatorio/
│   └── relatorio-mvp-foco.pdf
└── molic/
    └── diagrama-molic-foco.pdf
```

---

## Design System e Metodologia

- **Design System:** Material Design 3 (MD3)
- **Ferramenta:** Figma
- **Modelagem de interação:** MoLIC (Model of Interaction as Language-based Conversation)
- **Classificação de tarefas:** Urgência × Importância (automática pelo sistema)

---

## Como navegar no protótipo

1. Acesse o link do Figma acima
2. Clique em **Present** (▶) no menu superior
3. Comece pela tela **"01 · Ver tarefas do dia"**

---

## Autora

**Andrieli Cheva**
Pós-Graduação em Interação Humano-Computador — PUC-Rio
📧 a.cheva7082@gmail.com
```

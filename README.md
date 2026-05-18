# 🧠 claude-skills

Repositório de skills personalizadas para uso com o **Claude AI** — desenvolvidas por [Leandro Marques Pitol](https://github.com/leandropitol) para operações em pine chemicals, inteligência de dados, gestão da qualidade e automação de processos.

---

## O que são Skills?

Skills são arquivos `SKILL.md` que instruem o Claude a se comportar como um especialista em um domínio específico. Quando carregadas no contexto do Claude, ativam raciocínio aprofundado, frameworks e boas práticas para aquele tema.

---

## 📦 Skills disponíveis

| Skill | Domínio | Descrição |
|-------|---------|-----------|
| [storytelling-dados](./skills/storytelling-dados/SKILL.md) | Dados & Visualização | Especialista em comunicação visual de dados baseado nos princípios de Cole Nussbaumer Knaflic. Cobre escolha de gráficos, eliminação de saturação, atributos pré-atentivos, narrativa com dados e checklists de publicação. |
| [regulacao-reach](./skills/regulacao-reach/SKILL.md) | Conformidade Química / Exportação para UE | Especialista em Regulamento REACH (CE nº 1907/2006) para fabricantes, importadores, distribuidores e utilizadores a jusante. Cobre registo de substâncias, SVHC/Lista Candidata, Anexo XIV (autorização), Anexo XVII (restrições), FDS/SDS com cenários de exposição, Only Representative para exportadores não-UE, e taxas ECHA. |
| [iso9001-sgq](./skills/iso9001-sgq/SKILL.md) | Gestão da Qualidade / SGQ | Sistema multi-agente para ISO 9001:2015 com 8 agentes especializados: não conformidades (NC/CAPA/8D), auditoria interna, controle de documentos, gestão de riscos, calibração metrológica, planejamento estratégico e análise crítica pela direção. |

---

## 🚀 Como usar

### Instalar via arquivo `.skill` (recomendado para Cowork)

1. Baixe o arquivo `regulacao-reach.skill` da pasta da skill desejada
2. Clique duas vezes para instalar no Claude Cowork

### Usar o SKILL.md diretamente

Cole o conteúdo do `SKILL.md` no início de uma conversa com o Claude, ou adicione-o como documento de contexto.

---

## 📁 Estrutura do repositório

```
skills/
├── storytelling-dados/
│   └── SKILL.md
└── regulacao-reach/
    ├── SKILL.md
    ├── regulacao-reach.skill        ← arquivo de instalação para Cowork
    └── references/
        └── definicoes-reach.md      ← glossário Art. 3 REACH
```

---

## 🔗 Contexto

Skills desenvolvidas no contexto da **RJ Comércio e Extração de Resinas Ltda.**, operando na cadeia de pine chemicals (goma resina, breu/colofônia, terebintina) com foco em exportação e conformidade regulatória internacional.

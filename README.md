# 🧠 claude-skills

Repositório de skills personalizadas para uso com o **Claude AI** — desenvolvidas por [Leandro Marques Pitol](https://github.com/leandropitol) para operações em pine chemicals, inteligência de dados, gestão da qualidade e automação de processos.

---

## O que são Skills?

Skills são arquivos `SKILL.md` que instruem o Claude a se comportar como um especialista em um domínio específico. Quando carregadas no contexto do Claude, ativam raciocínio aprofundado, frameworks e boas práticas para aquele tema.

---

## 📦 Skills disponíveis

| Skill | Domínio | Descrição |
|-------|---------|-----------|
| [avaliacao-rural](./skills/avaliacao-rural/README.md) | Engenharia de Avaliações / Mercado de Terras | Co-piloto técnico para laudos de imóveis rurais conforme NBR 14653. Cobre MCDDM, Método Evolutivo, Capitalização da Renda, Box Plot, homogeneização, graus de fundamentação e precisão, VTN/VTI, análise LTV para crédito rural (BACEN 4.676/2018) e Atlas INCRA 2025. |
| [ghs-fispq](./skills/ghs-fispq/README.md) | Conformidade Química / Segurança | Especialista em GHS (ONU ST/SG/AC.10/30/Rev.10) e sua implementação brasileira via ABNT NBR 14725 (FISPQ). Elabora fichas de segurança, rótulos GHS, classifica substâncias/misturas, consulta códigos H/P e audita documentos. |
| [regulacao-reach](./skills/regulacao-reach/README.md) | Conformidade Química / Exportação para UE | Especialista em Regulamento REACH (CE nº 1907/2006) para fabricantes, importadores, distribuidores e utilizadores a jusante. Cobre registo de substâncias, SVHC/Lista Candidata, Anexo XIV (autorização), Anexo XVII (restrições), FDS/SDS com cenários de exposição, Only Representative para exportadores não-UE, e taxas ECHA. |
| [iso9001-sgq](./skills/iso9001-sgq/README.md) | Gestão da Qualidade / SGQ | Sistema multi-agente para ISO 9001:2015 com 8 agentes especializados: não conformidades (NC/CAPA/8D), auditoria interna, controle de documentos, gestão de riscos, calibração metrológica, planejamento estratégico e análise crítica pela direção. |
| [storytelling-dados](./skills/storytelling-dados/SKILL.md) | Dados & Visualização | Especialista em comunicação visual de dados baseado nos princípios de Cole Nussbaumer Knaflic. Cobre escolha de gráficos, eliminação de saturação, atributos pré-atentivos, narrativa com dados e checklists de publicação. |

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
├── avaliacao-rural/
│   ├── README.md
│   ├── SKILL.md
│   ├── avaliacao-rural.skill        ← arquivo de instalação para Cowork
│   └── references/
│       ├── NBR 14653-5 Parte 1, 3, 4, 5 e Parte 6 (NBR 14653-6)
│       ├── Atlas_do_Mercado_de_Terras_2025.md
│       ├── planilha-vtn-2025-para-publicacao-6.md
│       └── RESOLUCAO_N4676_DE_31_DE_JULHO_DE_2018.md
├── ghs-fispq/
│   ├── README.md
│   ├── SKILL.md
│   ├── ghs-fispq.skill              ← arquivo de instalação para Cowork
│   └── references/
│       ├── h-p-statements.md
│       ├── rotulagem-ghs.md
│       ├── sds-16-secoes.md
│       └── auditoria-checklist.md
├── regulacao-reach/
│   ├── README.md
│   ├── SKILL.md
│   ├── regulacao-reach.skill        ← arquivo de instalação para Cowork
│   └── references/
│       └── definicoes-reach.md
├── iso9001-sgq/
│   ├── README.md
│   ├── SKILL.md
│   ├── iso9001-sgq.skill            ← arquivo de instalação para Cowork
│   └── references/
│       └── agentes 1–8 (arquivos de cada agente especializado)
└── storytelling-dados/
    └── SKILL.md
```

---

## 🔗 Contexto

Skills desenvolvidas no contexto da **RJ Comércio e Extração de Resinas Ltda.**, operando na cadeia de pine chemicals (goma resina, breu/colofônia, terebintina) com foco em exportação e conformidade regulatória internacional.

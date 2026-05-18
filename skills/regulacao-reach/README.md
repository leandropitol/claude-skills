# 🧪 regulacao-reach

Skill especializada em **Regulamento REACH** (Regulamento CE nº 1907/2006) para fabricantes, importadores, distribuidores e utilizadores a jusante de substâncias e misturas químicas que operam no mercado europeu ou exportam para a UE.

---

## 🎯 O que esta skill faz

Quando ativada, o Claude responde como um consultor especializado em conformidade REACH, com domínio de todos os títulos, anexos e regulamentos de execução associados. As respostas são orientadas à ação prática, com referências legais precisas e estrutura de tomada de decisão.

---

## ⚡ Quando ativa automaticamente

A skill dispara ao mencionar qualquer um destes termos:

- REACH, registo de substâncias, dossiê ECHA
- FDS / SDS / ficha de dados de segurança
- SVHC, Lista Candidata, substância de elevada preocupação
- Anexo XIV (autorização), Anexo XVII (restrições)
- Only Representative / Representante Único
- Utilizador a jusante / downstream user
- Cenários de exposição / CSR / avaliação de segurança química
- Substâncias em artigos (Art. 7 ou 33)
- PBT, vPvB, CMR
- Taxas ECHA, Reg. 340/2008
- "Tenho obrigações REACH?", "Como exportar químicos para a Europa?"

---

## 📋 Casos de uso cobertos

| Perfil | Exemplo de pergunta |
|--------|---------------------|
| **Exportador não-UE** | "Fabricamos colofônia no Brasil e exportamos 3.000 t/ano para a Europa. Temos obrigações REACH?" |
| **Formulador / DU** | "Usamos xileno na formulação de solventes. Precisamos de CSR próprio?" |
| **Importador de artigos** | "Importamos móveis da China. Como notificar SVHC à ECHA?" |
| **Distribuidor** | "Um produto que vendemos entrou no Anexo XIV. Podemos continuar vendendo?" |
| **Qualquer empresa** | "O que é SVHC?", "Qual o limiar de tonelagem para registo?" |

---

## 📦 Conteúdo da pasta

| Arquivo | Descrição |
|---------|-----------|
| `SKILL.md` | Skill principal — base normativa, workflow de resposta e exemplos práticos |
| `references/definicoes-reach.md` | Glossário das definições-chave do Art. 3 do REACH (substância, mistura, artigo, DU, OR, SVHC, PBT, vPvB, CMR, DNEL, PNEC, UVCB…) |
| `regulacao-reach.skill` | Arquivo de instalação para Claude Cowork (clique duas vezes para instalar) |

---

## ⚖️ Base normativa coberta

| Regulamento | Assunto |
|-------------|---------|
| Reg. (CE) 1907/2006 | REACH — regulamento principal |
| Reg. (CE) 340/2008 (cons. nov/2025) | Taxas e encargos ECHA |
| Reg. (UE) 2016/9 | Submissão conjunta e partilha de dados |
| Reg. (UE) 2019/1692 | Substâncias de fase-in pós-prazo |
| Reg. (UE) 2020/1435 | Prazos de atualização de registos |
| Reg. (UE) 2023/464 | Atualização de métodos de ensaio |
| Reg. (UE) 2025/2573 | Atualização de métodos de ensaio (2025) |
| Reg. (UE) 2026/859 | Restrição 2,4-DNT em artigos (Anexo XVII) |

---

## 🚀 Como instalar

**Cowork (recomendado):** baixe `regulacao-reach.skill` e clique duas vezes para instalar.

**Claude.ai / API:** copie o conteúdo de `SKILL.md` e cole no início da conversa ou como documento de contexto.

---

## 🌲 Contexto

Desenvolvida para operações de pine chemicals com exportação para a UE — especialmente relevante para fabricantes de colofônia/breu (CAS 8050-09-7), terebintina e derivados resinosos que precisam navegar as obrigações REACH como exportadores não-UE ou através do mecanismo de Only Representative (Art. 8).

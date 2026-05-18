# GHS / FISPQ / Rotulagem Química

Skill especialista em **GHS (Sistema Globalmente Harmonizado de Classificação e Rotulagem de Produtos Químicos)** — ONU ST/SG/AC.10/30/Rev.10 (10ª edição revisada, 2023) — e em sua implementação brasileira via **ABNT NBR 14725 (FISPQ)**.

## O que esta skill faz

| Tarefa | Exemplo de uso |
|---|---|
| **Elaborar FISPQ** | "Crie uma FISPQ completa para terebintina" |
| **Criar rótulo GHS** | "Quais pictogramas e frases H para colofônia Cat.1 sensibilizante?" |
| **Classificar substância/mistura** | "Classifique esta mistura: 70% breu + 30% nafta aromética" |
| **Consultar códigos H/P** | "Qual o texto exato do H317 em português?" |
| **Auditar documento** | "Audite esta FISPQ e aponte não conformidades" |
| **Ficha de transporte** | "Qual o número ONU e grupo de embalagem da terebintina?" |

## Quando a skill é acionada

Acione ao mencionar: `FISPQ`, `FDS`, `MSDS`, `SDS`, `ficha de segurança`, `fichas de transporte`, `rotulagem química`, `rótulo GHS`, `pictograma GHS`, `frases H`, `frases P`, `códigos H`, `códigos P`, `classificação de perigo`, `NBR 14725`, `ABNT NBR 14725`, `SGH`, `sistema globalmente harmonizado`, `auditoria FISPQ`, `conformidade GHS`, `número UN`, `número ONU`, `packing group`, `FISPQ breu`, `FISPQ terebintina`, `FISPQ colofônia`, `elaborar FISPQ`, `criar rótulo`, `validar rótulo`, `auditar documento`, `SGH Brasil`.

## Personas de uso — exemplos reais

### Técnico de segurança / responsável técnico
> "Preciso elaborar a FISPQ do nosso éster de pentaeritritol de breu para exportação para a Europa. Quais adaptações são necessárias em relação ao CLP europeu?"

> "Nossa FISPQ do aguarrás foi reprovada numa auditoria ISO 9001. Revise e aponte os problemas."

### Exportador de pine chemicals
> "Estamos exportando goma resina para a China. Qual o UN number, classe de transporte e grupo de embalagem correto para transporte marítimo (IMDG)?"

> "Preciso comparar os requisitos de rotulagem GHS do Brasil (NBR 14725) com os dos EUA (OSHA HazCom 2012) para o mesmo produto."

### Desenvolvedor de novos produtos
> "Formulamos um novo éster de breu com 85% colofônia modificada e 15% pentaeritritol residual. Como classificar e quais frases H aplicar?"

### Auditor de qualidade
> "Realize uma auditoria completa desta FISPQ [texto colado] contra o GHS Rev.10, identificando NCs críticas, maiores e observações."

## Produtos da cadeia pine chemicals cobertos

| Produto | CAS | Classificações típicas |
|---|---|---|
| Colofônia / Breu | 8050-09-7 | H317 (sensibiliz. cutânea); H412/H413 |
| Terebintina (espírito) | 8006-64-2 | H226, H304, H315, H317, H319, H336, H411 |
| Goma resina (bruta) | — | H226 (voláteis), H317 (ác. resinosos) |
| Ésteres de breu (PER/GLI) | variável | verificar sensibilização residual; Seção 9 |
| alpha-Pineno | 80-56-8 | H226, H304, H315, H317, H319, H336 |
| beta-Pineno | 127-91-3 | H226, H304, H315, H317, H319 |

## Estrutura da skill

```
ghs-fispq/
├── SKILL.md                        # Orchestrador principal
├── ghs-fispq.skill                 # Pacote instalável
└── references/
    ├── h-p-statements.md           # Todos os códigos H e P com textos exatos (PT-BR)
    ├── rotulagem-ghs.md            # 9 pictogramas, dimensionamento, regras de rótulo
    ├── sds-16-secoes.md            # Guia detalhado das 16 seções da FISPQ
    └── auditoria-checklist.md      # Checklist com 50+ pontos + modelo de relatório
```

## Base normativa

| Documento | Descrição |
|---|---|
| **GHS Rev.10** (ST/SG/AC.10/30/Rev.10, 2023) | Documento base — ONU |
| **ABNT NBR 14725** (Partes 1–4) | Implementação brasileira (FISPQ) |
| **NR-26** (MTE) | Sinalização de segurança em ambientes de trabalho |
| **NR-15** (MTE) | Atividades insalubres — limites de exposição |
| **Resolução ANTT 5.232/2016** | Transporte terrestre de produtos perigosos — Brasil |
| **IMDG Code** | Transporte marítimo de mercadorias perigosas |
| **ADR 2023** | Transporte rodoviário de mercadorias perigosas — Europa |
| **IATA DGR** | Transporte aéreo de mercadorias perigosas |
| **CONAMA / ABNT NBR 10004** | Classificação e descarte de resíduos — Brasil |

## Instalação

1. Baixe o arquivo `ghs-fispq.skill`
2. No Cowork, abra **Plugins → Install from file**
3. Selecione o arquivo `.skill`
4. A skill estará disponível imediatamente

## Desenvolvido por

**Leandro Pitol — RJ Comércio e Extração de Resinas Ltda.**  
Especialista em pine chemicals (goma resina, breu, terebintina e derivados).  
Baseado no manual oficial GHS Rev.10 da ONU (ST/SG/AC.10/30/Rev.10, 2023).

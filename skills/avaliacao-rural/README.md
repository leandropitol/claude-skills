# Avaliação de Imóveis Rurais

Skill especialista em **Engenharia de Avaliações Rurais** — co-piloto técnico para engenheiros avaliadores, peritos judiciais e analistas de risco de instituições financeiras. Fundamentada na **NBR 14653-3**, no **Atlas do Mercado de Terras INCRA 2025** e na **Resolução BACEN nº 4.676/2018**.

## O que esta skill faz

| Tarefa | Exemplo de uso |
|---|---|
| **Elaborar laudo de VTN** | "Avalie a terra nua de uma fazenda de 500 ha em Unaí/MG com aptidão agrícola regular" |
| **Calcular VTI pelo Método Evolutivo** | "Calcule o VTI com pastagem formada, sede e 2 açudes" |
| **Tratar amostra de mercado** | "Tenho 12 ofertas de R$/ha — aplique Box Plot e homogeneização" |
| **Consultar Atlas INCRA 2025** | "Qual o MRT e VTN de referência para soja em Lucas do Rio Verde/MT?" |
| **Consultar Planilha VTN 2025** | "Qual o VTN oficial do INCRA para pastagem no município X?" |
| **Análise LTV para crédito rural** | "Qual o valor máximo financiável com LTV de 60% para esta garantia?" |
| **Enquadramento grau NBR** | "Qual o grau de fundamentação e precisão desta avaliação?" |
| **Capitalização da Renda** | "Avalie um talhão de eucalipto de 8 anos com exploração autorizada" |

## Quando a skill é acionada

Acione ao mencionar: `laudo rural`, `fazenda`, `sítio`, `terra nua`, `VTN`, `VTI`, `benfeitoria rural`, `método comparativo de dados de mercado`, `método evolutivo`, `capitalização da renda`, `NBR 14653`, `avaliação rural`, `grau de fundamentação`, `homogeneização`, `Box Plot avaliação`, `Atlas INCRA`, `planilha VTN`, `CAR`, `reserva legal`, `APP`, `passivo ambiental`, `ativo ambiental`, `LTV rural`, `garantia rural`, `financiamento rural`, `laudo para banco`, `crédito rural`, `CREA`, `ART`, `perito avaliador`, `vistoria rural`, `pastagem`, `pecuária`, `lavoura`, `silvicultura`, `eucalipto`, `pinus`, `reflorestamento`, `arrendamento rural`, `capitalização de renda rural`, `mercado de terras`, `avaliação de fazenda`, `parecer técnico rural`, `LTV 60%`, `LTV 80%`.

## Personas de uso — exemplos reais

### Engenheiro Avaliador / Perito Judicial
> "Preciso elaborar um laudo de avaliação de fazenda de 320 ha em pecuária extensiva para processo de desapropriação. A região tem histórico de preço entre R$ 8.000 e R$ 15.000/ha."

> "Tenho 8 transações homogêneas coletadas em campo. Aplique tratamento estatístico e calcule o VTN com Box Plot."

### Analista de Crédito Rural / Banco
> "O banco precisa avaliar uma garantia real de 1.200 ha em soja para uma operação de R$ 4M. Qual o LTV máximo conforme BACEN 4.676?"

> "O laudo externo apresenta VTI de R$ 12M para 600 ha de cana. Faça uma análise crítica da metodologia adotada."

### Produtor Rural / Comprador
> "Estou comprando uma fazenda de 180 ha em Minas Gerais, parte pastagem e parte lavoura. Como estimar o valor justo antes de negociar?"

> "Quero arrendar um talhão de 50 ha de eucalipto para colheita em 2 anos. Como calcular o valor de arrendamento por capitalização da renda?"

### Auditor / Revisor de Laudos
> "Revise este laudo e verifique conformidade com a NBR 14653-3: grau de fundamentação, número de amostras, extrapolação e disclaimers obrigatórios."

## Fluxo de trabalho da skill

```
ENTRADA → Módulo 1 — Ingestão e Classificação
           (VTN / VTI / VBR / VBNR / AA / PA)
        ↓
        Módulo 2 — Motor Metodológico (Árvore de Decisão NBR 14653)
           MCDDM → Método Evolutivo → Capitalização da Renda
        ↓
        Módulo 3 — Motor Estatístico
           Box Plot → Regressão Linear Múltipla → Fatores de Homogeneização
        ↓
        Módulo 4 — Compliance NBR 14653-3
           Grau de Fundamentação (I / II / III) + Grau de Precisão
        ↓
SAÍDA → Módulo 5 — Laudo Completo
           Memória de cálculo + Campo de Arbítrio ± 15% + Disclaimer CREA/ART
```

## Estrutura da skill

```
avaliacao-rural/
├── SKILL.md                                                    # Orchestrador principal (5 módulos)
├── avaliacao-rural.skill                                       # Pacote instalável
└── references/
    ├── NBR 14653-5 - 2002 - Avaliação de Bens - Parte 1 - Procedimentos_GERAIS.md
    ├── NBR 14653-5 - 2002 - Avaliação de Bens - Parte 3 - Imoveis_rurais.md
    ├── NBR 14653-5 - 2002 - Avaliação de Bens - Parte 4 - Empreendimentos.md
    ├── NBR 14653-5 - 2002 - Avaliação de Bens - Parte 5 - Máquinas,.md
    ├── NBR 14653-6 - 2002 - Avaliação de Bens - Parte 6 - Recursos.md
    ├── RESOLUCAO_N4676_DE_31_DE_JULHO_DE_2018.md               # Critérios BACEN: LTV e garantias
    ├── Atlas_do_Mercado_de_Terras_2025.md                      # Inteligência de mercado regional
    ├── planilha-vtn-2025-para-publicacao-6.md                  # VTN oficial por município/aptidão
    └── palestra-Carlos-Augusto-Arantes-A-nova-norma-da-ABNT-para-imóveis-Rurais.md
```

## Base normativa

| Documento | Descrição |
|---|---|
| **ABNT NBR 14653-1** | Procedimentos gerais de avaliação de bens |
| **ABNT NBR 14653-3** | Regras específicas para imóveis rurais: classificação, métodos, homogeneização |
| **ABNT NBR 14653-4** | Avaliação de empreendimentos agropecuários e florestas |
| **ABNT NBR 14653-5** | Benfeitorias reprodutivas: máquinas, equipamentos, instalações |
| **ABNT NBR 14653-6** | Recursos naturais e ambientais; ativos e passivos ambientais |
| **Resolução BACEN nº 4.676/2018** | Critérios de garantias imobiliárias, LTV e amortização |
| **Atlas do Mercado de Terras 2025 (INCRA)** | VTN dinâmico regional para fins comerciais |
| **Planilha VTN 2025 (INCRA)** | VTN oficial por município e aptidão para ITR/documentação |

## Componentes de valor cobertos

| Componente | Sigla | Método de avaliação |
|---|---|---|
| Valor da Terra Nua | **VTN** | MCDDM (método prioritário) |
| Benfeitorias Reprodutivas | **VBR** | Custo de implantação com depreciação |
| Benfeitorias Não Reprodutivas | **VBNR** | CRN depreciado (Ross-Heidecke) |
| Ativo Ambiental | **AA** | Mercado ou renda (NBR 14653-6) |
| Passivo Ambiental | **PA** | Custo de recuperação ou desvalorização |
| **Valor Total do Imóvel** | **VTI** | VTN + VBR + VBNR + AA − PA |

## Instalação

1. Baixe o arquivo `avaliacao-rural.skill`
2. No Cowork, abra **Plugins → Install from file**
3. Selecione o arquivo `.skill`
4. Configure o caminho da pasta de trabalho: `AVALIACAO_TERRAS/`
5. A skill estará disponível imediatamente

## Desenvolvido por

**Leandro Pitol**  
Baseado na ABNT NBR 14653 (todas as partes relevantes), Atlas do Mercado de Terras INCRA 2025 e Resolução BACEN nº 4.676/2018.

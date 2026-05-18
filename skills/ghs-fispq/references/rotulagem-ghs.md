# Rotulagem GHS — Guia Completo

## Elementos obrigatórios do rótulo GHS

Um rótulo GHS completo deve conter **todos** estes elementos (quando aplicáveis):

1. **Identificador do produto** — nome químico ou comercial que conste na FISPQ
2. **Pictograma(s)** — losango com moldura vermelha, símbolo preto, fundo branco
3. **Palavra de advertência** — "PERIGO" ou "ATENÇÃO" (nunca ambos)
4. **Declarações de perigo** (frases H) — todas as aplicáveis
5. **Declarações de precaução** (frases P) — seleção baseada na classificação
6. **Informações do fornecedor** — nome, endereço completo, telefone
7. **Quantidade nominal** do produto
8. **Telefone de emergência**
9. **Número ONU e nome de embarque** (se produto sujeito a regulamentos de transporte)

---

## Os 9 Pictogramas GHS

| # | Nome | Código | Classes de Perigo |
|---|------|--------|-------------------|
| 1 | Chama | GHS01 | Explosivos (Div.1-3), Substâncias autorreativas Tipo A/B, Peróxidos orgânicos Tipo A/B |
| 2 | Chama sobre círculo | GHS02 | Líquidos/Gases/Sólidos inflamáveis, Aerossóis inflamáveis, Substâncias pirofóricas, Autorreativas C-F, Peróxidos orgânicos C-F, Gases químicos sob pressão inflamáveis, Sólidos de aquecimento próprio |
| 3 | Bomba explodindo | GHS03 | Explosivos (instáveis, Div.1, 2A), Autorreativas Tipo A/B, Peróxidos orgânicos Tipo A/B |
| 4 | Corrosão | GHS04 | Corrosão cutânea Cat.1, Lesões oculares graves Cat.1, Corrosivo para metais |
| 5 | Cilindro de gás | GHS05 | Gases sob pressão (comprimido, liquefeito, dissolvido, liquefeito refrigerado) |
| 6 | Caveira/ossos cruzados | GHS06 | Toxicidade aguda Cat.1-3 (oral, dérmica, inalação) |
| 7 | Ponto de exclamação | GHS07 | Toxicidade aguda Cat.4, Irritação cutânea Cat.2, Sensibilização cutânea Cat.1, Irritação ocular Cat.2, Toxicidade para órgão-alvo Cat.3 (STOT), Irritação das vias resp. Cat.3 |
| 8 | Ambiente | GHS08 | Perigo aquático agudo Cat.1, Perigo aquático crônico Cat.1/2 |
| 9 | Perigo para a saúde | GHS09 | Sensibilização respiratória, Mutagenicidade Cat.1/2, Carcinogenicidade Cat.1/2, Toxicidade reprodutiva Cat.1/2, STOT Cat.1/2, Perigo de aspiração Cat.1 |

> **Nota**: Quando dois pictogramas se aplicam ao mesmo perigo, pode haver hierarquia:
> - Se H314 (corrosão), dispensar H315/H319
> - Se caveira (H300/310/330), dispensar ponto de exclamação para o mesmo efeito tóxico
> - Se símbolo de saúde (H334), dispensar ponto de exclamação H335 para via inalatória

---

## Palavra de advertência — Regras de atribuição

**"PERIGO"** (categorias mais severas):
- Toxicidade aguda Cat. 1, 2, 3
- Corrosão cutânea Cat. 1, 1A, 1B, 1C
- Lesões oculares graves Cat. 1
- Sensibilização respiratória Cat. 1, 1A, 1B
- Mutagenicidade Cat. 1, 1A, 1B
- Carcinogenicidade Cat. 1, 1A, 1B
- Toxicidade reprodutiva Cat. 1, 1A, 1B
- STOT exposição única Cat. 1
- STOT exposição repetida Cat. 1
- Perigo de aspiração Cat. 1
- Perigo aquático agudo Cat. 1
- Perigo aquático crônico Cat. 1
- Explosivos Div. 1-4, 2A
- Líquidos inflamáveis Cat. 1, 2
- Gases inflamáveis Cat. 1A
- Oxidantes (liq./sól.) Cat. 1
- Gases sob pressão (todos)
- Peróxidos orgânicos Tipo A, B

**"ATENÇÃO"** (categorias menos severas):
- Todos os demais casos onde a palavra de advertência é requerida

**Quando "PERIGO" é atribuído, "ATENÇÃO" NÃO aparece no rótulo** — usar apenas a palavra de nível mais alto.

---

## Disposição dos elementos no rótulo

O GHS não exige layout fixo, mas recomenda agrupamento lógico:

```
┌─────────────────────────────────────┐
│ NOME DO PRODUTO                     │
│ [Identificador / Uso recomendado]   │
├─────────────────────────────────────┤
│ [Pictograma]  [Pictograma]          │
│                                     │
│ PERIGO / ATENÇÃO                    │
│                                     │
│ Declarações de perigo:              │
│ H226 Líquido e vapor inflamáveis.   │
│ H304 Pode ser fatal se ingerido...  │
│ H317 Pode provocar reação alérgica. │
│                                     │
│ Declarações de precaução:           │
│ P210 Manter afastado do calor...    │
│ P261 Evitar respirar vapores.       │
│ P301+P310 Em caso de ingestão:      │
│   contactar médico imediatamente.   │
├─────────────────────────────────────┤
│ FORNECEDOR:                         │
│ [Nome, endereço, telefone]          │
│ Tel. emergência: [número]           │
│ Quantidade: [XXX mL/kg]             │
└─────────────────────────────────────┘
```

---

## Dimensionamento do rótulo

O GHS define tamanho mínimo dos pictogramas em relação ao volume da embalagem:

| Volume da embalagem | Área mínima do pictograma |
|---------------------|--------------------------|
| ≤ 3 L | ≥ 1 cm² (10 × 10 mm) |
| 3 a 50 L | ≥ 2 cm² (14 × 14 mm) |
| 50 a 500 L | ≥ 4 cm² (20 × 20 mm) |
| > 500 L | ≥ 9 cm² (30 × 30 mm) |

---

## Pictogramas de transporte vs. GHS — diferenças importantes

| Característica | Pictograma GHS (local trabalho) | Pictograma de Transporte (UN) |
|---|---|---|
| Forma | Losango (quadrado na ponta) | Losango (quadrado na ponta) |
| Moldura | **Vermelha** | Sem moldura padrão (borda da própria forma colorida) |
| Fundo | **Branco** | **Colorido** (laranja, amarelo, etc.) |
| Tamanho mínimo | Proporcional à embalagem | **100 mm × 100 mm** |
| Número de classe | Não contém | Contém (canto inferior) |
| Norma | GHS, NBR 14725 | Regulamentos Modelo ONU, ADR, IMDG |

---

## Rótulo de local de trabalho (Workplace Label)

Para recipientes de trabalho (não originais, reembalagens internas), o GHS permite
rótulo simplificado contendo pelo menos:
- Identificação do produto
- Indicação dos perigos (pode ser por pictogramas ou palavras)
- Medidas de precaução relevantes
- Nome do fornecedor/responsável

---

## Ingredientes que devem aparecer no rótulo

Obrigatório declarar no rótulo quando presentes acima dos limiares:
- Substâncias CMR (carcinogênicas, mutagênicas ou tóxicas para reprodução) — Cat. 1A/1B
- Sensibilizantes respiratórios — Cat. 1, 1A, 1B
- STOT — Cat. 1 após exposição repetida

O nome do ingrediente no rótulo deve ser consistente com o nome na Seção 3 da FISPQ.

---

## Atualização do rótulo

- Atualizar **prontamente** quando nova informação disponível alterar a classificação
- Revisão periódica recomendada: **a cada 3 a 5 anos**
- Alterações significativas na composição de mistura requerem reavaliação imediata

---

## Lista de verificação — rótulo completo

- [ ] Identificador do produto presente e consistente com Seção 1 da FISPQ
- [ ] Todos os pictogramas aplicáveis incluídos (nenhum faltando, nenhum a mais)
- [ ] Palavra de advertência correta ("PERIGO" ou "ATENÇÃO", não ambas)
- [ ] Todas as frases H aplicáveis presentes, com texto exato normalizado
- [ ] Frases P adequadas à classificação e ao uso do produto
- [ ] Nome e endereço completo do fornecedor
- [ ] Telefone de emergência 24h
- [ ] Quantidade nominal do produto
- [ ] Se transporte: número ONU e nome de embarque
- [ ] Dimensões dos pictogramas adequadas ao volume da embalagem
- [ ] Idioma adequado à jurisdição de destino

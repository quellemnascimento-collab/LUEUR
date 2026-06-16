# Dossiê LUEUR Papelaria
### Documento executivo consolidado — visão de negócio, marca, operação e finanças

---

## Ficha da Empresa

| Campo | Informação |
|---|---|
| **Razão/Nome Fantasia** | Lueur — Papelaria e Ateliê |
| **CNPJ** | 65.723.134/0001-86 |
| **Setor** | Comércio varejista de papelaria de design (D2C + marketplaces) |
| **CNAE principal recomendado** | 47.61-0/03 — Comércio varejista de artigos de papelaria |
| **CNAE secundário recomendado** | 47.89-0/05 — Comércio varejista de outros produtos não especificados |
| **Conceito de marca** | "Cada um brilha na sua hora" — sistema de coleções "Fases da Luz" (Aurora, Golden Hour, Dusk, Night Glow) |
| **Posicionamento** | Premium acessível — entre a papelaria de massa (Kalunga/Tilibra) e o importado premium (Muji/Kokuyo) |
| **Ticket médio-alvo** | R$ 75 – R$ 110 |

> Status: CNPJ já constituído. Próximo passo imediato é confirmar regime tributário (MEI vs ME) com o contador —
> ver `ESTRUTURA_EMPRESARIAL.md`, seção 1.

---

## 1. Visão de Negócio (resumo)

LUEUR ocupa o espaço entre três zonas do mercado brasileiro de papelaria: a papelaria de massa (preço baixo, sem
identidade), a papelaria "kawaii" saturada, e o premium importado (caro, sem conexão local). A proposta de valor é
uma papelaria de autor com sistema de coleções emocionais ("Fases da Luz") e uma linha de assinatura tecnicamente
diferenciada — **Night Glow**, com tinta fosforescente que brilha no escuro.

Documento completo: `PLANO_DE_NEGOCIO_V2.md` (mercado, concorrentes, branding, marketplaces, eventos, fornecedores,
projeções financeiras em 3 cenários).

### Identidade Visual — Paleta Final

| Cor | Nome | Hex | Uso |
|---|---|---|---|
| Off-white rosado | Bruma | `#F2E9E4` | Fundo principal, embalagens |
| Verde-sálvia | Folha Suave | `#A9AD8E` | Acento natureza/sustentabilidade |
| Rosa-pó | Pó de Luz | `#E8D2D0` | Acentos suaves, coleção Aurora |
| Pêssego/salmão | Brilho Pêssego | `#F1C6B3` | Destaques de coleção, capas Aurora |
| Dourado-amadeirado | Âmbar | `#A4824A` | Detalhes premium, hot stamping |
| Marrom-chocolate | Terra Noturna | `#4A3624` | Tipografia/logo + base da linha Night Glow |

---

## 2. Estrutura da Empresa (resumo)

### 2.1 Setores

```
DIREÇÃO/FUNDAÇÃO
   ├── Produto & Estoque
   ├── Marketing & Digital
   ├── Comercial / Vendas (canais)
   ├── Operações & Logística
   └── Financeiro & Administrativo
```

### 2.2 Plano de pessoal (6 meses)

| Função | Quando contratar | Custo mensal estimado |
|---|---|---|
| Fundadora (pró-labore) | Já | R$ 2.000 – 3.500 |
| Auxiliar de Logística | Mês 3-4 (>15 pedidos/dia) | R$ 1.200 – 2.500 |
| Social Media/Atendimento | Mês 5-6 | R$ 1.200 – 2.000 |
| Designer (pontual) | Conforme necessidade | R$ 300 – 800/mês (médio) |
| Fotógrafo (pontual) | Mensal/bimestral | R$ 400 – 800/mês (médio) |
| Contador | Já | R$ 150 – 350 |

Documento completo: `ESTRUTURA_EMPRESARIAL.md` (burocracia, setores, critérios de decisão).

---

## 3. Orçamento e Projeções Financeiras (resumo)

### 3.1 Cenário base (bootstrap) — 6 meses

| Mês | Receita (R$) | Caixa líquido (R$) |
|---|---|---|
| 1 | 6.000 | (3.060) |
| 2 | 9.000 | (3.130) |
| 3 | 13.000 | (3.100) |
| 4 | 18.000 | (3.300) |
| 5 | 24.000 | (3.460) |
| 6 | 32.000 | (2.880) |

- **Capital de giro necessário (6 meses)**: ~R$ 18.900.
- **Capital total recomendado** (giro + investimento inicial de estoque/branding/site): **R$ 65.000 – R$ 90.000**.

### 3.2 Cenários alternativos (com aporte)

| Cenário | Faturamento Ano 1 estimado | Margem líquida Ano 1 | Retorno de aporte |
|---|---|---|---|
| Conservador (bootstrap) | R$ 350.000 – 450.000 | variável (foco em sobrevivência/crescimento) | n/a |
| Moderado (aporte R$100-150k) | R$ 600.000 – 750.000 | 15-25% | 18-24 meses |
| Agressivo (aporte R$350k) | R$ 850.000 – 1.000.000 | 15-20% (lucro ~R$130-200k) | 18-24 meses |

Detalhamento completo, premissas e uso de capital: `PLANO_DE_NEGOCIO_V2.md`, seção 8.

### 3.3 Planilhas de controle (uso diário)

- `planilhas/estoque.csv` — controle de SKU, custo, preço, quantidade, fornecedor, coleção/"fase da luz".
- `planilhas/fluxo_caixa_projecao.csv` — projeção mês a mês (espinha dorsal financeira dos 6 primeiros meses).
- `planilhas/fluxo_caixa_registro.csv` — registro real de entradas/saídas (preencher diariamente/semanalmente).

> Recomendação: abrir esses CSVs no Google Sheets/Excel e manter atualizados semanalmente. O `fluxo_caixa_registro.csv`
> deve ser comparado mensalmente com o `fluxo_caixa_projecao.csv` para identificar desvios e recalibrar decisões
> (ver critérios de decisão em `ESTRUTURA_EMPRESARIAL.md`, seção 5.3).

---

## 4. Canais de Venda — Priorização

| Fase | Canais |
|---|---|
| Meses 1-3 | Site próprio (Nuvemshop) + Shopee + Instagram/TikTok Shop |
| Meses 4-6 | + Mercado Livre + Elo7 |
| Meses 7+ (se operação estável) | + Magalu / Amazon BR / Americanas |

---

## 5. Roadmap — 12 Meses

| Fase | Meses | Marcos |
|---|---|---|
| Fundação | 1-2 | Confirmar regime tributário, registro de marca (INPI), identidade visual final, 1ª produção (Aurora + Night Glow), cadastro de fornecedores, site + Shopee + Instagram Shop |
| Lançamento | 3-4 | Campanha de lançamento, parcerias com microinfluenciadoras, cadastro Mercado Livre + Elo7, primeiros 100-300 clientes |
| Crescimento | 5-8 | Lançamento Golden Hour, expansão de catálogo, avaliação de migração de regime tributário, 1ª contratação (logística) |
| Escala | 9-12 | Avaliação de canais adicionais, participação em evento do setor (visita), avaliação de rodada de investimento com dados reais |

---

## 6. Índice de Documentos do Negócio

| Documento | Conteúdo |
|---|---|
| `PLANO_DE_NEGOCIO_V2.md` | Plano de negócio completo (mercado, concorrentes, branding, digital, marketplaces, eventos, fornecedores, projeções financeiras em 3 cenários) — **documento de referência principal** |
| `BRANDING.md` | História da marca, posicionamento, personas, identidade visual, estratégia de marketing |
| `REDES_SOCIAIS.md` | Setup de perfis, bios, calendário de conteúdo, banco de ideias (30 dias) e métricas |
| `PRODUTOS_VIRAIS_TIKTOK.md` | 22 produtos virais validados para TikTok Shop (papelaria + costura) com ângulo Lueur, ticket e estratégia de conteúdo |
| `ATELIE_PERSONALIZACAO.md` | Linha de personalização/encomendas (Ateliê) — produtos, operação, precificação, marketing e impacto financeiro |
| `LINHA_PAPELARIA_FINA.md` | Catálogo estratégico de papelaria fina (24 produtos, 5 eixos), benchmark Criare, tendências 2026 e programa de fidelidade |
| `moodboard.html` | Moodboard visual da identidade (paleta, tipografia, logo, direções de fotografia) |
| `ESTRUTURA_EMPRESARIAL.md` | Burocracia, setores, orçamento mensal detalhado, plano de contratação, checklist de decisões |
| `PLANO_DE_NEGOCIO.md` | Versão original do plano (mantida para histórico) |
| `planilhas/estoque.csv` | Controle de estoque |
| `planilhas/fluxo_caixa_projecao.csv` | Projeção financeira mês a mês |
| `planilhas/fluxo_caixa_registro.csv` | Registro real de fluxo de caixa |
| `DOSSIE_LUEUR.md` | Este documento — visão executiva consolidada |

---

## 7. Próximos Passos Imediatos

1. Confirmar regime tributário do CNPJ `65.723.134/0001-86` com contador (MEI ou ME) e CNAEs ativos.
2. Preencher `planilhas/estoque.csv` com o estoque atual real.
3. Iniciar registro de marca "LUEUR" no INPI em nome do CNPJ acima.
4. Definir as 2 primeiras "fases da luz" para o lançamento (recomendação: Aurora + Night Glow).
5. Configurar site (Nuvemshop) + Shopee + Instagram Shop.

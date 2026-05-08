# PROF2030 — O Profissional do Futuro: O Tripé do Nei Maldaner

**Data:** 2026-05-08
**Autor:** Nei Maldaner (visão e tripé)
**Formato:** Curso HTML INEMA.CLUB
**Status:** Design aprovado por Nei em 2026-05-08
**Repo:** https://github.com/inematds/prof2030
**Site:** https://inematds.github.io/prof2030/

## 1. Premissa

Curso baseado no **tripé** que Nei Maldaner ensina sobre o profissional do futuro:

1. **Comunicação com a Máquina** — saber dialogar com IA (prompt + context engineering)
2. **Empreender através da Automação** — gerar receita e alavancagem com IA + n8n
3. **Empatia e Comportamento Humano** — caráter como vantagem competitiva insubstituível

Conteúdo de Nei reforçado pela entrevista de **Jensen Huang** (Lex Fridman Podcast #494, mar/2026) e por autoridades externas (Karpathy, Naval, Goleman, Sam Altman, Pieter Levels, WEF Future of Jobs 2025).

## 2. Diferencial competitivo

5 cursos brasileiros concorrentes mapeados. **Todos pegam apenas UMA perna do tripé**. Este curso é o primeiro produto brasileiro a tratar as 3 dimensões como **sistema interdependente**.

## 3. Estrutura

**3 trilhas × 6 módulos = 18 módulos totais.** 6 tópicos por módulo = 108 tópicos.

Arco emocional comum: **Despertar → Fundamento → Prática → Aplicação → Síntese → Projeto**.

### Trilha 1 — Comunicar com a Máquina (Emerald)
- Gatilho: "Antes que a IA te substitua"
- Metáfora: "O tradutor do séc. XXI traduz intenção humana para linguagem de máquina."
- Epígrafe: Jensen — "A definição de programar hoje é simplesmente especificar."
- Módulos: Despertar (30M→1B) · Ferramenta vs. Propósito · Engenharia de Prompt · Engenharia de Contexto · Dialogar com Agentes · Projeto: Agente Pessoal

### Trilha 2 — Empreender pela Automação (Blue)
- Gatilho: "O profissional que o mundo vai pagar caro pra ter"
- Metáfora: "Você não precisa de um exército. Precisa de máquinas que trabalham enquanto você dorme."
- Epígrafe: Sam Altman — "A primeira empresa unicórnio de uma pessoa está chegando."
- Módulos: Despertar (alavancagem) · Solopreneur Real · n8n na Prática · Stack econômica · Precificar e vender · Projeto: Produto Automatizado

### Trilha 3 — Liderar com Humanidade (Purple)
- Gatilho: "Forme pessoas insubstituíveis"
- Metáfora: "Quando a inteligência vira commodity, o que sobra é você."
- Epígrafe: Jensen — "Caráter, humanidade, compaixão — esses são os poderes sobre-humanos."
- Módulos: Despertar (commodity) · 5 pilares de Goleman · Caráter como vantagem · Antecipação · Formar insubstituíveis · Projeto: Identidade

## 4. Tecnologia

- HTML estático no padrão **INEMA.CLUB**
- Tailwind CDN
- Inter font (Google Fonts)
- Dark/light mode com persistência via localStorage
- Mobile-first
- Hospedagem: GitHub Pages

## 5. Estrutura de arquivos

```
prof2030/
├── index.html                       # Landing
├── README.md
├── docs/superpowers/specs/          # Esta spec
├── pesquisa/                        # Relatório de fontes
└── curso/
    ├── trilha1/
    │   ├── index.html
    │   ├── modulo-1-1.html ... modulo-1-6.html
    ├── trilha2/
    │   ├── index.html
    │   ├── modulo-2-1.html ... modulo-2-6.html
    └── trilha3/
        ├── index.html
        └── modulo-3-1.html ... modulo-3-6.html
```

## 6. Gatilhos emocionais validados (BR)

- **Medo dominante:** 76% dos profissionais brasileiros temem ser substituídos por IA (Page/Exame).
- **Ambição dominante:** 63% querem renda > 6 SM em 5 anos; 33% querem empreender.
- **Responsabilidade dominante:** 44% querem garantir conforto futuro pros filhos.

Cada gatilho mapeia diretamente para uma das 3 trilhas (medo→T1, ambição→T2, responsabilidade→T3).

## 7. Fora do escopo (YAGNI)

- Vídeos gravados
- Sistema de login/progressão persistente
- Pagamento e gateway (curso entra no INEMA.VIP)
- Tradução pra outros idiomas
- App mobile nativo

# Desenvolvimento

## Modelo em Duas Camadas

```text
Escritório de Dados e IA
├── Camada 1 - Dados & Analytics
│   ├── Engenheiro de Dados
│   ├── Analista de Dados
│   └── Cientista de Dados
│
└── Camada 2 - Produtos & Orquestração com IA
    ├── AI Engineer
    ├── Engenheiro de Software
    └── Arquiteto de Soluções
```

### Camada 1 - Dados & Analytics

Estrutura e centraliza a inteligência corporativa com dados. Usa engenharia, analytics e ciência de dados para fornecer análises, indicadores, estudos e apoio à tomada de decisão data-driven.

**Perfis principais:**

- Engenheiro de Dados;
- Analista de Dados;
- Cientista de Dados.

### Camada 2 - Produtos & Orquestração com IA

Cria mecanismos de orquestração, agentes, automações e produtos com IA. O foco é acelerar entregas, reduzir trabalho manual e transformar protótipos em soluções corporativas governadas.

**Perfis principais:**

- AI Engineer;
- Engenheiro de Software;
- Arquiteto de Soluções.

## Estrutura TO BE

| Área | Perfil | Status |
| --- | --- | --- |
| Liderança | Head de Dados e IA | Ocupado |
| Dados & Analytics | Engenheiro de Dados | Ocupado |
| Dados & Analytics | Analista de Dados | Acumulado temporariamente |
| Dados & Analytics | Cientista de Dados | A contratar |
| Produtos & Orquestração com IA | AI Engineer | Ocupado |
| Produtos & Orquestração com IA | Engenheiro de Software | A contratar ou absorver da TI |
| Produtos & Orquestração com IA | Arquiteto de Soluções | A contratar ou absorver da TI |
| Transversal | Analista de Requisitos | Ocupado |

!!! warning "Gap operacional"
    O papel de Analista de Dados está temporariamente acumulado. Esse gap deve ser tratado conforme a demanda analítica crescer.

## Papéis e Responsabilidades

### Head de Dados e IA

Lidera a estratégia do escritório e garante entrega de valor mensurável para o Grupo CSC.

**Responsabilidades principais:**

- definir e gerir o roadmap de dados e IA;
- priorizar iniciativas por impacto de negócio;
- conduzir governança de dados e uso responsável de IA;
- fazer interface com diretorias e áreas de negócio;
- gerir sprints, rituais e métricas de fluxo;
- comunicar resultados à liderança.

### Engenheiro de Dados

Constrói a fundação técnica que torna dados acessíveis, confiáveis e utilizáveis.

**Responsabilidades principais:**

- construir pipelines de ingestão, transformação e disponibilização;
- consolidar dados de sistemas transacionais, ERPs, APIs e fontes internas;
- modelar e manter o Data Lake;
- monitorar qualidade de dados;
- manter catálogo, owners, glossário e documentação.

### Analista de Dados

Transforma dados estruturados em respostas claras para o negócio.

**Responsabilidades principais:**

- desenvolver dashboards, relatórios e indicadores;
- atender demandas analíticas recorrentes;
- executar análises exploratórias;
- traduzir dados em narrativas acionáveis;
- documentar métricas e definições de negócio.

### Cientista de Dados

Avança a capacidade analítica para previsão, otimização e modelos de risco.

**Responsabilidades principais:**

- desenvolver modelos preditivos e prescritivos;
- validar hipóteses com rigor estatístico;
- criar features para modelos e agentes;
- monitorar drift, acurácia e vieses;
- aplicar técnicas de machine learning a casos de uso relevantes.

### AI Engineer

Constrói sistemas RAG, agentes, integrações com LLMs e produtos funcionais de IA.

**Responsabilidades principais:**

- desenvolver soluções RAG sobre documentos e dados internos;
- construir agentes com acesso controlado a ferramentas e APIs;
- prototipar e validar soluções de IA generativa;
- avaliar modelos, frameworks e ferramentas;
- evoluir arquitetura, guardrails e observabilidade da Plataforma CSC de IA.

### Engenheiro de Software

Transforma protótipos e agentes em produtos robustos, escaláveis e mantidos.

**Responsabilidades principais:**

- desenvolver APIs, integrações e sistemas de apoio;
- aplicar CI/CD, testes e observabilidade;
- manter e evoluir produtos de software;
- integrar soluções com SAP, Google Workspace e ferramentas internas.

### Arquiteto de Soluções

Define padrões técnicos, integração, segurança e escalabilidade.

**Responsabilidades principais:**

- definir arquitetura de produtos e integrações;
- padronizar tecnologias e frameworks;
- revisar decisões de autenticação, autorização e segurança;
- avaliar make versus buy;
- documentar decisões arquiteturais.

### Analista de Requisitos

Garante que o trabalho técnico esteja conectado a problemas reais de negócio.

**Responsabilidades principais:**

- levantar, documentar e validar requisitos;
- organizar o processo de intake;
- traduzir necessidades em especificações claras;
- definir critérios de aceite;
- manter rastreabilidade entre demanda e entrega.

## Modelo Operacional

O escritório opera em ciclos de sprint de 2 semanas, em parceria com mentoria especializada.

| Ritual | Frequência | Objetivo |
| --- | --- | --- |
| Planejamento de sprint | A cada sprint | Priorizar demandas do backlog |
| Revisão de entrega | Final de cada sprint | Demonstrar resultados entregues |
| Retrospectiva | A cada 2 sprints | Melhorar processo, colaboração e fluxo |

## Fluxo de Demandas

```text
Áreas de negócio
└── Intake único
    └── Qualificação pelo Analista de Requisitos
        └── Priorização pelo Head
            └── Execução por Dados, IA ou Engenharia
                └── Registro em GitHub
                    └── Entrega, documentação e revisão
```

## Rastreabilidade

Todo o trabalho deve ser registrado e medido via GitHub:

- issues para demandas e critérios de aceite;
- pull requests para revisão e entrega;
- métricas de throughput e lead time;
- documentação técnica e estratégica em Markdown;
- histórico rastreável de decisões e entregas.

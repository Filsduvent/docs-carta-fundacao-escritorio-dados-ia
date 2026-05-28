# Diretrizes

## Princípios de Operação

1. Toda demanda deve entrar por um processo único de intake.
2. Toda iniciativa deve ter objetivo de negócio claro.
3. Toda entrega deve possuir responsável, critério de aceite e rastreabilidade.
4. Produtos de dados e IA devem ser documentados em Markdown.
5. Dados, agentes e automações devem operar com governança, controle de acesso e auditoria.
6. A evolução da plataforma deve ser incremental, priorizada por impacto e viabilidade.

## Padrões Obrigatórios

### Governança de Dados

- manter catálogo de dados, owners e glossário corporativo;
- documentar métricas e definições de negócio;
- monitorar qualidade, inconsistências e disponibilidade;
- observar requisitos de LGPD, segurança e conformidade.

### Governança de IA

- registrar produtos, agentes e automações relevantes;
- definir limites de autonomia dos agentes;
- controlar acesso a dados internos;
- manter logs, critérios de auditoria e revisão humana quando necessário;
- prevenir shadow AI por meio de padrões claros de criação e uso.

### Desenvolvimento de Produtos

- usar backlog priorizado por impacto e viabilidade;
- trabalhar em ciclos curtos de entrega;
- registrar demandas e decisões no GitHub;
- revisar entregas por pull request quando houver código ou documentação técnica;
- manter documentação viva junto ao repositório da solução.

## Checklist de Demanda

Antes de uma demanda entrar em execução, validar:

- [ ] problema de negócio descrito;
- [ ] área solicitante identificada;
- [ ] owner da demanda definido;
- [ ] objetivo e resultado esperado claros;
- [ ] dados ou sistemas necessários mapeados;
- [ ] riscos de dados, acesso ou LGPD avaliados;
- [ ] critérios de aceite documentados;
- [ ] prioridade definida pelo Head;
- [ ] capacidade do time confirmada.

## Boas Práticas

### Faça

- priorize entregas com impacto mensurável;
- comece com MVPs e evolua por ciclos;
- documente decisões enquanto a solução é construída;
- envolva TI em integrações, segurança e infraestrutura;
- comunique resultados em linguagem executiva.

### Evite

- iniciar produtos sem owner de negócio;
- criar agentes sem controle de acesso e auditoria;
- manter documentação em arquivos isolados e não rastreáveis;
- tratar IA generativa como experimento sem governança;
- acumular decisões técnicas fora do repositório.

## Critérios de Escalação

Escalar para liderança quando houver:

- acesso a dados sensíveis, pessoais ou confidenciais;
- impacto relevante em clientes, colaboradores ou decisões corporativas;
- dependência crítica de fornecedor;
- necessidade de contratação ou absorção de capacidade de engenharia;
- conflito de prioridade entre áreas;
- risco de segurança, compliance ou exposição reputacional.

!!! danger "Risco central"
    Sem governança integrada, iniciativas de dados e IA podem se fragmentar, criando shadow AI, baixa rastreabilidade, duplicidade de esforços e decisões sem evidência confiável.

# ProGirls Marketing Analytics

Plataforma de Analytics desenvolvida para apoiar a tomada de decisão da equipe de Marketing da comunidade ProGirls.

## Objetivos

- Automatizar coleta de dados
- Construir ETL com Python
- Centralizar métricas do Notion e redes sociais
- Criar dashboards em Power BI

- 

                ProGirls Marketing Analytics

                 ┌───────────────────────┐
                 │        Notion         │
                 └───────────┬───────────┘
                             │
                 ┌───────────▼───────────┐
                 │       Python ETL      │
                 └───────────┬───────────┘
                             │
          ┌──────────────────┼──────────────────┐
          │                  │                  │
          ▼                  ▼                  ▼
     Instagram CSV      LinkedIn CSV      Google Forms
          │                  │                  │
          └──────────────────┴──────────────────┘
                             │
                 ┌───────────▼───────────┐
                 │     Banco de Dados    │
                 └───────────┬───────────┘
                             │
                 ┌───────────▼───────────┐
                 │     Power BI / BI     │
                 └───────────────────────┘

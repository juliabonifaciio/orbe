# Diagrama do Processo — ORBE

## 1. Processo anterior à automação

```mermaid
flowchart TD
    A[Paramédico identifica uma ocorrência] --> B[Envia informações por e-mail]
    B --> C[Responsável recebe a solicitação]
    C --> D[Analisa manualmente as informações]
    D --> E[Organiza os dados]
    E --> F[Regista a ocorrência manualmente]
    F --> G[Encaminha para a equipa responsável]
```

## 2. Processo com o ORBE

```mermaid
flowchart TD
    A[Paramédico envia solicitação] --> B[Outlook recebe e-mail]
    B --> C{Existe anexo?}
    C -->|Sim| D[ORBE extrai dados do CSV ou Excel]
    C -->|Não| E[ORBE utiliza o texto do e-mail]
    D --> F[IA interpreta e estrutura os dados]
    E --> F
    F --> G[Gera protocolo e organiza informações]
    G --> H[Regista ocorrência no Excel]
    H --> I[Envia notificação por e-mail]
    I --> J[Equipa humana responsável recebe os dados]
```

## 3. Resultado da automação

- Automatização do recebimento das solicitações.
- Interpretação dos dados com Inteligência Artificial.
- Padronização dos registos operacionais.
- Geração automática de protocolos.
- Centralização das informações no Excel.
- Notificação automática da equipa responsável.

**Nota:** O ORBE apoia a organização e o encaminhamento operacional, sem substituir a avaliação dos profissionais.

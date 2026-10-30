# ORBE — Agente Inteligente de Apoio Operacional

## Sobre o projeto

O ORBE é um agente inteligente desenvolvido para apoiar a comunicação e a organização de solicitações operacionais em ambientes rodoviários.

A solução utiliza Inteligência Artificial para interpretar informações recebidas por e-mail e ficheiros, estruturar os dados das ocorrências e encaminhá-los para as equipas responsáveis.

## Objetivo

Automatizar o processo de recebimento, interpretação, registo e encaminhamento de solicitações operacionais, reduzindo tarefas manuais e facilitando o acesso às informações.

## Tecnologias utilizadas

- **n8n Cloud:** criação e automação dos fluxos de trabalho.
- **OpenAI:** interpretação e classificação das solicitações.
- **Microsoft Outlook:** recebimento e envio de e-mails.
- **Microsoft Excel / OneDrive:** armazenamento dos registos operacionais.
- **Webhook:** ponto de integração para futuras funcionalidades e agentes de voz.

## Funcionamento

O fluxo operacional segue as seguintes etapas:

1. Recebimento de solicitações por e-mail.
2. Identificação e leitura de ficheiros CSV e Excel anexados.
3. Interpretação das informações através de Inteligência Artificial.
4. Extração e organização dos dados da ocorrência.
5. Identificação de informações pendentes.
6. Geração de um protocolo de atendimento.
7. Registo automático das informações no Excel.
8. Envio de uma notificação por e-mail à equipa responsável.

## Dados estruturados

O ORBE organiza informações como:

- Rodovia e quilómetro.
- Sentido da via.
- Tipo de ocorrência.
- Quantidade de veículos envolvidos.
- Quantidade de vítimas.
- Informações relatadas.
- Apoio solicitado.
- Informações pendentes.
- Encaminhamento sugerido.
- Protocolo e estado do registo.

## Segurança e limites de atuação

O ORBE funciona como uma ferramenta de apoio operacional. Não realiza diagnósticos médicos, não prescreve tratamentos e não determina prioridades clínicas.

As informações são organizadas para apoiar a equipa humana responsável, sem substituir a avaliação dos profissionais.

## Estado do projeto

**MVP funcional — Sprint 1**

As funcionalidades de recebimento por e-mail, interpretação com IA, leitura de CSV e Excel, registo automático e envio de notificações foram implementadas e testadas.

## Próximas evoluções

- Integração com agente de voz.
- Expansão dos mecanismos de encaminhamento.
- Aprimoramento da validação das informações recebidas.
- Evolução da plataforma de apoio operacional.

### 1. Amazon Web Services (AWS)

- **Nível de Disponibilidade Garantida:**
  - **AWS IoT Core:** 99.9% de disponibilidade mensal.
  - **AWS Greengrass:** 99.9% de disponibilidade para execução de computação na borda.
  - **AWS SiteWise:** 99.9% de disponibilidade para coleta, organização e análise de dados de equipamentos industriais.
  - **Amazon EC2 (Elastic Compute Cloud):** 99.99% para instâncias distribuídas em múltiplas Zonas de Disponibilidade (AZs).

- **Exclusões dos SLAs:**
  - **Manutenção programada:** Não conta para a disponibilidade.
  - **Eventos de força maior:** Catástrofes naturais e outros eventos fora do controle da AWS não são cobertos.
  - **Falhas de terceiros:** Incluindo problemas de ISPs e outros fornecedores de serviços externos.

- **Créditos de Serviço:**
  - **Até 10% de crédito:** Para disponibilidade entre 99% e 99.9%.
  - **Até 25% de crédito:** Para disponibilidade inferior a 99%.
  - **Procedimento:** Requer submissão de um ticket de suporte em até 30 dias após o evento de indisponibilidade.

- **Serviços Específicos para Aplicações IIoT:**
  - **AWS IoT Core:** Para conectividade de dispositivos e gerenciamento de dados IoT.
  - **AWS Greengrass:** Permite executar funções Lambda localmente para resposta em tempo real e menor latência.
  - **AWS SiteWise:** Conectividade com equipamentos industriais para monitoramento e manutenção preditiva.

- **Políticas Regionais:**
  - Diferentes SLAs podem ser aplicados dependendo da região geográfica, especialmente para serviços como EC2 e SiteWise.

- **Níveis de Suporte:**
  - **Básico:** Sem SLA de suporte.
  - **Developer:** Tempo de resposta até 12 horas.
  - **Business:** Tempo de resposta até 1 hora.
  - **Enterprise:** Tempo de resposta até 15 minutos.



## Referências:
https://aws.amazon.com/lambda/sla/
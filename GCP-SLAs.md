### Google Cloud Platform (GCP)

- **Nível de Disponibilidade Garantida:**
  - **Google Cloud IoT Core:** 99.9% de disponibilidade mensal.
  - **Google Cloud IoT Edge:** 99.9% de disponibilidade para gerenciamento de dispositivos e execução de tarefas na borda.
  - **Google Cloud Bigtable:** 99.9% de disponibilidade para gerenciamento de grandes volumes de dados gerados por dispositivos IIoT.
  - **Google Compute Engine (Virtual Machines):** 99.99% para VMs em múltiplas zonas.

- **Exclusões dos SLAs:**
  - **Manutenção planejada:** Não conta para o cálculo de disponibilidade.
  - **Desastres naturais e eventos externos:** Não cobertos.
  - **Problemas relacionados a aplicações do cliente:** Não são considerados para crédito de SLA.

- **Créditos de Serviço:**
  - **Até 10% de crédito:** Para disponibilidade abaixo de 99.9% mas acima de 99.0%.
  - **Até 50% de crédito:** Para disponibilidade abaixo de 95%.
  - **Procedimento:** Necessário abrir uma solicitação de crédito em até 30 dias após o incidente.

- **Serviços Específicos para Aplicações IIoT:**
  - **Google Cloud IoT Core:** Para gerenciar dispositivos e coleta de dados.
  - **Google Cloud IoT Edge:** Executa processamento na borda para reduzir latência.
  - **Google Cloud Bigtable:** Para armazenar e processar grandes volumes de dados gerados por sensores e dispositivos industriais.

- **Políticas Regionais:**
  - SLAs específicos podem variar conforme a região, particularmente para serviços de armazenamento e computação.

- **Níveis de Suporte:**
  - **Basic Support:** Sem garantia de SLA.
  - **Standard Support:** Respostas em até 4 horas.
  - **Enhanced Support:** Respostas em até 1 hora.
  - **Premium Support:** Respostas em até 15 minutos.

## Referências
https://cloud.google.com/terms/sla
# Monitoramento com AWS CloudWatch e CloudTrail

![AWS Monitoring](https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg)

## 📌 Descrição do Projeto

Este repositório documenta as etapas e configurações realizadas no **Lab 7**, onde exploramos o monitoramento de recursos na AWS utilizando **Amazon CloudWatch** e **AWS CloudTrail**.

O objetivo do projeto é implementar uma solução de monitoramento eficaz, garantindo visibilidade sobre o desempenho, logs e eventos de segurança dos serviços AWS.

## 📋 O que foi feito

### 🔹 Configuração do CloudWatch
- Criação e personalização de **métricas** para monitoramento.
- Implementação de **CloudWatch Logs** para armazenar eventos relevantes.
- Configuração de **alarmes no CloudWatch** para alertas automáticos.

### 🔹 Monitoramento com CloudTrail
- **Ativação do AWS CloudTrail** para capturar eventos e auditoria de ações.
- **Criação de um bucket S3** para armazenar logs do CloudTrail.
- **Análise e filtro de eventos** para detectar atividades suspeitas.

### 🔹 Integração e Notificações
- **Criação de uma função Lambda** para processar logs automaticamente.
- **Configuração de alertas via Amazon SNS** para notificação em tempo real.
- **Dashboards no CloudWatch** para visualização rápida dos dados.

## 🚀 Como Utilizar

### 📥 1. Clonar este repositório
```bash
git clone https://github.com/gabrielsilva798/Lab-7-CloudWatch-e-CloudTrail.-.git
```

### ⚙️ 2. Configurar AWS CLI
Caso ainda não tenha a AWS CLI instalada, siga as instruções [neste link](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

Autentique sua conta:
```bash
aws configure
```
Informe:
- AWS Access Key ID
- AWS Secret Access Key
- Região Padrão
- Formato de Saída

### 📊 3. Acessar Monitoramento
- **CloudWatch**: Acesse [CloudWatch Console](https://console.aws.amazon.com/cloudwatch/) e visualize métricas, logs e alarmes.
- **CloudTrail**: Acesse [CloudTrail Console](https://console.aws.amazon.com/cloudtrail/) para conferir eventos e auditoria de acessos.

## 🛠 Tecnologias Utilizadas

| Tecnologia      | Descrição |
|---------------|-------------|
| **AWS CloudWatch** | Monitoramento e coleta de métricas |
| **AWS CloudTrail** | Registro e auditoria de eventos |
| **AWS Lambda** | Execução de código sem servidor |
| **Amazon S3** | Armazenamento de logs |
| **Amazon SNS** | Envio de notificações |

## 👀 Participe

Caso tenha dúvidas ou sugestões, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**. 

---

🔍 *Este README foi elaborado para documentar todas as configurações realizadas no lab e auxiliar outros desenvolvedores na implementação de soluções semelhantes.* 🚀



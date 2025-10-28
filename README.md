# AWS-CodeGirls-Desafio-3 


## 🚀 AWS Step Functions 

### 📌 Visão Geral  
Este repositório reúne a documentação do laboratório realizado no Bootcamp da Digital Innovation One (DIO), com foco na criação de **workflows automatizados** utilizando o serviço **AWS Step Functions**.

A ideia é registrar aprendizados, anotações e boas práticas adquiridas durante a execução do desafio, servindo como referência para estudos futuros e aplicações reais.

Cada etapa 
### 📖 O que é AWS Step Functions?  
O **AWS Step Functions** é um serviço que permite **orquestrar diferentes serviços da AWS** em fluxos de trabalho **serverless**, tornando a automação mais simples e eficiente.

De acordo com a AWS, ele oferece:  
- **Integração entre serviços**: conecta Lambda, S3, DynamoDB, SNS, ECS e outros.  
- **Monitoramento em tempo real**: acompanhamento via console e CloudWatch.  
- **Confiabilidade**: suporte a tentativas automáticas, tratamento de erros e execução paralela.  
- **Escalabilidade**: projetado para lidar com milhares de execuções simultâneas.  

---

### 🎯 Objetivos do Desafio  
Ao concluir este laboratório, você será capaz de:  
✔ Aplicar conceitos de automação em um ambiente prático;  
✔ Documentar processos técnicos de forma clara;  
✔ Utilizar o GitHub para compartilhar conhecimento técnico.  

---

### 🔧 Serviços Utilizados  
- **Amazon S3** – armazenamento de dados  
- **AWS Lambda** – execução de funções serverless  
- **AWS Step Functions** – orquestração do fluxo  
- **Amazon SNS** – envio de notificações  
- **(Opcional) DynamoDB** – armazenamento estruturado  

---

### ▶️ Como Testar o Workflow  
1. Criar um bucket no S3 para armazenar os dados.  
2. Implementar uma função Lambda para processar os arquivos.  
3. Configurar o Step Functions com os estados do fluxo.  
4. Definir destino para os resultados (outro bucket ou banco).  
5. Configurar SNS para enviar alertas ao final do processo.  

---

### 🚀 Benefícios do Step Functions  
- **Escalabilidade**: suporta múltiplas execuções simultâneas.  
- **Baixo acoplamento**: cada etapa é independente.  
- **Monitoramento**: integração com CloudWatch.  
- **Resiliência**: tolerância a falhas e mecanismos de retry.





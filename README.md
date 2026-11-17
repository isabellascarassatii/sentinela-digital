# 🛡️ Sentinela Digital

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green)
![Docker](https://img.shields.io/badge/Docker-Containers-blue)
![Uptime Kuma](https://img.shields.io/badge/Uptime%20Kuma-Monitoramento-success)
![Telegram](https://img.shields.io/badge/Telegram-Alertas-informational)

> **Projeto Integrador de DevOps** – Monitoramento proativo e infraestrutura como código (IaC) desenvolvido para garantir a alta disponibilidade digital do provedor de internet **OPS Telecom**.

## 📖 Sobre o Projeto
O **Sentinela Digital** é um sistema de monitoramento contínuo (uptime) desenvolvido como projeto de extensão universitária (Universidade de Sorocaba - UNISO). A aplicação realiza auditorias externas constantes no site institucional da empresa parceira, identificando instabilidades de infraestrutura (downtime) e enviando alertas imediatos para a equipe técnica. 

O projeto substitui o monitoramento reativo tradicional por uma abordagem proativa e automatizada, atendendo diretamente a dois **Objetivos de Desenvolvimento Sustentável (ODS)** da ONU:
- 🏗️ **ODS 9 (Indústria, Inovação e Infraestrutura):** Fomento de tecnologias modernas (DevOps e Containers) para a resiliência da infraestrutura digital de negócios locais.
- ♻️ **ODS 12 (Consumo e Produção Responsáveis):** Otimização de recursos operacionais através de ferramentas *open-source* e fomento à continuidade do atendimento digital (garantindo o autoatendimento para emissão de faturas online, reduzindo o uso de papel).

## 🎯 Funcionalidades
- 🐳 **Infraestrutura como Código (IaC):** Servidor 100% orquestrado em contêiner Docker, isolado da hospedagem original do cliente.
- ⏱️ **Health Checks Automatizados:** Auditoria de rotina a cada 5 minutos validando o retorno HTTP (Status 200 OK).
- 📱 **Notificações Push Instantâneas:** Integração com a API do Telegram (via Webhooks) alertando imediatamente sobre quedas (*Timeout* ou Erro 500) e recuperações.
- 📊 **Observabilidade:** Painéis visuais para a gestão do Tempo Médio de Descoberta (MTTD) e do tempo de resposta do servidor.

## 🛠️ Tecnologias Utilizadas
- **[Docker e Docker Compose]** - Orquestração e virtualização do ambiente.
- **[Uptime Kuma]** - Plataforma *open-source* de monitoramento de serviços.
- **[Telegram Bot API]** - Mensageria para alertas automatizados em tempo real.
- **[Git e GitHub]** - Versionamento de código e repositório central.

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Servidor local ou em nuvem com **Docker** e **Docker Compose** instalados.
- Bot criado no Telegram através do `@BotFather` (necessário o Token da API e o ID do grupo de alertas).

### Instalação (Passo a Passo)

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/isabellascarassatii/sentinela-digital.git](https://github.com/isabellascarassatii/sentinela-digital.git)

# 🏗️ Construindo Arquiteturas no Azure

## 📄 Descrição

Este repositório documenta o processo realizado durante o laboratório de **Construção de Arquiteturas no Azure**, como parte da trilha de aprendizagem da **DIO - Digital Innovation One**. O objetivo foi criar uma arquitetura na nuvem utilizando recursos fundamentais da plataforma Azure, garantindo escalabilidade, segurança e disponibilidade.

---

## 🚀 Passo a Passo Executado

### 1️⃣ Criação do Grupo de Recursos
- ✅ Acesse o portal [Azure](https://portal.azure.com).
- ✅ Crie um **Grupo de Recursos** para organizar os serviços.

### 2️⃣ Configuração da Rede Virtual (VNet)
- ✅ Criação de uma **VNet (Virtual Network)**.
- ✅ Definição de sub-redes para segmentar serviços (ex.: front-end, banco de dados).

### 3️⃣ Provisionamento das Máquinas Virtuais
- ✅ Criação de VMs para servidores de aplicação e banco de dados.
- ✅ Configuração de regras de segurança (NSG) para controle de tráfego (SSH, RDP, HTTP/HTTPS).

### 4️⃣ Configuração do Balanceador de Carga (Load Balancer)
- ✅ Implementação de um **Load Balancer Público** para distribuir requisições entre múltiplas VMs.
- ✅ Criação de regras de balanceamento para portas HTTP (80) e HTTPS (443).

### 5️⃣ Implementação de Banco de Dados
- ✅ Criação de um **Azure SQL Database** ou **VM com SQL Server** conforme necessidade do projeto.
- ✅ Configuração de regras de acesso seguras.

### 6️⃣ Alta Disponibilidade e Escalabilidade
- ✅ Configuração de **Scale Sets** para escalar horizontalmente as VMs.
- ✅ Definição de critérios de escalonamento (CPU, memória, etc.).

### 7️⃣ Monitoramento e Logs
- ✅ Ativação do **Azure Monitor** e **Log Analytics** para acompanhar desempenho, alertas e logs dos recursos.

---

## 🔗 Links Úteis

- 🏢 [Portal Azure](https://portal.azure.com)
- 📑 [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- 🛠️ [Azure Architecture Center](https://learn.microsoft.com/pt-br/azure/architecture/)
- 📘 [Documentação do Load Balancer Azure](https://learn.microsoft.com/pt-br/azure/load-balancer/load-balancer-overview)
- 📗 [Documentação de Virtual Network (VNet)](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-overview)
- 📙 [Documentação de Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/database/sql-database-overview)

---

## 🧠 Aprendizados

Neste projeto, aprendi como estruturar uma arquitetura escalável, segura e de alta disponibilidade na nuvem Microsoft Azure. A construção incluiu o uso de redes virtuais, balanceadores de carga, máquinas virtuais, bancos de dados e ferramentas de monitoramento, aplicando boas práticas de cloud computing.

---

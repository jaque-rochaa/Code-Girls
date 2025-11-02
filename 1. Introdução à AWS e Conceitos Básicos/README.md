# Módulo 1: Introdução à AWS e Conceitos Básicos*

**Visão Geral**

**O que é AWS?**
A Amazon Web Services (AWS) é a plataforma de computação em nuvem mais completa e amplamente adotada do mundo, oferecendo mais de 200 serviços de data centers em todo o globo.

# Infraestrutura Global

 **Estrutura de Distribuição**
 
  33 Regiões Geográficas:
  
    ─ 4 Novas Regiões em expansão)          
    ─ 105 Zonas de Disponibilidade 
       ─ Múltiplos Data Centers    
       ─ Alta Redundância          

**Regions (Regiões)**

**O que é?**

Áreas geográficas independentes que contêm múltiplas Availability Zones.

**Características:**

- Isolamento geográfico entre regiões
- Recursos exclusivos de cada região
- Replicação entre regiões é opcional (não automática)
- Latência mínima global: < 10ms

**Critérios para Escolher:**

- Compliance regulatório
- Disponibilidade de serviços
- Custo operacional
- Proximidade dos usuários finais

**Availability Zones (Zonas de Disponibilidade)**

**O que é?**
- Data centers independentes fisicamente, mas conectados logicamente para garantir alta disponibilidade.

**Características:**
- Mínimo de 2 zonas por região
- Isolamento de falhas entre zonas
- Conectividade redundante
- Suporte para aplicações resilientes

# Modelo de Negócio

**Pagamento por Uso**

A AWS utiliza um modelo de OPEX (Operational Expenditure) onde você paga apenas pelos recursos consumidos.

**Comparação: OPEX vs CAPEX**

<img width="614" height="266" alt="image" src="https://github.com/user-attachments/assets/68b95c8d-66b6-4df7-9685-75fe093e17c6" />

**Vantagens do Modelo AWS**

**Precificação Flexível:**
- Pague apenas o que usar
- Sem contratos de longo prazo obrigatórios
- Escalabilidade sob demanda

**Acessibilidade:**
- Democratiza acesso à infraestrutura de nível empresarial
- Ideal para startups e empresas consolidadas
- Reduz barreira de entrada

**Inovação Contínua:**
- Novos serviços regularmente
- Atualização constante de tecnologias
- Adaptação às necessidades do mercado

# Modelos de Computação

**Responsabilidade Compartilhada**

SaaS (Software as a Service)
- Você: Usa
- AWS: Tudo  

 PaaS (Platform as a Service)
 - Você: Aplicações + Dados
 - AWS: Runtime, Middleware, SO, Infra
   
IaaS (Infrastructure as Service)  
 - Você: Apps, Dados, Runtime, Middleware
 - AWS: SO, Virtualização, Servidores  

**Detalhamento dos Modelos**

**IaaS - Infrastructure as a Service**

**Responsabilidade do Cliente:**
- Aplicações
- Dados
- Runtime
- Middleware
- Sistema Operacional
  
**Responsabilidade da AWS:**
- Virtualização
- Servidores
- Armazenamento
- Networking

**PaaS - Platform as a Service**

**Responsabilidade do Cliente:**
- Aplicações
- Dados

  **Responsabilidade da AWS:**
  - Runtime, Middleware, SO
  - Virtualização, Servidores, Storage
 
  **SaaS - Software as a Service**

  **Responsabilidade do Cliente**
  - Usar a aplicação

 **Responsabilidade da AWS:**
 - Gerenciar tudo

# Resumo

**Pontos-Chave**

1. AWS é o maior Cloud Provider com infraestrutura global em 33 regiões e 105 zonas de disponibilidade
2. Modelo de negócio baseado em OPEX - pague apenas pelo que usar
3. Infraestrutura distribuída garante alta disponibilidade e baixa latência
4. Responsabilidade compartilhada entre AWS e cliente varia conforme o modelo (IaaS, PaaS, SaaS)
5. Mais de 200 serviços cobrindo computação, armazenamento, segurança, IoT e muito mais
6. Segurança é responsabilidade compartilhada - comeãr protegendo sua conta root e implementando MFA
  

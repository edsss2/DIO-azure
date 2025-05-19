# DIO-azure

## Azure SQL Database

**Azure SQL Database** é um serviço PaaS totalmente gerenciado que abstrai a administração de infraestrutura (patching, backups, alta disponibilidade, tuning), permitindo que você foque na aplicação em vez da gestão do servidor :contentReference[oaicite:0]{index=0}.

### 1. Provisionamento
- **Resource Group**: agrupa logicamente seus recursos e define limites de custo e acesso.  
- **Servidor Lógico**: ponto administrativo central para múltiplos bancos; gerencia logins, firewall e políticas de segurança :contentReference[oaicite:1]{index=1}.  
- **Banco de Dados**: crie uma instância única, um *elastic pool* (recursos compartilhados) ou *Managed Instance* (compatibilidade total com on-prem) conforme o cenário :contentReference[oaicite:2]{index=2}.

### 2. Configuração de Performance
- **Tier de Computação**: escolha entre DTU, vCore ou Serverless para equilibrar custo vs. performance.  
- **Armazenamento**: defina capacidade inicial e configure crescimento automático conforme o workload.

### 3. Segurança & Conectividade
- **Firewall**: regras de IP bloqueiam conexões por padrão; adicione regras de rede ou habilite “Allow Azure services” para acesso de aplicativos e ferramentas :contentReference[oaicite:3]{index=3}.  
- **Autenticação**: suporte a SQL Authentication (login/senha) e Azure AD Authentication com RBAC e roles internos (db_owner, dbmanager etc.) :contentReference[oaicite:4]{index=4}.

### 4. Escalabilidade & Monitoramento
- **Auto-scale**: ajuste dinámico de vCores/DTUs via portal, CLI ou API.  
- **Métricas & Logs**: use Azure Monitor para métricas em tempo real, alertas e logs de auditoria.  
- **Backups & PITR**: backups automáticos com Point-In-Time Restore para recuperação de dados.  
- **SLA 99,99 %**: disponibilidade garantida, com créditos em caso de não conformidade :contentReference[oaicite:5]{index=5}.

---
> **Dica:** personalize limites de recursos e níveis de serviço conforme seu perfil de uso e orçamento.

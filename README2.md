## Arquitetura no Microsoft Azure

Projetar soluções no Azure envolve combinar boas práticas de nuvem com os serviços gerenciados da plataforma para garantir escalabilidade, segurança e governança.

### 🔷 Princípios Fundamentais (Well-Architected Framework)
- **Confiabilidade**: alta disponibilidade e recuperação de falhas.
- **Segurança**: controle de acesso, rede protegida e identidade como perímetro.
- **Desempenho**: escalabilidade automática e uso eficiente de recursos.
- **Custo**: otimização por uso, escalonamento e monitoramento de consumo.
- **Operacional**: automação, monitoramento e resposta a incidentes.

### 🧱 Organização e Governança
- **Resource Groups & Subscriptions**: agrupamento lógico de recursos.
- **Landing Zones**: estrutura inicial padronizada com rede, identidade e políticas.
- **RBAC & Azure Policy**: controle de acesso e conformidade em escala.

### 🌐 Rede e Segurança
- **VNet e Subnets**: segmentação lógica com regras de NSG.
- **Hub-Spoke**: topologia recomendada para grandes ambientes.
- **Firewall, DDoS e Defender**: segurança multicamada nativa.

### 🔄 Automação e Monitoramento
- **IaC (ARM, Bicep, Terraform)**: infraestrutura como código.
- **CI/CD (DevOps ou GitHub Actions)**: deploy contínuo.
- **Azure Monitor & Logs**: métricas, alertas e dashboards operacionais.

> **Dica:** use os aceleradores da Microsoft (Landing Zones) para iniciar com uma base segura, escalável e alinhada às boas práticas.

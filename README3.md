## Configuração e Dimensionamento de Máquinas Virtuais no Azure

### 🧩 Escolha da Série de VM
- **Uso geral**: Séries D, B – equilibram CPU e memória para workloads comuns.
- **Otimizada para memória**: Séries E, M – ideais para bancos de dados e aplicações com uso intensivo de RAM.
- **Otimizada para computação**: Série F – adequada para cargas de trabalho com alta demanda de CPU.
- **GPU**: Séries NC, ND, NV – recomendadas para IA, renderização e simulações gráficas.

### 📐 Dimensionamento por Perfil de Usuário
- **Usuário leve**: 2 vCPUs, 8 GB RAM – tarefas básicas e navegação web.
- **Usuário médio**: 4 vCPUs, 16 GB RAM – aplicações de escritório e multitarefa moderada.
- **Usuário pesado**: 8 vCPUs, 32 GB RAM – desenvolvimento, design gráfico e análise de dados.

### 🛠️ Boas Práticas de Configuração
- **Discos Gerenciados**: Utilize discos gerenciados para maior desempenho e confiabilidade.
- **Redes Virtuais (VNet)**: Configure VNets e Subnets para isolamento e segurança.
- **Grupos de Segurança de Rede (NSG)**: Controle o tráfego de rede com regras de segurança.
- **Monitoramento**: Implemente o Azure Monitor para insights de desempenho e alertas proativos.

### 💡 Dicas de Otimização
- **Dimensionamento Correto**: Evite superdimensionamento para reduzir custos; ajuste conforme a demanda.
- **Escalabilidade**: Considere conjuntos de dimensionamento de máquinas virtuais (VMSS) para cargas de trabalho variáveis.
- **Automação**: Use scripts e ferramentas de automação para implantações consistentes e eficientes.


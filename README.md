# resumo-do-lab

# Localizando Serviços por Categoria
 Localizando Serviços por Categoria no Azure" envolve a utilização do portal do Azure para navegar e encontrar serviços agrupados por suas funções específicas, como ocupação, armazenamento, rede e segurança. Essa abordagem facilita a identificação de soluções adequadas para necessidades específicas, permitindo que usuários e desenvolvedores acessem rapidamente os recursos necessários para suas aplicações e projetos. Essa categorização otimiza a gestão e a implementação

# Criando máquinas Virtuais na Azure
 SLA (Service Level Agreement) é um acordo entre o provedor de serviços (como o Azure) e o cliente que define os níveis mínimos de desempenho e as especificações exigidas para um serviço específico.
Garanta metas de desempenho específicas para cada produto ou serviço do Azure.
Definir garantias de tempo de atividade e conectividade (geralmente entre 99,9% e 99,999%).
Descrever como a Microsoft responderá caso não cumpra as especificações do SLA.
Permite créditos de serviço ao cliente em caso de falha na entrega do serviço.

# Configurando uma instância de Banco de Dados na Azure
A Instância Gerenciada de SQL do Azure é um serviço PaaS totalmente gerenciado que oferece quase 100% de compatibilidade com o SQL Server. Principais características:
Escalabilidade e alta disponibilidade, atualizações automáticas e backups isolamento de rede virtual (VNets), apoio à migração de bancos de dados locais
Entre no portal do Azure
Selecione SQL do Azure > Instância Gerenciada de SQL
Escolha opções de configuração
Escolha a configuração adequada para carga de trabalho
Considere a migração existente de bancos de dados locais
Utilize recursos avançados de segurança
Monitore o desempenho após implantação
A Instância Gerenciada oferece uma solução completa para mover cargas de trabalho de banco de dados para nuvem com o menor esforço de migração possível.

# Construindo Arquiteturas no Azure
O Azure oferece ferramentas e diretrizes para arquitetar soluções eficientes. Algumas práticas recomendadas incluem:

Utilização arquiteturas de múltiplas camadas para aplicações complexas
Implementar recursos como conjuntos de disponibilidade e dimensionamento automático
Seguir padrões recomendados para desenvolvimento no Azure
Uso do Azure Advisor para obter recomendações sobre melhorias
Crie diagramas de arquitetura do Azure para visualizar a infraestrutura da solução
Usar ferramentas como Azure Blueprints para definir conjuntos reaproveitáveis ​​de recursos
O objetivo é criar soluções otimizadas em termos de desempenho, custos e segurança, seguindo os princípios do Framework Well-Architected do Azure.

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
O Azure permite uma ampla gama de configurações personalizadas para máquinas virtuais (VMs), focando-se em recursos e dimensionamentos. Algumas das principais características incluem:

Escolha de tamanhos variados de VMs, desde pequenas até grandes instâncias
Opções de armazenamento local e gerenciado pelo sistema
Configuração de memória, CPUs e discos conforme necessário
Suporte a diferentes tipos de discos (SSD e HDD)
Possibilidade de adicionar ou remover recursos após a criação do VM
Capacidade de migrar VMs entre regiões sem interrupção
Ferramentas de monitoramento e otimização de desempenho
Integração com outros serviços do Azure para automatização e orquestração
O objetivo é fornecer flexibilidade para ajustar os recursos das VMs às necessidades específicas do aplicativo, garantindo eficiência e escalabilidade.

#  Dominando o Armazenamento na Azure
O Azure Storage é uma plataforma de armazenamento em nuvem robusta e escalável, oferecendo vários serviços para diferentes tipos de dados:

Blob Storage: Ideal para armazenar grandes quantidades de dados não estruturados (imagens, vídeos, documentos)
File Storage: Permite montagem de compartilhamentos de arquivos no Azure
Queue Storage: Útil para mensagens sincronizadas entre componentes de aplicações
Table Storage: Para armazenar dados estruturados em tabelas
Principais características:

Alta disponibilidade e disponibilidade
Escalabilidade automática
Segurança e acesso controlado
Suporte a vários protocolos (HTTP/HTTPS, SMB)
Integração com outros serviços Azure
Para configurar o armazenamento:

Crie uma conta de armazenamento
Escolha o tipo de serviço adequado para seus dados
Configurar políticas de acesso e segurança
Utilize ferramentas como Azure Portal ou CLI para gerenciar recursos
O objetivo é aproveitar a flexibilidade e escalabilidade do Azure Storage para armazenar e acessar dados de forma eficiente em suas soluções.

# Entendendo sobre Segurança e Identidade na Azure
A segurança e identidade no Azure se concentram principalmente nos seguintes aspectos:

Gerenciamento de identidades:
O Microsoft Entra ID é a principal solução para gerenciamento de identidades e acesso no Azure.
Ele combina diretórios, acesso a aplicativos e proteção de identidades em uma única solução.
Autenticação e autorização:
Single Sign-On (SSO) para milhares de aplicações SaaS e acesso a aplicações locais.
Controle baseado em papéis (RBAC) para gerenciar quem tem acesso aos recursos Azure.
Proteção contra ameaças:
Detecção de riscos e vulnerabilidades em identidades.
Autenticação multifator e políticas de acesso condicional.
Governança de identidades:
Gerenciamento de usuários, grupos e dispositivos.
Provisionamento de acesso seguro para aplicações locais através de proxy de aplicação.
Gestão privilegiada:
Just-in-Time (JIT) para acesso administrativo temporário.
Relatórios e alertas sobre uso de contas com privilégios.
Monitoramento e melhoria contínua:
Pontuação de segurança de identidade para medir e melhorar a postura de segurança.
Revisões periódicas de acesso e gestão de concessões.
O objetivo é criar uma estrutura de segurança robusta, centralizada nas identidades, para proteger recursos e dados na nuvem Azure.

# Otimizando Custos no Azure

A supervisão de custos no Azure envolve estratégias para gerenciar e reduzir os custos associados ao uso de serviços da nuvem Azure. Algumas práticas importantes incluem:

Dimensionamento correto de recursos: Escolha o tamanho adequado de VMs e outros recursos para evitar sobreaquisição desnecessária.
Uso de tags e organização de recursos: Categorizar recursos por departamento, projeto etc. para facilitar o rastreamento e controle de custos.
Escalar recursos automaticamente: ajusta automaticamente o número de instâncias de VMs em resposta às variações de demanda.
Desligue recursos quando não utilizados: Parar máquinas virtuais e outros recursos durante períodos de baixa atividade.
Utilização planos de economia: Comprar capacidade reservada para cargas de trabalho previsíveis.
Monitore e analise custos regularmente: Usar ferramentas do Azure para monitorar o uso e identificar oportunidades de otimização.
Negociar preços: Explorar opções de negócios para volumes maiores de uso.
Implementar políticas de governança: Definir limites e restrições para evitar gastos excessivos.

# Gerenciando Politicas em Acessos Azure
Gerenciar políticas de acesso no Azure envolve criar e aplicar regras para controlar quem pode acessar quais recursos. Algumas práticas importantes incluem:

Usar o Azure Policy para criar definições de política que especifiquem condições e efeitos para recursos do Azure.
Aplicar políticas em diferentes escopos (assinaturas, grupos de gerenciamento, grupos de recursos) conforme necessário.
Criar iniciativas para agrupar políticas relacionadas e monitorar a conformidade em múltiplos recursos.
Utilização de políticas de acesso condicional no Azure Active Directory para exigência de autenticação adicional baseada em fatores ou condições.
Configure controles de acesso baseados em funções (RBAC) para gerenciar controles de recursos do Azure.
Implementar políticas de acesso condicional para aplicações SaaS e locais.
Usando o Azure AD Identity Protection para detecção e resposta a riscos de identidade.
Crie pacotes de acesso para gerenciar fluxos de trabalho de acesso a recursos específicos.

# Ferramentas de Implantação na Azure
As ferramentas de implantação no Azure permitem automatizar e otimizar o processo de entrega de software. As principais ferramentas incluem:

Azure DevOps: Plataforma completa de CI/CD que oferece pipelines de implantação, orquestração de testes e monitoramento.
Azure Pipelines: Serviço de orquestração de pipelines que permite criar fluxos de trabalho de CI/CD.
Azure Functions: Serviço de computação serverless para executar código em resposta a eventos.
Azure Container Instances: Serviço para executar contêineres Docker sem gerenciar servidores.
Azure Kubernetes Service (AKS): Plataforma gerenciada para implantar e gerenciar contêineres.
Conjuntos de escala de VM do Azure: recursos de dimensionamento automático para máquinas virtuais.
Azure App Service: Serviço PaaS para aplicações web hospedadas em diversas linguagens.
Azure Traffic Manager: Ferramenta de balanceamento de carga para distribuição de tráfego entre regiões.
Práticas recomendadas:

Utilização de pipelines de CI/CD automatizados
Implementar testes contínuos no pipeline
Usar variáveis ​​de ambiente e segredos para configuração
Configurar monitoramento e alertas
Utilização de ferramentas como Azure Monitor para rastreamento de implantações

# Monitoramento Inteligente com o Azure

O Azure oferece ferramentas de monitoramento para fornecer insights e análises preditivas. Algumas características principais incluem:

Azure Monitor: Plataforma de monitoramento unificada que coleta dados de diversos serviços Azure.
Análise de logs e estatísticas: Coleta e processa dados em tempo real para identificar padrões e anormalidades.
Machine Learning: Integração com serviços AI/ML para prever problemas e melhorar desempenho.
Alertas personalizáveis: Notificações automáticas baseadas em critérios definidos.
Visualizações e dashboards: Interface gráfica para visualização de métricas e KPIs.
Correlação de eventos: Identificação de causas raiz de problemas complexos.
Monitoramento preditivo: Previsão de falhas e anomalias futuras.
Integração com serviços específicos: Exemplo, monitoramento de VMs, contêineres, redes.
Exportação de dados: Facilita análise externa e integração com ferramentas de terceiros.
Governança e conformidade: Regulamentações e políticas de monitoramento.




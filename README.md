# Construindo-Arquiteturas-no-Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Resumo do que aprendi: Construindo Arquiteturas no Azure

No curso entendi que o Azure oferece diversas ferramentas e boas práticas para desenhar arquiteturas em nuvem seguras, escaláveis e resilientes.

Principais pontos:

Conceito de Arquitetura no Azure

É a forma de organizar recursos e serviços para atender a uma solução de negócio.

Envolve computação, rede, armazenamento, banco de dados, segurança e monitoramento.

Ferramentas de apoio

Azure Architecture Center: repositório com guias de referência.

Microsoft Well-Architected Framework: boas práticas em 5 pilares → Confiabilidade, Segurança, Otimização de Custos, Desempenho e Eficiência Operacional.

Diagramas e modelos prontos no portal e no Azure Design Studio.

Boas práticas de arquitetura

Alta disponibilidade: usar zonas de disponibilidade, balanceadores e redundância.

Escalabilidade: prever crescimento com Scale Sets e App Services.

Segurança: aplicar o princípio de menor privilégio, usar NSGs, Firewalls e Key Vault.

Governança: padronizar com Azure Policy, RBAC e Management Groups.

Monitoramento e custos: acompanhar consumo via Azure Monitor e Cost Management.

Exemplos de arquiteturas comuns

Web App escalável: App Service + Banco de Dados + Load Balancer.

Arquitetura de Big Data: Data Lake + Synapse + Machine Learning.

Ambiente híbrido: Azure VPN Gateway ou ExpressRoute integrando on-premises.

Aprendizado principal

Antes de criar recursos isolados, é fundamental planejar a arquitetura completa considerando resiliência, performance, custo e segurança.

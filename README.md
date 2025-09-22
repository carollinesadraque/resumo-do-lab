# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
o que é e como funciona: O Azure é a plataforma de computação em nuvem da Microsoft, que oferece serviços a pessoas e empresas. Funciona como um data center virtual para hospedar sites e sistemas, guardar arquivos e banco de dados, cria redes seguras na numvem, usa IA e analise de dados. O serviço corresponde como "alugar computadores de ponta". Em resumo, é um conjunto de ferramentas na internet que substitui ou complementa servidores e softwares que antes ficavam só dentro da empresa.
Conceitos de nuvem: usar recursos de TI (servidores, bancos, redes,aplicativos) pela internet em vez de depender apenas do computador local ou do data center próprio. Funciona com modelos diferentes de serviços como SAAS (software como serviço, usando programas prontos, teams, outlook etc)/ iaas-você aluga máquinas virtuais, redes e discos. É como alugar um “computador gigante” na nuvem. (serviço redes, discos ou maquinas virtuais), paas:você usa uma plataforma pronta para rodar aplicativos sem precisar gerenciar servidores. Ex.: Azure App Service (plataforma como serviço (hospedar apps sem cuidar de servidores). Oss modelos de implantação podem ser em nuvem publica (azure, aws, google cloud), nuvem privada (servidores exclusivos da empresa) e nuvem híbrica (mistura dos dois). Os beneficios em adiquirir esse tipo de serviço, são: agilidade, redução de custos, segurança, disponibilidade etc.
Principais benefícios:
Escalabilidade
Crescer ou diminuir recursos conforme a demanda.
Ex.: Loja online que aumenta servidores na Black Friday e reduz depois.
Elasticidade
Ajuste automático e quase imediato de recursos.
Ex.: Um app que aumenta poder de processamento só quando recebe muitos acessos.
Confiabilidade e alta disponibilidade
O Azure tem datacenters no mundo inteiro, garantindo redundância.
Isso significa menos chance de ficar fora do ar.
Segurança
Camadas de proteção física, digital e políticas de acesso (MFA, RBAC).
Mais investimento em segurança do que a maioria das empresas poderia ter sozinha.
Previsibilidade de custo
Paga-se só pelo uso (modelo “pay-as-you-go”).
Também existem reservas (contratos de 1 a 3 anos que reduzem custos).
Agilidade e inovação
Permite testar novas ideias rapidamente sem precisar comprar hardware caro.
Ex.: testar IA no Azure Cognitive Services sem precisar ter um supercomputador.
Modelo de responsabilidade compartilhada
A Microsoft cuida da infraestrutura física.
Você cuida dos dados e configurações.
Isso simplifica a vida de quem usa.
Arquitetura e serviços Azure: regiões: locais no mundo onde ficam os datacenters (Brasil, EUA, etc). Areas disponiveis ou Availability Zones : zonas independentes dentro de uma região para garantir alta disponilidade. Grupo de recursos e subinscrições: formas de organizar os recursos criados;. Grupos de gerenciamento: camadas acima para organizar varias contas, subscrições.
Principais serviços do Azure: Compute (processamento): Máquinas Virtuais, App Service, Azure Functions, Kubernetes (AKS).
Armazenamento: Blob (arquivos grandes), Files (pasta de rede), Disk (discos de VM), Queue (filas).
Redes: Virtual Network (VNet), VPN Gateway, ExpressRoute, DNS, Load Balancer.
Bancos de dados: Azure SQL Database, Cosmos DB, MySQL, PostgreSQL.
Ferramentas de desenvolvimento e integração: Azure DevOps, GitHub, Logic Apps
IA e dados: Azure Cognitive Services, Machine Learning, Synapse Analytic
Segurança: Microsoft Entra ID (antigo Azure AD): identidade e login.
RBAC (Role-Based Access Control): dar permissões específicas para usuários/grupos.
MFA (Autenticação multifator): login mais seguro (senha + celular, por exemplo).
Defender for Cloud: monitora vulnerabilidades e ataques.
Princípio Zero Trust: nunca confiar automaticamente, sempre verificar.
Governança:
Azure Policy: regras para garantir conformidade (ex.: só criar recursos no Brasil).
Resource Locks: travar recursos para evitar exclusão acidental.
Tags: etiquetas para organizar recursos por projeto/departamento.
BluePrints: modelos para aplicar governança de forma padronizada.
Custos:
Modelo Pay-as-you-go: pagar pelo uso (como conta de luz).
Reserved Instances: desconto por contratar 1–3 anos.
Pricing Calculator: simular custos antes de criar recursos.
TCO Calculator: comparar custos da nuvem x infraestrutura local.
Azure Advisor: recomenda como economizar.


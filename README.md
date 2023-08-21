# Visão Geral De Produtos E Serviços Da Amazon Web Services (Aws)
Artigo escrito para a comunidade DIO (https://web.dio.me)

Pessoal, estou compartilhando com vocês este resumão contendo a visão geral de produtos e serviços da AWS, que elaborei durante as atividades e cursos que fiz aqui na DIO, e das consultas a documentação no site da AWS. 

Espero que seja tão útil para vocês assim como foi prazeroso para mim elaborá-lo. Bom proveito a todos. 

## PRODUTOS E SERVIÇOS AWS

A AWS é uma plataforma segura que oferece um amplo conjunto de serviços globais baseados na nuvem desde 2006. Atualmente são 23 serviços de acesso sob demanda a computação, armazenamento, gerenciamento de redes, banco de dados e ferramentas de monitoria e gerenciamento, dentre outros. Os principais serviços são:
- Computação: EC2; Lambda; ECS; Elastic Beanstalk
- Armazenamento: S3; EBS; EFS; Glacier
- Banco de Dados: RDS (Aurora, Postgre, MySQL, MariaDb, Oracle DB e SQLServer); DynamoDb; Elasticache 
- Redes: VPC; ELB; CloudFront; Route53; 
- Segurança: IAM; Organizations; Cognito; KMS

## O QUE É COMPUTAÇÃO EM NUVEM

CLOUD COMPUTING ou SERVIÇOS DE COMPUTAÇÃO EM NUVEM é o conjunto de serviços de infraestrutura de TI disponibilizados pela internet, permitindo o acesso a recursos como servidores, armazenamento e software/aplicativos, sem a necessidade de tê-los instalados fisicamente.

## BENEFÍCIOS DA COMPUTAÇÃO EM NUVEM

- Redução de custos pagando apenas recursos utilizados.
- Acesso remoto de qualquer lugar que tenha uma conexão de internet. 
- Flexibilidade pois os recursos são escaláveis conforme a necessidade.
- Eficiência ao permitir que as empresas foquem em seus negócios ao invés de gerenciar os recursos de TI.
- Confiabilidade ao disponibilizar backups em locais remotos e rápida recuperação quando necessário.

## AS 6 VANTAGENS DA COMPUTAÇÃO EM NUVEM

1. Trocar o investimento em infraestrutura de TI (datacenters, servidores, manutenção da equipe, etc.) por custo variável, pagando somente pelos recursos consumidos.
2. Beneficiar-se da economia de escala dos provedores de serviços, diluindo os custos pela grande quantidade de clientes e resultando em preços menores de pagamento conforme o uso.
3. Eliminar as constantes suposições sobre a capacidade de sua infraestrutura ou necessidades de aquisição, com a facilidade para reconfigurar os recursos com alguns minutos de antecedência conforme a demanda.
4. Aumentar a velocidade e a agilidade da organização, pois a diminuição do tempo para administrar e disponibilizar os recursos de infraestrutura para os desenvolvedores (agora na casa de minutos) permite que os atuais custos e tempos necessários para experimentar e desenvolver sejam bem mais baixos.
5. Focar nos seus negócios e nos seus clientes, com a diminuição da necessidade de investimentos e esforços em administração e manutenção de infraestrutura.
6. Tornar-se global em minutos, apenas alguns cliques poderão implantar sua aplicação em várias regiões ao redor do mundo fornecendo menor latência e melhor experiência aos seus clientes a um custo mínimo.

## OS MODELOS DE COMPUTAÇÃO EM NUVEM

1. IaaS - Infraestrutura como serviço: fornece os componentes básicos da TI de nuvem, como acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço para armazenamento de dados. Ex: Máquinas virtuais Amazon EC2 ou armazenamento Amazon S3.
2. PaaS - Plataforma como serviço: fornece os serviços de gerenciamento da infraestrutura de servidores, geralmente hardware e manutenção e atualização de sistemas operacionais para que você se dedique exclusivamente na implantação e manutenção da sua aplicação. Ex: Heroku, AWS Lambda.
3. SaaS - Software como serviço: fornece um produto completo executado e gerenciado pelo provedor de serviço. Resta ao usuário final apenas utilizar a solução (seja um serviço ou um produto) que está sendo disponibilizada sem se preocupar com sua instalação. Ex: Netflix, Google Drive, AirBnB.
4. Caas - Container como serviço: fornece uma maneira de empacotar e executar aplicativos, utilizando ambientes virtualizados. Ex: Docker, Amazon ECS, Google Kubernetes.

## OS NÍVEIS DE IMPLANTAÇÂO DA COMPUTAÇÃO EM NUVEM

- Nuvem - Uma aplicação é totalmente implantada na nuvem se todas as partes da aplicação e os recursos utilizados são executados nela. Desfruta-se plenamente de todos os benefícios e vantagens da Nuvem.
- Híbrida - Quando conecta os recursos (infraestrutura e aplicações) baseados na nuvem a recursos existentes que não se encontram na nuvem. Aproveita-se assim parcialmente dos benefícios e vantagens da Nuvem. 
- On-premises - Quando as ferramentas de gerenciamento de recursos e virtualização estão em uma "nuvem privada", ou seja, em algum fornecedor de recurso dedicado, sendo necessário usar tecnologias de gerenciamento e virtualização de aplicações para tentar aumentar a disponibilidade de recursos.

## GLOBALIZAÇÃO

- Região - é uma área geográfica no mundo com 2 ou mais Zonas de disponibilidade; são isoladas, proporcionando maior tolerância a falhas e estabilidade; os recursos não são replicados entre as zonas; a comunicação entre zonas é feita através de backbones; para decidir qual região utilizar, deve-se levar em consideração aspectos legais na governança de dados, latência, proximidade com clientes, disponibilidade de alguns serviços e seus custos.
- Zona de disponibilidade (AZ) - São partições da região isoladas fisicamente, contendo pelo menos um datacenter; é considerada como uma zona de falha independente; oferecem capacidade de operar aplicações e bancos de dados mais altamente disponíveis, tolerantes a falhas e escaláveis do que seria em um único datacenter.
- Datacenter - é uma instalação segura, com suprimento de energia, rede e conectividade redundantes e independentes, inclusive, dos suprimentos de backups; são alojados em instalações distintas e fisicamente isolados; local onde o processamento e o processamento ocorrem; estão localizados em áreas cuidadosamente planejadas para evitar, por exemplo, inundações; estima-se que cada datacenter abrigue entre 50.000 a 80.ooo servidores.
- Local de borda - garantem o cache local para performance no acesso de recursos, por exemplo, armazenamento e recuperação de dados. 
 
## SEGURANÇA

A AWS provê uma ifraestrutura resiliente projetada para alta segurança, disponibilizando:
- Gerenciamento do controle de acesso a serviços e recursos
- Registros em log e Monitoramento e auditoria de eventos
- Criptografia de dados em repouso e em trânsito
- Gerenciamento de chaves
- Segmentação de Rede  
- Firewall e Proteção contra DDoS
- Backup e Recuperação de Desastres
- Automação das tarefas de segurança
- Relatórios de segurança e conformidade
- Serviço de cadastro, login e controle de acesso a apps web e mobile 

## MODELO DE RESPONSABIIDADE COMPARTILHADA

A segurança e a conformidade dos serviços gerenciado são uma responsabilidade compartilhada entre o cliente e a AWS. Basicamente a AWS é responsável pela segurança "da" nuvem, enquanto o cliente é responsável pela segurança "na" nuvem.

A AWS é responsável por oferecer segurança e confiabilidade em:
- Infraestrutura e serviços gerenciados de computação, armazenamento banco de dados e redes
- Infraestrutura global das Regiões, Zonas de Disponibilidade e Locais de borda

O cliente é responsável por:
- Segurança dos dados
- Gerenciamento da identidade e acesso a plataforma AWS e aplicações
- Configuração de sistemas operacionais, redes e firewall
- Criptografia de dados, integridade e autenticação client-side
- Criptografia de dados e de arquivos client-side
- Criptografia e integridade dos dados trafegados pela rede

## USO ABUSIVO E COMPROMETIMENTO

A AWS detecta e encerra imediatamente atividades abusivas em seus recursos usando mecanismos como:
- Monitoramento de eventos internos da AWS
- Inteligência de segurança externa contra espaço de endereço de rede da AWS
- Reclamações de abuso na Internet contra recursos da AWS
A AWS tem o compromisso de trabalhar com os clientes para prevenir, detectar e mitigar abusos e se defender contra recorrências futuras.

## GOVERNANÇA

- A Governança de Segurança define as políticas e objetivos de controle para ajudar a gerenciar riscos
- Visa apoiar os objetivos de negócio
- Os riscos são baseados em probabilidade (frequência de ocorrências anteriores) e na consequência (custo financeiro, de reputação e de tempo do evento)
- Compreender o Modelo de Responsabilidade Compartilhada da AWS é a camada mais importante
- Aplicar e atualizar as políticas de segurança (IAM, IAM Identity Center, SCP) deve ser feita a cada nova configuração dos serviços
- Cada camada deve restringir os recursos da camada anterior, de forma a mitigar os riscos residuais  

## GESTÃO DE CUSTOS

- Pay-as-you-go - pagamento de acordo com o uso dos recursos
- Instâncias Sob Demanda - pagamento por hora/segundo em contratos curtos e sem exigência de permanência mínima; escaláveis conforme necessidade 
- Instâncias Reservadas - contratos com maior permanência; descontos significativos de até 70% do preço sob demanda
- Instâncias Pontuais - solicitar capacidade pontual complementar por até 90% do preço sob demanda; duração até 6h com redução de 30 a 60% do preço
- Servidor dedicado - servidor físico EC2 dedicado; permite a redução do custo de licenças vinculadas a servidores (es: Windows Server, SQL Server, Suse Linux Enterprise) 

## NÍVEL GRATUITO FREE-TIER

- 12 meses gratuitos - disponível para novos clientes a partir da data de cadasro na AWS; paga taxa normal após 12 meses ou se exceder o nível gratuito
- Sempre Gratuito - não expiram após o período gratuito de 12 meses; disponível para todos os clientes  
- Testes Gratuitos - ofertas de avaliação de curto prazo que começam a vigorar a partir do primeiro uso; paga a taxa normal após expirar o prazo

## GESTÃO FINANCEIRA (CFM)

Conjunto de atividades para medir, otimizar e planejar custos a medida que aumenta o uso dos recursos e serviços, em 4 áreas:
- Medição e Responsabilidade: estabelecer custo e visibilidade para garantir transparência e responsabilidade dos custos
- Otimização de Custos ou Economia: garantir que se pague somente pelo que precisa
- Planejamento e Previsão: Entender os custos associados a futuros workloads
- Operações Financeiras: Permitir que a organização escale a gestão financeira da nuvem (CFM).

Resultados esperados:
- Redução do custo unitário ao escalar
- Reinvestir despesas desnecessárias e agilizar o negócio, inovar
- Melhorar a previsibilidade financeira
- Criar uma cultura consciente de custos

Competências presentes após o CFM
- Propriedade e responsabilidade
- Parceria entre as áreas Financeira e Tecnologia
- Alocação correta de custos
- Visibilidade de custos
- Otimização de custos
- Previsibilidade financeira

## MODELO DE MATURIDADE

Objetivos:
- Avaliar a organização e identificar oportunidade de melhoria
- Autoavaliar e traçar um roteiro para aumentar a maturidade do CFM

Modelos:
1. Novato
2. Iniciante
3. Intermediário
4. Avançado
5. Especialista

CTA (Call to Action) ou Plano de Ação:
- objetivo é atingir o sucesso financeiro na AWS
- montar um Roadmap para avaliar ações com o objetivo de aumentar a maturidade das competências realmente importantes para a organização

Recomendações conforme o Nível de Maturidade:
1. Iniciante no processo
- ientificar propriedade e responsabilidade e estabelecer a parceria entre as áreas Financeira e TI
- identificar oportunidades de otimização de custos
2. Já tem áreas interessadas na redução de custos
- aumentar a proatividade na redução de custos
- difundir os KPIs entre os Stakeholders
- aumentar a previsibilidade de custos
3. Já segue as práticas recomendadas do CFM
- automatizar estratégias de alocação e iniciativas de otimização de custos a longo prazo
- permitir que sejam escaladas
 


Fonte:

Whitepaper Visão geral da Amazon Web Services
https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/introduction.html

Pilar Segurança: AWS Well-Architected Framework
https://docs.aws.amazon.com/pt_br/wellarchitected/latest/security-pillar/welcome.html

Produtos da nuvem AWS
https://aws.amazon.com/pt/products/

Cursos do Bootcamp Descubra a Nuvem AWS - Nexa Resources, módulo Fundamentos de Computação em Nuvem na AWS
https://web.dio.me/track/descubra-nuvem-aws-nexa-resources

Cursos do Bootcamp Descubra a Nuvem AWS - Resources, módulo Fundamentos de Computação em Nuvem na AWS
https://web.dio.me/track/descubra-nuvem-aws-localizalabs-meu-futuro-e-tech
	



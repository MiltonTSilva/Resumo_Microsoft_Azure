# Resumo Microsoft Azure
## Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab sobre Microsoft Azure

1 - O que é computação em nuvem

Computação em nuvem é a entrega de serviços de computação, como servidores, armazenamento, bancos de dados, redes, software, análises e inteligência, pela internet ("a nuvem"). Isso permite que você acesse e use recursos de TI sob demanda, sem precisar gerenciar fisicamente o hardware.

Imagine que você precisa de um servidor para hospedar um site. Em vez de comprar e configurar um servidor físico, você pode alugar um servidor virtual de um provedor de nuvem, como a Microsoft Azure. Isso oferece flexibilidade, escalabilidade e economia de custos, pois você paga apenas pelo que usa.

2 - Modelos de nuvem

Existem três principais modelos de nuvem:

- Nuvem Pública: Recursos de computação são fornecidos por terceiros, como a Microsoft Azure, e compartilhados entre múltiplos usuários. É ideal para empresas que precisam de escalabilidade e custo-benefício.

- Nuvem Privada: Recursos de computação são usados exclusivamente por uma única organização. Oferece maior controle e segurança, sendo ideal para empresas com requisitos rigorosos de conformidade.

- Nuvem Híbrida: Combina nuvens públicas e privadas, permitindo que dados e aplicativos sejam compartilhados entre elas. Oferece flexibilidade e opções de implantação mais variadas.

Cada modelo tem suas vantagens e desvantagens, dependendo das necessidades específicas da sua organização. 

3 - Custo de capital versus custo operacional

No contexto de serviços em nuvem, os custos de capital (CAPEX) e os custos operacionais (OPEX) são duas formas de investimento que diferem na maneira como os recursos são gastos:

- Custo de Capital (CAPEX - Capital Expenditure):

São despesas de investimento em bens duráveis, como equipamentos e infraestrutura. Em um cenário on-premises (servidores locais), por exemplo, isso incluiria a compra de servidores, infraestrutura de rede, datacenters, etc.
Estes custos são fixos e ocorrem antecipadamente, exigindo uma grande quantia inicial de investimento.
Com o uso de serviços de nuvem como o Azure, o CAPEX diminui ou até mesmo desaparece, pois a infraestrutura é gerenciada pela Microsoft, e o cliente paga apenas pelo serviço utilizado.

- Custo Operacional (OPEX - Operational Expenditure):

Representa os custos contínuos e variáveis relacionados à operação dos serviços em nuvem, como taxas mensais de assinatura, custo de uso de serviços de computação, armazenamento, bancos de dados, e outros serviços no Azure.
O OPEX permite uma maior flexibilidade, pois os custos são distribuídos ao longo do tempo, e o usuário paga apenas pelo que usa. Isso torna a nuvem ideal para organizações que preferem gastos variáveis, que podem ser escalados para cima ou para baixo conforme a necessidade.

Resumo: No Azure, o modelo de cobrança é predominantemente OPEX, permitindo que você pague conforme o uso e escale os serviços rapidamente. Isso substitui a necessidade de grandes investimentos iniciais (CAPEX), pois a Microsoft gerencia a infraestrutura e a manutenção dos recursos.

4 - Benefícios da Nuvem:

- Escalabilidade e Elasticidade: O Azure permite ajustar os recursos de acordo com as necessidades da sua operação, garantindo flexibilidade para lidar com demandas variáveis. 
DIO

- Disponibilidade e Confiabilidade: Com uma rede global de data centers, o Azure proporciona alta disponibilidade e confiabilidade, assegurando que seus serviços permaneçam operacionais mesmo diante de falhas em componentes individuais. 
DIO

- Segurança e Conformidade: O Azure segue rigorosos protocolos de segurança e oferece a maior cobertura de conformidade simplificada do mercado, garantindo a proteção e a privacidade dos dados da sua empresa. 
LATTINE GROUP

- Redução de Custos: Ao migrar para o Azure, sua empresa pode economizar em investimentos de hardware e manutenção, pagando apenas pelos recursos utilizados, o que otimiza o orçamento de TI. 
SGA

- Inovação Rápida: O Azure oferece uma plataforma abrangente com serviços avançados, incluindo inteligência artificial e aprendizado de máquina, permitindo que sua empresa inove e se adapte rapidamente às demandas do mercado.

5 - IaaS, PaaS e SaaS são três modelos principais de serviço em computação em nuvem, cada um com seu próprio nível de controle, responsabilidade e flexibilidade:

- IaaS (Infrastructure as a Service)
Definição: IaaS fornece infraestrutura de TI completa na nuvem, como servidores, redes e armazenamento. É a camada mais básica, em que o usuário controla os recursos, mas depende do provedor para a infraestrutura física.
Exemplo de uso: Hospedar e gerenciar um servidor web ou banco de dados.
Exemplos de provedores: Amazon Web Services (AWS EC2), Google Compute Engine, Microsoft Azure.
Responsabilidade do usuário: Manter o sistema operacional, aplicativos, middleware e dados.

- PaaS (Platform as a Service)
Definição: PaaS oferece uma plataforma que inclui infraestrutura e um ambiente para desenvolvimento, permitindo que desenvolvedores criem, testem e implementem aplicações sem gerenciar a infraestrutura.
Exemplo de uso: Desenvolvimento e implantação de uma aplicação web ou API.
Exemplos de provedores: Google App Engine, Microsoft Azure App Services, Heroku.
Responsabilidade do usuário: Focar no desenvolvimento e na gestão das aplicações, enquanto o provedor cuida do sistema operacional, infraestrutura e segurança básica.

- SaaS (Software as a Service)
Definição: SaaS oferece software pronto para uso na nuvem, acessado por meio de um navegador ou app. É a camada mais alta, onde o usuário apenas consome o serviço sem ter controle sobre a infraestrutura ou plataformas.
Exemplo de uso: Gerenciar emails, criar documentos, armazenar arquivos.
Exemplos de provedores: Gmail, Google Workspace, Microsoft 365, Salesforce.
Responsabilidade do usuário: Usar o software e personalizá-lo dentro das limitações do serviço, sem necessidade de gerenciar infraestrutura, plataforma ou segurança.

- Comparação rápida

  1 - Controle: IaaS oferece o controle máximo sobre a infraestrutura, enquanto SaaS tem o menor controle.
  
  2 - Gerenciamento: IaaS exige mais gerenciamento e conhecimento técnico, enquanto SaaS é mais simples e gerenciado pelo provedor.
  
  3 - Flexibilidade: IaaS e PaaS permitem maior customização, enquanto SaaS é focado na simplicidade e acessibilidade.

Esses modelos ajudam as empresas a escolher o nível de controle e responsabilidade ideal para suas necessidades e estratégias de TI.

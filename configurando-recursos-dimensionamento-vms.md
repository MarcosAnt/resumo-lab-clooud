## Quiz
- Quais das instruções sobre máquinas virtuais (VMs) e contêineres são verdadeiras?
  - VMs e contêineres são isolados do hardware do host.

- Ela estende as redes locais para o Azure por meio de uma conexão privada facilitada por um provedor de conectividade.
  - ExpressRoute

- As Instâncias de Contêiner do Azure são classificadas como uma oferta no modelo:
  - PaaS

- Para possibilitar a comunicação entre redes virtuais, qual configuração é necessária?
  - Emparelhamento de rede (VNet Peering)

- Consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente. 
  - Serviços de Aplicativos

## Lab: Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
- para criar VMs existem configurações pré difinidas (recurso novo):
  - desenvolvimento/teste
  - produção

- além das configurações pré-defindas existe tbm opção de criar já com alguns aplicativos incluídos;

-  Zona de disponibilidade: cada zona correspode a uma região física;
  - a boa prática é dividir seus dados em mais de uma região para segurança;
 
- Modo de dimencionamento:
  - atualizar manualmente;
  - dimencionamento automático: precisa configurar parâmetros como minímo e máximo de VMs, escalar e reduzir horizontalmente, duração da consulta;
  
- Spot: modo em que se paga menos pelos serviços mas não se tem prioridade nem garantia de disponibilidade, se chegar alguém com mais prioridade (pagando mais pelos serviços) sua aplicação é derrubada;

- é possível ter uma imagem base personalizada para criação de novas VMs para organização;

- importante marcar as opções **"Excluir junto com a VM"** quando estiver criando a VM para não acontecer de ter recursos "orfãos" gerando custos mesmo após ter excluído a VM, pois só de existir os recursos tem seu custo;

- lembrar de hablitar o backup (modelo padrão ou avançado - mais seguro);

- configurar portas de entrada, tipo de disco, alertas de consumo e desempenho da VM, extensões, tags da VM (para identificar na fatura),

- no passo de "Revisar + cirar" o Azure da a estimativa de custo mensal;

# Área de Trabalho Virtual do Azure
Permite criar máquinas virtuais que podem ser acessadas remotamente sem necessidade de um hardware específico, muito útil para empresa fornecer ambiente de trabalho para os funcionários.

# Aplicativo de Função (Azure Function)
É um serviço de computação sem servidor (serverless) oferecido pela Microsoft Azure. Em essência, elas permitem que você execute pequenos trechos de código ("funções") na nuvem sem a necessidade de provisionar ou gerenciar infraestrutura (servidores). 

- Úteis para automação
- Pode selecionar linguagem de programação ( o SO depende da linguagem ex.: .NET, Java, NodeJS -> windows, python -> linux)

Modelos de custo:
- Computação sem servidor: Você não precisa se preocupar com a infraestrutura. O Azure aloca dinamicamente os recursos necessários;
- Orientado por eventos (Event-driven): As funções são executadas em resposta a eventos ou gatilhos. Esses gatilhos podem ser uma variedade de eventos de outros serviços do Azure (como a chegada de uma mensagem em uma fila);
- Pague pelo que usar (Pay-per-use): O modelo de preços é baseado no consumo de recursos e no número de execuções da sua função. Você só paga quando seu código está rodando;
- Escalabilidade automática: O Azure Functions escala automaticamente para atender à demanda.

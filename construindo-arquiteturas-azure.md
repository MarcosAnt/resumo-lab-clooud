## Quiz

- Os conjuntos de disponibilidade são compostos por quais dos itens a seguir?
  - Domínios de atualização e domínios de falha

- É um contêiner que você usa para gerenciar e agregar recursos em uma única unidade.
  - Grupo de Recursos

- Qual objeto do Microsoft Azure contém múltiplos datacenters que são conectados por uma rede de baixa latência?
  - Uma região

- Assinale a alternativa incorreta sobre Grupos de Recursos.
  - Os grupos de recursos podem conter apenas recursos de uma mesma região.

## Lab: Construindo Arquiteturas no Azure

- Regiões
  - Brazil South: São Paulo State - All costumers and partners (replicação automática para US);
  - Brazil Souteast: Rio Janeiro - Reserved for Brazil South costumers requiring scenario-based in-country disaster recovery (sem replicação automática);
  - para atender a LGPD o cliente ter que requisitar para a MS para ter seus dados replicados para regiões no exterior aí os Brazil Souteast replica para o Brazil South;

- Criando grupo de recursos
  - selecionar assinatura;
  - selecionar região;
  - criar marcação: boa prática para identificar na fatura depois;
  - log de atividade é como um log de autoria de tudo;
  - IAM: controle de acesso;
  - Eventos: últi para automações;

- VNET: Rede virtual que atribui os IPs para as VMs

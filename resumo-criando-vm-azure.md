## Resumo lab "Criando máquinas Virtuais na Azure"

- definir qual SLA (tempo de indisponibilidade) adequado para a solução;

- definir zonas de disponibilidade, a Azure cria uma máquina para cada zona e a partir de 3 zonas sugere outra estratégia para criação da VM;

- definir conta de armazenamento: relacionado a forma de redundância do armazenamento, impacta no SLA e nos custos.
  - LRS: Armazenamento com redundância local (baixo custo, porteção baixa contra falhas de drive, cenários não críticos)
  - GRS: Armazenamento com redundância geográfica (custo médio, opção intermediária, funcionalidade failover em uma região secundária, cenários de backup)
  - ZRS: Armazenamento com redundânciade zona (custo médio, opção intermediária, proteção contra falhas no nível do datacenter, cenários de alta disponibilidade)
  - GZRS: Armazenamento com redundância de zona geográfica (alto custo, solução completa, redundância de zona e replicação geográfica contra interrupções, cenários de alta performance e disponibilidade)

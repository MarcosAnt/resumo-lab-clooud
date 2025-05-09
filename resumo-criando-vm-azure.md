## Quiz
- Ao adotarmos a nuvem pública podemos adaptar nossos sistemas para que os mesmos atendam as requisições externas com agilidade e rapidez. Qual vantagem da nuvem atende a esta expectativa?
  - Elasticidade

- Gerenciar o seu ambiente de nuvem por meio do Portal ou linha de comando remete a qual benefício da nuvem?
  - Gerenciabilidade

- A nuvem pública é um ambiente que garante determinados tempos de atividade conforme o tipo de serviço, essa garantia é chamada de:
  - SLA

- A capacidade de adicionar recursos para lidar com o aumento da demanda de consumo para atender uma necessidade especifica é chamado de:
  - Escalabilidade

<br>

## Resumo lab "Criando máquinas Virtuais na Azure"

- definir qual SLA (tempo de indisponibilidade) adequado para a solução;

- definir zonas de disponibilidade, a Azure cria uma máquina para cada zona e a partir de 3 zonas sugere outra estratégia para criação da VM;

- definir conta de armazenamento: relacionado a forma de redundância do armazenamento, impacta no SLA e nos custos.
  - LRS: Armazenamento com redundância local (baixo custo, porteção baixa contra falhas de drive, cenários não críticos)
  - GRS: Armazenamento com redundância geográfica (custo médio, opção intermediária, funcionalidade failover em uma região secundária, cenários de backup)
  - ZRS: Armazenamento com redundânciade zona (custo médio, opção intermediária, proteção contra falhas no nível do datacenter, cenários de alta disponibilidade)
  - GZRS: Armazenamento com redundância de zona geográfica (alto custo, solução completa, redundância de zona e replicação geográfica contra interrupções, cenários de alta performance e disponibilidade)

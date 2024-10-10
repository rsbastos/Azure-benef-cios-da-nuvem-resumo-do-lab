# Azure-benefícios-da-nuvem-resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab "Benefícios da Nuvem" na DIO

### Tópicos Abordados no LAB:

- SLA (Server Level Agreement):
  - Explicação da tabela de disponibilidade dos serviços, que mostra os valores "aceitáveis" relativos ao tempo de inatividade por semana, mês e ano. Os modelos de SLA contratados por serviço variam de 99% a 99,999% de garantia de disponibilidade. Apenas como comparação, uma SLA de 99% garante que os serviços não ficarão indisponíves por mais do que 1,68 horas por semana (7,2 horas/mês - 3,65 dias/ano) ao passo que o máximo de SLA, que corresponde a 99,999%, garante que esses serviços não fiquem indisponíveis por mais do que 6 segundos por semana (25,9 segundos/mês - 5,26 minutos/ano). Ocorrendo indisponibilidade superior ao SLA contratado, a microsoft deve ressarcir os clientes mediante créditos equivalentes.

- MÁQUINAS VIRTUAIS:
  - Utilização da categoria de VMs para explicar sobre como encontrar informações relativas a determinado serviço quando da criação do mesmo. Os serviços e suas opções de configuração, contam com informações (que podem ser visualizadas ao passar o mouse sobre o campo "i") e alguns contém um atalho através do link "saiba mais", que leva direto à documentação da plataforma, auxiliando a entender como contratar/configurar determinado serviço.

- CONTA DE ARMAZENAMENTO:
  - Explicação sobre as opções de "armazenamento com redundância", onde temos a LRS(armazenamento com redundância local), GRS(armazenamento com redundância geográfica), ZRS(armazenamento com redundância de zona) e GZRS (armazenamento com redundância de zona geográfica). Quanto maior a zona de redundância, maior o número de servidores de armazenamento, sendo a LRS (LOCAL) a menor. A redundância afeta também o SLA contratado: quanto mais servidores de armazenamento maior a disponibilidsade garantida pela microsoft. Pelo mesmo motivo, a redundância também influenciará na velocidade de execução dos serviços, proporcionalmente à disponibilidade dos mesmos.

- CUSTOS X NECESSIDADE:
  - Uma ressalva importante abordada, foi sobre estudarmos a real necessidade antes de escolhermos a disponibilidade dos serviços, pois quanto maior a SLA ou Zona de Redundância, maior serão também os custos envolvidos na contratação. Deve-se verificar sobre a imprescindibilidade de termos um determinado serviço rodando 99,999% do tempo, sob o risco de pagarmos um alto valor por algo desnecessário.   

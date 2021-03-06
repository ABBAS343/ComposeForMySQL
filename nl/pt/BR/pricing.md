---

copyright:
  years: 2016,2018
lastupdated: "2018-01-03"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Preços
{: #pricing}

## Configuração base
Um serviço {{site.data.keyword.composeForMySQL_full}} começa com três nós de dados, cada um com 1 GB de armazenamento e 102 MB de memória, que é igual a 1 unidade de recursos. O serviço _inclui_ replicação e alta disponibilidade, de maneira que cada unidade e o preço por unidade _inclua_ o custo dos recursos em todos os três nós. 

Também estão inclusos dois portais HAProxy, cada um com 64 MB de memória para gerenciar a autenticação, HTTPS e a lista de aplicativos confiáveis IP.

### Total
A configuração de serviço de base tem um preço definido. Consulte o ladrilho de catálogo no {{site.data.keyword.cloud_notm}} para precificação base em sua moeda local. Por exemplo, o preço base em dólares americanos é $18/mês.

## Opções de expansão
Se você precisar de armazenamento ou memória adicional para o seu serviço, será possível aumentar os recursos alocados em uma razão 10:1 de armazenamento em disco para unidade de memória. Aumentar o disco alocado para a implementação também aumentará a RAM alocada. Uma unidade do {{site.data.keyword.composeForMySQL}} consiste em 1 GB de armazenamento e 102 MB de memória e cada unidade e o preço por unidade _incluem_ o custo para aumentar os recursos em todos os três nós.

### Total
Cada unidade adicional (1 GB de armazenamento/102 MB de memória) tem um preço unitário, que é listado em sua moeda local no ladrilho de catálogo do {{site.data.keyword.cloud_notm}} para o serviço. Em dólares americanos cada unidade adicional custa $18. Conforme o tamanho _total_ de todos os serviços do {{site.data.keyword.composeForMySQL}} aumenta, o preço por unidade diminui, conforme mostrado na tabela de precificação em camadas, abaixo.

### Precificação em camadas
Número de unidades|Preço por unidade
----------|-----------
1 - 9 unidades|preço base por unidade -- US$18,00/Unidade
10 - 24 unidades|10% redução -- US$16,20/Unidade
25 - 49 unidades|20% redução -- US$14,40/Unidade
50 - 99 unidades|30% redução -- US$12,60/Unidade
100 - 499 unidades|40% redução -- US$10,80/Unidade
500 - 999 unidades|50% redução -- US$9,00/Unidade
1.000 - 4.999 unidades|60% redução -- US$7,20/Unidade
+ de 5.000 unidades|70% redução -- US$5,40/Unidade
{: caption="Tabela 1. Precificação em camadas do {{site.data.keyword.composeForMySQL}}" caption-side="top"}

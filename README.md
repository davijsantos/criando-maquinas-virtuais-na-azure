# Criando máquinas virtuais no Azure

Este projeto é um demonstrativo de como criar máquinas virtuais na Azure e contas de armazenamento

## Definindo a opção de disponibilidade

São 3 opções de disponibilidade, cujas diferenças são:
1. Zona de disponbilidade - redundância de infraestrutura de ordem física e lógica 
3. Conjuntos de dimensionamento de máquinas virtuais - número elástico de VMs com balanceamento de carga
4. Conjuntos de disponibilidade - Agrupameto lógico de VMs por meio do qual o Azure fornece redundância e disponibilidade para a aplicação hospedada.

![availability_options](https://github.com/user-attachments/assets/d0240037-4d21-4bd0-bda9-5af808e3191b)

## Definindo Zona de Disponibilidade

Zonas de disponibilidade se referem a datacenters separados fisica e logicamente, com infraestruturas independentes. Definir mais de uma zona de disponibilidade para uma VM significa contribuir para a sua alta disponibilidade.

![availability_zone](https://github.com/user-attachments/assets/b35c638a-ff40-4669-b935-06e64b7ebcb2)

## Contas de Armazenamento - Definindo redundância

Neste serviço o Azure fornece redundância para o armazenamento de dados em prevenção a eventos planejados ou inesperados. As opções de redundância definirão os custos e o nível de disponibilidade dos dados.

![storage_account_redundancy](https://github.com/user-attachments/assets/9cc95f3d-6fee-4c90-b6aa-81e497142ff1)

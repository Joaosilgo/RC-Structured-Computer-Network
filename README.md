# RC-Structured-Computer-Network
Simulation of the implementation of a computer network for a company. The project aims to build logical and physical topologies that will determine the devices and their placement within the company, through the plant provided, the network distributions by the different “sectors” of the company through VLANs that will be properly identified, such as the distribution of the ranges of IPs for each VLAN calculated from the website to the support of subnets: http://www.vlsm-calc.net/. A simulation performed on the Packet Tracer will be presented, and finally, a budget that will include the different components used in the construction of the network.


**CURSO DE LICENCIATURA EM**


ENGENHARIA INFORMÁTICA
3 º ANO | 1 º SEMESTRE

# REDES DE COMPUTADORES

## RELATÓRIO - REDE DE COMPUTADORES ESTRUTURADA

Turma: IG


João Gomes | Nº 150221001


Gonçalo Ribeiro | Nº 160221095

Docente:

## Prof. António Joaquim Colaço


Ano Letivo 2018 /2019
Setúbal, 4 de fevereiro de 2019


## Índice


## Introdução


No âmbito da Unidade Curricular de Redes de Computadores, lecionada no 1º

semestre do 3º ano do Curso de Licenciatura em Engenharia Informática da Escola

Superior de Tecnologia de Setúbal do Instituto Politécnico de Setúbal, foi proposta a

realização de um projeto que consiste numa simulação da implementação de uma rede

de computadores para uma empresa denominada empresa XPTO Lda – composta por

consultórios, ginásio, salas de reunião, beauty center e auditório. O presente relatório

visa a descrição dessa mesma rede.


O projeto tem como objetivos a construção de topologias lógicas e físicas que


irão determinar os dispositivos e respetiva colocação dentro da empresa, mediante da

planta fornecida, as distribuições da rede pelos diferentes “setores” da empresa através

de VLANs que serão devidamente identificadas, tal como a distribuição das gamas de IPs

para cada VLAN calculadas a partir do site ao apoio de sub-redes: [http://www.vlsm-](http://www.vlsm-calc.net/)

.


Será apresentada ainda uma simulação realizada no Packet Tracer e por fim, um

orçamento que irá englobar os diferentes componentes utilizados na construção da

rede.


## 1. Descrição Geral da Rede

A rede a ser desenvolvida tem como objetivo suportar os colaboradores da

empresa ( 20 ) bem como os equipamentos associados ao bom funcionamento da

empresa. Durante o planeamento da rede foram definidas as seguintes premissas:

- Um posto de trabalho engloba sempre o telefone VOIP e um computador.
- O número de tomadas irá ao encontro ao número de postos de trabalho


de uma sala contento uma folga.

Para o bom planeamento da rede foi fornecida uma planta que se encontra

descrita tanto na topologia física tal como num ficheiro em anexo. Na planta encontram-

se 15 salas (descritas na Tabela 1) tal como os respetivos postos de trabalho, tomadas

duplas e portas ligadas aos _switches (Tabela 2)_.






## 2. Justificação das VLANs


De modo a construir uma rede estruturada, os diferentes setores da empresa

foram separados por diferentes VLANs (Tabela 3 ) e cada VLAN distribuída por

determinados Setores (Tabela 4).





## 3. Topologia Lógica


De forma a estruturar corretamente uma rede de computadores é necessária

uma topologia lógica. A topologia lógica tem como objetivo a representação

esquemática das ligações entre os diferentes dispositivos que compõem a rede.


Nesta topologia foi definido um router (RT1) que estabelece a ligação entre a rede

exterior e os diferentes dipositivos da rede interior da empresa e também do Router da

sucursal (RT2). De modo a distribuir a rede por todos os dispositivos da sede XPTO foi

estabelecida a necessidade de 3 _switches_ de 24 portas sendo os _switches_ SW1, SW 2 e

SW3. Os _switches_ encontram-se ligados por cabos cruzados sendo que o _SW1_ que realiza

a ligação ao router (RT1) , conecta-se através de cabo direto (Imagem1).


![alt text](/Proj_Redes/Imagens/Topologia Logica.png?sanitize=true "IPS logo")


Imagem 1 – Topologia Lógica.


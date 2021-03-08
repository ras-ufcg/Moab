## Descrição
Este é um projeto com o objetivo de implementar um sistema que permite equilibrar uma bola sobre uma plataforma, a qual possui a liberdade de inclinar-se sobre dois eixos, possibilitando realizar os movimentos sobre a bola. Em princípio, a bola deve retornar ao centro da plataforma, sem deixa-la cair, independente de perturbações externas e internas.

## Inspirações
O projeto possuem duas inspirações diretas, uma é no PROJETO MOAB, da Microsoft, no qual consiste em um kit de hardware de ensino de máquina para sistemas autônomos da Microsoft.

A outra inspiração é o BABOT, criado pelo estudante Johan Link do Instituto Federal Suíço de Tecnologia de Lausanne. 

## Planejamento
No primeiro momento será seguindo os passos documentados pelo Johan, na documentação do seu projeto. Por isso, será implementado uma estrutura física com o mesmo designer, caracteristicas e especificções de hardware e método de controle disponibilizados.

Em um segunda etapa é objetivado a implementação mais semelahnte com o Projeto Moab da Microsoft, mas mantendo a mesma estrutura. Isto é, realizar a modelagem, implementar no Simulink, enviar para a plataforma Bonsai para realizar o treianmento do cérebro e aplicar.

## Métodologia
Visando uma melhor divisão de tarefas e possibilitando um paralelismo das atividades a equipe foi dividida em três áreas: Hardware, Visão e Controle.
* Hardware - responsáveis por todo o desenvolvimento da estrutura física, isto é, estarão pesquisando local para realizar as impressões das peças em 3D e resolvendo qualquer problema que surgir. Além disso, analisaram, simularão e implementaram o circuito eletrônico, somente assim finalizando com a montagem final da estrutura. 
* Visão - tem como objetivo estudar os métodos que serão utilizados para identificação dos obejtos de interesse, por exemplo, a bola e plataforma por meio de uma câmera. Ademais, estudar e implemenetar meios de comunicar/integrar com a parte de controle.
* Controle -  o controle será feito de duas maneiras, utilziando métodos de controle de malha fechada com um controlador Proporcional, Integral e Derivativo (PID) e a partir de Inteligência Artificial (IA). No momento de implementação utilizando Inteligência Artificial (IA), então essa área estudará os métodos aplicados para realizar o treinamento no Projeto Bonsai, simulador recomendado pela Microsoft  para realizar o treinamento dos modelos, e como exportar o cérebro gerado para ser implementado, assim podendo enviar os comandos para o microcontrolador da estrutrua.

## Equipe
A equipe é formada por cinco membros, apenas graduandos em Engenharia Elétrica na Universidade Federal de Campina Grande (UFCG). Todos são voluntários do Capítulo Estudantil da Sociedade de Robótica e Automação (RAS) do Instituto de Engenheiros Eletricistas e Eletrônicos (IEEE), essa sendo a idealizadora, patrocinadora e criadora do projeto. 


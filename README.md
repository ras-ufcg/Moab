<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=Projeto%20Ativo&color=orange&style=for-the-badge"/>
</p>

## Descrição
O projeto Moab RAS tem como objetivo implementar um sistema que permite equilibrar uma bola sobre uma plataforma, a qual possui a liberdade de inclinar-se sobre dois eixos, possibilitando realizar os movimentos sobre a bola. Inicialmente, a bola deve retornar ao centro da plataforma, sem deixa-la cair, independente de perturbações externas e internas.

- [ENRON](https://edu.ieee.org/br-ufcgras/enron-moab/)

### Palavras-chaves
Plataforma Stewart, Moab, Visão Computacional, PDI

## Inspirações

- [Projeto MOAB - Microsoft](https://microsoft.github.io/moab/)

Este projeto consiste em um kit de hardware de ensino de máquina para sistemas autônomos da Microsoft, que combina controle de movimento, simulação e Microsoft Bonsai.
<p align="center">
<img src = "/Midia/Moab_SoftwareHardware_v01_JS-02.gif?w=512" height="300" width = "700" >
 </p>
 
- [Projeto BABOT - Johan Link](https://www.ba-bot.com/)

O projeto BABOT consiste em um robô de balanceamento DIY que usa visão computacional e um Raspberry Pi para equilibrar uma bola em sua plataforma. 

<p align="center">
<img src = "/Midia/johan.png?w=512" height="200" width = "400" >
</p>

## Metodologia
Para uma melhor dinâmica de desenvolvimento, o projto é subdividido em três áreas principais:

* Hardware - Responsável pelo desenvolvimento da estrutura física, isto é, estarão pesquisando local para realizar as impressões das peças em 3D e resolvendo qualquer problema que surgir. Além disso, analisaram, simularão e implementaram o circuito eletrônico, somente assim finalizando com a montagem final da estrutura. 
* Visão - tem como objetivo estudar os métodos que serão utilizados para identificação dos obejtos de interesse, por exemplo, a bola e plataforma por meio de uma câmera. Ademais, estudar e implemenetar meios de comunicar/integrar com a parte de controle.
* Controle -  o controle será feito de duas maneiras, utilziando métodos de controle de malha fechada com um controlador Proporcional, Integral e Derivativo (PID) e a partir de Inteligência Artificial (IA). No momento de implementação utilizando IA, então essa área estudará os métodos aplicados para realizar o treinamento no Projeto Bonsai, simulador recomendado pela Microsoft  para realizar o treinamento dos modelos, e como exportar o cérebro gerado para ser implementado, assim podendo enviar os comandos para o microcontrolador da estrutrua.

## Planejamento
No primeiro momento será seguindo os passos documentados pelo Johan, na documentação do seu projeto. Por isso, será implementado uma estrutura física com o mesmo designer, caracteristicas e especificções de hardware e método de controle disponibilizados.

Em um segunda etapa é objetivado a implementação mais semelhante com o Projeto Moab da Microsoft, mas mantendo a mesma estrutura. Por meio da utilização de Python se comunicar com plataforma Bonsai para realizar o treianmento do cérebro e aplica-lo.

#### Status do projeto

| #        | Capítulo          | _Status_ |
|:--|:----------------------------|:------------------|
| 1 | Introdução Geral            | <img alt="Finalizado" src="https://img.shields.io/badge/-Finalizado-brightgreen">| 
| 2 | Desenvolvimento de PCB      | <img alt="Andamento" src="https://img.shields.io/badge/-Andamento-yellow"> |  
| 3 | Controle dos Motores        |  |  
| 4 | Documentação                |  |  


## Equipe
A equipe atual é formada por graduandos em Engenharia Elétrica na Universidade Federal de Campina Grande (UFCG), ao qual todos são voluntários do Capítulo Estudantil da Sociedade de Robótica e Automação (IEEE RAS UFCG).

- [Breno Meneses](https://github.com/brenopmeneses)
- [Gabriel Henrique](https://github.com/gabrielhvs)
- [Larissa Teixeira](https://github.com/lateixeiraa)
- [Lucas Lobo](https://github.com/LucasLobo7)
- [Maria Eduarda](https://github.com/MariaEduarda358)


<h4 align="center"> 
	🚧  Readme em construção...  🚧
</h4>

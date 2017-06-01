##O mundo wumpus

O mundo wumpus é uma caverna que consiste de salas conectadas por passagens. À espreita em algum lugar da taverna está o wumpus, um monstro fétido devorador de arqueiros agentes inteligentes que invadem a sua sala. O wumpus pode ser morto pelo agente, mas este só tem uma flecha!

Algumas salas contém buracos sem fundo, nos quais cairá qualquer um que vagar por ele (com exceção do wumpus, que é muito grande para cair no buraco).

Opcionalmente, salas podem ter super-morcegos, que jogam o agente para alguma casa aleatória.

Nos há também uma vantagem: em algum lugar há um (ou mais) monte de ouro.

Este é um excelente ambiente para teste de programação lógica.

#### Regras lógicas

* O agente tem uma única flecha, e começa olhando para a direita.

* O agente tem orientações de 0(dir), 90(cim), 180(esq), e 270(bai) graus.

* O fedor do wumpus pode ser detectado de qualquer casa não-diagonal adjacente a ele.

* A brisa dos buracos sem fundo pode ser detectada da mesma forma.

* O mesmo vale para o farfalhar das asas dos morcegos.

#### O funcionamento

Existem dois programas: o wumpus.pl e o agente00X.pl. O programa wumpus é inalterável, e se comunica com o agente mandando percepções. O agente, por sua vez, se comunica com o wumpus mandando ações. 




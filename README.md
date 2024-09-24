# Problema de roteamento com capacidade limitada 
Desenvolvimento de um algoritmo em python capaz de obter o número de camiões necessários, sequência de rotas a percorrer e custo de cada rota, tendo por base todos os custos envolvidos no processo (meios de transporte, motoristas, etc), janelas temporais e velocidades de cada meio de transporte.<br /><br />

Este projeto baseou-se na obtenção de rotas e otimização do número de camiões e motoristas tendo a utilizar diariamente, tendo por base:
-	todos os custos fixos e variáveis inerentes a este meio de transporte (licenças, seguros, depreciações, pessoal, combustível, pessoas e manutenções);
-	as velocidades relativas a estradas Nacionais (50 Km/h) e/ou Autoestradas(75 km/h); 
-	horários de motoristas; 
-	janelas temporais de entrega das mercadorias;
-	limitação das capacidades dos camiões (26 e 40 Ton);
-	pesos de cada mercadoria;
-	número e localidades dos clientes.<br /><br />

Por sua vez, este trabalho foi desenvolvido em programação python de forma a ser possível obter as rotas pretendidas para satisfazer cada cliente (associada ao número de camiões), as horas de partida e chegada a cada cliente, como também a distância percorrida e custo total por rota (figura 1).<br />
A este ponto é importante referir que a empresa se encontra funcional entre as 8h e 20h com possibilidade de os motoristas iniciarem a sua rota às 4h, como também se considerou para cada carga e descarga uma duração de 40 min.<br /><br />


<p align="center">
  <img src="https://github.com/nunogabriel11/gerador_rotas_cap_limitada/blob/main/imgs/result_code.PNG?raw=true" width="90%" />
</p>


<p align="center">
<i>Figura 1: Imagem ilustrativa, da solução obtida, para camiões de 26 Ton a 75 Km/h (Autoestrada)</i>
</p><br /><br />


O código em questão encontra-se otimizado de forma a o utilizador a possibilitar o utilizador a introduzir a velocidade pretendida, podendo, deste modo, encontrar um meio termo em caso de análise de rotas para uma mistura entre estradas Nacionais e Autoestradas.
O número de motorista foi obtido separadamente de forma a ter uma análise mais profunda e considerar as horas de trajeto e descanso permitidas, como analisar a vertente de implementação de um segundo motorista Vs custo obtido.<br />
Por último, recorreu-se á funcionalidade “3D Maps” do Excel de maneira a ser possível obter uma perspetiva visual de cada rota a realizar, como se pode observar de seguida.<br /><br />






<p align="center">
  <img src="https://github.com/nunogabriel11/gerador_rotas_cap_limitada/blob/main/imgs/map.png?raw=true" width="200" />
</p>


<p align="center">
<i>Figura 2: Imagem ilustrativa de cada rota a realizar pelos camionistas</i>
</p><br />

Objetivo: Em python, implementar uma rede de Sensores sendo monitorados através de um Broker de
mensagens
1) Deve ser possível instanciar diversos equipamentos com sensores, sendo que cada
equipamento deve ter apenas um sensor.
2) Deve ser definido um parâmetro a ser gerado pelos sensores (pressão, temperatura,
umidade, velocidade, etc.)
3) Deve ser possível definir limites máximo e mínimo para o parâmetro
4) Deve ser possível ligar e desligar o equipamento
5) Ao ser ligado, o sensor gera valores aleatórios para o seu parâmetro, dentro da faixa de
valores permitidos
6) Deve ser criado um tópico no Broker para cada equipamento
7) Se um valor gerado for maior ou igual ao máximo, ou menor ou igual ao mínimo, o
sensor deve enviar uma mensagem para o Broker para o respectivo tópico relativo ao
equipamento monitorado.
8) Um Gerenciador de Equipamentos (GE) deve ser criado para monitorar os equipamentos
e seus sensores
9) O GE deve apresentar os equipamentos disponíveis para gerenciamento consultando os
tópicos que estão no Broker
10) Para cada equipamento, devem ser apresentador os alarmes gerados pelos respectivos
sensores.

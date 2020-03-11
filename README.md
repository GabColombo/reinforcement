# reinforcement

## tf-agents

Neste repositório está o código tutorial traduzido de [Tutorial tf-agents](https://github.com/tensorflow/agents/blob/master/docs/tutorials/1_dqn_tutorial.ipynb), responsável por dar uma introdução à biblioteca tf-agents: [tutorial](https://github.com/GabColombo/reinforcement/blob/master/tf_agent_DQN_CartPole.ipynb)

## Ambientes

### CarRacing-v0

Aqui também está disponibilizado o ambiente [CarRacing-v0](https://github.com/GabColombo/reinforcement/blob/master/car_racing.py), com algumas pequenas modificações do ambientes original. No ambiente original, as ações são contínuas, dificultando o treinamento. Para resolver este problema, as ações foram limitadas à 5 possibilidades: 

Ação            | Valor
----------------|-------
Virar à esquerda| 0
Virar à direita | 1
Frear           | 2
Acelerar        | 3
Nenhuma ação    | 4

A opção 'nenhuma ação' é necessária para que o carro continue executando a ação atual.

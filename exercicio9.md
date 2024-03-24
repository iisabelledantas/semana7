**9)** Você foi contratado(a) como estagiário(a) da Tesla e está participando do desenvolvimento de um programa para simular o desempenho de um carro elétrico em uma corrida. Seu objetivo é determinar em quantos minutos o carro levará para completar uma determinada distância, levando em consideração uma velocidade inicial e uma taxa de aceleração constante. No entanto, você deseja garantir que o carro não exceda uma velocidade máxima nem que a corrida demore mais do que um tempo máximo. Implemente a lógica dessa simulação em pseudocódigo.

Considere a fórumla de atualização velocidade:
```
    velocidade = velocidadeInicial + aceleracao*tempo
```

______

 ### Segue a resposta:

```
função simularCorrida (distancia, velocidadeInicial, aceleracao, velocidadeMaxima,tempoMaximo) {

    definir tempo = 0 
    definir velocidadeInicial = 0 
    definir aceleração = 10 
    definir tempoMaximo = 20

    paea (definir tempo = 0 ; tempo <= tempoMaximo; tempo = tempo + 1) {

        se (velocidade < velocidadeMaxima) {
        velocidade = velocidadeInicial + aceleracao*tempo
        retornar velocidade
        }
    }
    distancia = velocidade * tempo
}



# Contagem de pressionamentos de botão.
Para contar o número de pressionamentos de botão, você precisa descobrir quantas vezes o estado do botão muda de desligado para ligado.

## 


## Explicação do programa
O programa compara o estado atual do botão com o seu estado da última vez no loop principal. Se o estado atual do botão diferir do último estado e for igual a HIGH, a contagem de cliques do botão será incrementada e as informações serão enviadas ao Serial Monitor.

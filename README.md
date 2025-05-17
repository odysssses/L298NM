# Instalação
* Primeiramente, baixe o arquivo .zip daqui do github
* Então, no arduino IDE, vá em **Sketch > Incluir biblioteca > Adicionar biblioteca .ZIP**
* Isso abrirá uma tela para selecionar um arquivo, vá até a pasta em que baixou essa biblioteca e clique duas vezes.
* Enfim, no topo do seu código, copie essa linha `#include <L298NM.h>`

(Alternativamente, você pode extrair o .zip e colocar a pasta "L298NM" dentro do diretório libraries do arduino) 

# Funções
## Construtor
Cria uma instância como um objeto no C++ da ponte L298N com os pinos, pedindo o IN1, IN2, IN3 e IN4.

`L298NM [nome](IN1, IN2, IN3, IN4)`
## begin
Inicializa os pinos dados no construtor

`[nome].begin()`
## forward
Faz o robô andar para frente

`[nome].forward(velocidade)`

Dica: Para fazer o robô por determinado tempo, use a função builtin `delay(tempo)` após essa função. Isso vale para todas as próximas funções
## backward
Faz o robô andar para trás

`[nome].backward(velocidade)`
## turnLeft
Faz o robô virar para a esquerda

`[nome].turnLeft(velocidade)`
## turnRight
Faz o robô virar para a direita

`[nome].turnRight(velocidade)`
## stop
Faz o robô parar

`[nome].stop`

## O que é Equidade?
- Equidade é a probabilidade de uma mão vencer no Showdown, dado um determinado range de mãos adversário e as cartas comunitárias. Pode ser expressa como percentual (ex. : minha equidade é de 65% contra esse range).
- A grosso modo, a equidade é a probabilidade de você ganhar: "Se essa mão rodasse milhões de vezes, quantas eu ganharia?"
## O que são Ranges?
Basicamente, é o conjunto de mãos que o jogador pode ter em determinada situação.

*Os ranges foram discutidos em maior detalhe no documento **Ranges de Mãos por Posição (Intermediário)***
## Onde os dois se conectam?
Você sempre joga contra um range, não uma mão. Por isso, a equidade precisa ser calculada contra o range inteiro, não só uma mão. 
Algumas ferramentas podem ajudar nessa tarefa, como o Equilab, FlopZilla e o PioSolver. Elas servem para:
- Definir um range adversário
- Calcular sua equidade contra ele
- Tomar decisões +EV
Entender esse conceito é importante, pois é necessário saber a força matemática da sua mão contra o range do adversário. Assim, você pode tomar decisões com embasamento lógico, e não em *feelings*.
## Como fazer isso ao vivo?
Apesar dessas ferramentas serem boas para te dar informações precisas sobre a partida, ao vivo você não pode usá-las para jogar. Então como comparar sua equidade contra o range do vilão **de cabeça**?
### 1. Identifique o range do vilão
- Como detalhado no documento **Ranges de Mãos por Posição (Intermediário)**, podemos deduzir qual range o vilão possui pela sua posição e ações no jogo.
### 2. Avalie sua mão contra esse range (Deduzir a equidade)
- Está a frente da maior parte do range? **Boa equidade**.
- Só ganha de blefes ou mãos muito específicas? **Equidade baixa**.
- Tem draws ou chances de melhorar? **Pode calcular seus outs (próximo passo)**.
### 3. Método dos *outs* para estimar a equidade
Você pode usar a regra do 2 e 4, usada para calcular odds, para estimar a equidade.
- **No turn**: multiplique os outs por 2
- **No flop**: multiplique os outs por 4
As odds que você chegar podem ser consideradas uma estimativa da sua equidade. Ainda assim, não esqueça que essa regra vai estimar somente a chance de você acertar sua mão, mas não compara com o range.
### 4. Compare equidade vs. Pot Odds
- Se o pote tem 100 e o vilão aposta 50:
	- Você precisa pagar 50 para um pote de 150 -> 33% de pot odds
- Agora compare:
	- Se você acha que tem mais de 33% de equidade, o call é +EV.
	- Se tem menos, é melhor largar.
### 5. Concluindo
- *Sempre pense em ranges, não em mãos*
Na prática, fazer essa análise requer prática para garantir uma intuição rápida. Esse método vai te ajudar a garantir jogadas melhores, mas ainda assim, não é totalmente preciso como a análise de um software. Treinar o cálculo de sua equidade contra o range do vilão requer prática, boa intuição de ranges, e cálculo rápido de outs e pot odds.
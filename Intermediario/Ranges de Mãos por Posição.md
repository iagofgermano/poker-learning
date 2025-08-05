# O que são Ranges?
São os conjuntos de mãos iniciais que um jogador deve jogar a partir de cada posição da mesa. 
- Quanto mais longe do Dealer, mais jogadores vão agir depois de você, e isso aumenta o risco de ser enfrentado por uma mão melhor. Por isso:
	- Posições iniciais (UTG, UTG+1) exigem ranges mais *tight* (seletivos).
	- Posições finais (cutoff, button) permitem ranges mais *loose* (mais mãos jogáveis).

| Posição | Range aproximado                                   | % de mãos jogadas |
| ------- | -------------------------------------------------- | ----------------- |
| UTG     | AA–22, AK–AQs                                      | ~15%              |
| MP      | AA–22, AK–ATs, AJo+                                | ~20%              |
| CO      | AA–22, Axs, ATo+, KQo, suited connectors           | ~25%              |
| BTN     | Muito mais amplo: qualquer par, Ax, Kx, conectores | ~45–55%           |
| SB      | Bem amplo contra BB, mas depende do plano de jogo  |                   |
| BB      | Depende da ação anterior (defesa, 3-bet, etc.)     |                   |

# Dinâmica dos ranges
- É a forma como os ranges mudam ao longo da mão com base nas ações e cartas da mesa
- Ex. :
	- Quando alguém da raise em UTG, assumimos range *tight*.
	- Se alguém dá call no BTN, o range dele costuma ser mais amplo e com mais mãos especulativas.
	- No flop, certas cartas atingem melhor alguns ranges que outros.
	- Situações como essas geram uma batalha de ranges.
## Como os ranges mudam por ação?
1. Pré-flop
	- Cada posição tem um range diferente (+*tight* no começo, +*loose* no final).
	- Quem dá raise representa uma faixa mais forte.
	- Quem dá call normalmente tem mãos que não são boas o suficiente para 3-bet, mas querem ver o flop.
2. Flop/Turn/River
	- As ações anteriores e as cartas comunitárias vão "filtrar" os ranges.
	- Ex. : Um flop A♠ 9♣ 2♦ acerta muito o range de quem deu raise pré-flop (Porque ele tem muitos A♠x), mas não tanto o de quem pagou.
3. Agressividade reduz o range
	- Quando alguém dá 3-bet ou dá check-raise, o range dele fica mais forte ("polarizado": muito forte ou blefe).
	- A cada ação agressiva, você pode eliminar certos ranges da mão do vilão.
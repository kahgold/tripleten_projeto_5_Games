# Projeto: Games

*Você trabalha para a loja online Ice, que vende videogames no mundo todo. As avaliações de usuários e especialistas, gêneros, plataformas (por exemplo, Xbox ou PlayStation) e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. Você precisa identificar padrões que determinam se um jogo tem sucesso ou não. Isso permitirá que você identifique potenciais grandes vencedores e planeje campanhas publicitárias.*

*Na sua frente estão dados que remontam a 2016. Vamos imaginar que estamos em dezembro de 2016 e você está planejando uma campanha para 2017. (O importante é ter experiência trabalhando com dados. Realmente não importa se você está prevendo as vendas de 2017 com base nos dados de 2016 ou as vendas de 2027 com base nos dados de 2026.) O conjunto de dados contém a abreviatura ESRB. O Entertainment Software Rating Board avalia o conteúdo de um jogo e atribui uma classificação etária, como Adolescente ou Maduro.*

*Aqui, algumas  perguntas que responderemos com base em dados estatísticos, gráficos e testes de hipóteses:* 

- *Qual é o ciclo de vida de um jogo?*
- *Como podemos descobrir quais jogos geraram mais receita?*
- *Quais jogos receberam mais avaliações?*
- *Como as avaliações dos usuários e da crítica influenciam nas vendas?*

*Prepare-se para uma emocionante jornada  de análise e descoberta de dados à medida que exploramos o mundo dos jogos, jogue e responda a essas perguntas e muito mais!!*

**Dicionário de dados**
**A tabela games (dados sobre jogos):**
- `Name` — (nome) — tipo object
- `Platform` — (plataforma) — tipo object
- `Year_of_Release` — (Ano de lançamento) — tipo float64
- `Genre` — (gênero) — tipo object
- `NA_sales` — (vendas norte-americanas em milhões de USD) — tipo float64
- `EU_sales` — (vendas na Europa em milhões de USD) — tipo float64
- `JP_sales` — (vendas no Japão em milhões de USD) — tipo float64
- `Other_sales` — (vendas em outros países em em milhões de USD) — tipo float64
- `Critic_Score` — (Pontuação crítica) (máximo de 100) — tipo float64
- `User_Score` — (Pontuação do usuário) (máximo de 10) — tipo object
- `Classificação` — (ESRB) — tipo object

**Teste as seguintes hipóteses**
- As classificações médias de usuários para as plataformas Xbox One e PC são as mesmas.
- As classificações médias de usuários para os gêneros Ação e Esportes são diferentes.

**Conclusão**

De tudo o que foi analisado, podemos ver alguns padrões de sucesso nos jogos. Padrões como ser do gênero de ação, esportes ou tiro em NA e EU, em relação à classificação, preferir E ou Mature e deve ser lançado nas plataformas mais novas, como PS4 e XboxOne, que são as que mais vendem. Mas fique de olho nas plataformas de PC, que estão vivas no mercado há muito tempo, no WiiU, que pode lançar um novo jogo se morrer, e no 3DS, que não vende muito, mas ainda está vivo. No Japão a história é diferente, lá você deve ficar de olho em jogos com classificação E ou T e principalmente no gênero RPG seguido de ação e plataforma, entre as plataformas vivas você deve priorizar 3DS, wiiU, PS4, XboxOne e Pc nessa ordem.

Sempre prefira o PlayStation ao Xbox em qualquer grupo, pois ele vende mais. Fique de olho nas plataformas PS4, XboxOne, WiiU e 3ds quando lançarem novas plataformas, pois nos primeiros anos elas costumam aumentar as vendas de jogos. Em resumo, um jogo de sucesso nos EUA ou em NA seria um jogo de ação para PS4 com classificação E. No Japão, um jogo de RPG com classificação E na plataforma 3DS.

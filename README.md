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

*Chegamos ao final do processo de análise de dados e obtivemos insights valiosos. Processamos um grande DataFrame cheio de valores faltantes e adotamos uma abordagem focada na visualização, buscando ir além dos números para representar graficamente o jogo, a plataforma e o comportamento do jogador, uso e vendas, bem como o ciclo de vida do jogo.*

***Destacamos alguns pontos-chave:***
- Exploramos a frequência de palavras em nomes de jogos, revelando que muitos jogos recebem uma segunda edição (II).
- `Need for Speed Most Wanted`, um jogo do gênero de corrida, liderou em termos de lançamentos em várias plataformas.
- As plataformas `PS2` e `DS` (portátil) receberam a maioria dos jogos em nosso DataFrame.
- Nossa análise abrangeu dados de 1980 a 2016, com um pico de lançamentos de jogos em 2010.
- Jogos dos gêneros `Action` e `Sports` receberam mais lançamentos.
- Observamos grandes diferenças entre os mercados da América do Norte, Japão e Europa em termos de preferências de gênero e plataformas.
- O mercado japonês tem uma forte preferência por plataformas portáteis.
- Gêneros de `Puzzle` e `Strategy` são os menos lucrativos.
- Notamos o impacto das avaliações profissionais nas vendas, destacando a importância de acompanhar análises de revistas e sites especializados.
- Nem todas as regiões classificam jogos por faixa etária ou têm o hábito de avaliá-los.
- As avaliações mais altas, dadas por profissionais, são para jogos dos gêneros `Shooter` e `Racing`, indicando um mercado a ser explorado.
- A partir de 1995, houve um aumento significativo no lançamento de jogos, seguido por uma desaceleração a partir de 2010.
- As vendas totais variam de plataforma para plataforma, sugerindo a necessidade de uma estratégia personalizada para cada mercado.
- As principais plataformas de vendas, como `PS3` e `X360`, estão se aproximando do fim de suas vidas úteis, indicando que é melhor investir em suas novas edições, ou seja, `PS4` e `XOne`.
- Os usuários na América do Norte preferem plataformas da `Microsoft` e `Sony`, enquanto os europeus jogam com bastante regularidade em computadores (`PC`), além das plataformas mencionadas.
- O gênero de `Action` é o preferido nos três mercados mencionados.

***Realizamos dois testes de hipótese, destacando que estatisticamente as classificações médias dos usuários para as plataformas `Xbox One` e `PC` são iguais, enquanto as médias das avaliações de usuários para os gêneros `Action` e `Sports` são estatisticamente diferentes.***

**Essas descobertas fornecem insights valiosos para orientar decisões e estratégias no mercado de jogos!**

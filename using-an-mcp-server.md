# Using an MCP server

Trym Fjørtoft Fjellstad. Session 2, part 2 of "Agentic AI for business economists". Written 2026-11-02 and 2026-11-03.

## 1. What an MCP server is, and why I trust mst0441

MCP er en server som kan koble AI-assistenten opp til ting jeg har gitt tilgang til, som filer og databaser med informasjon. Jeg stoler på MST0441 fordi det er Andreas som har gitt oss den, så den kommer fra en trygg kilde.

## 2. The new version of workshop 2

My agent (Claude Code) wrote this set with the mst0441 MCP server at https://andreaskostol.no/mcp/mst0441. Topics, weights and level follow the Workshop 2 exam paper of October 26, 2026 (Sessions 8 to 11). The setting and numbers are new. Each problem passed the server's tool mst0441_check_problem. The tool mst0441_verify cannot check the task model in Problem 1.

Five problems, weights in parentheses. 90 minutes.

### Problem 1 (15%)

Fjellheim Regnskap is an accounting firm. Every client file it handles needs four tasks: bookkeeping, payroll, tax filing and client meetings. One worker-hour produces one task-unit of any task and costs w = 500 kroner. The firm can instead rent AI services. One AI-service unit costs r = 1000 kroner and produces A_i task-units in task i:

| Task | AI productivity A_i | Baseline cost share χ_i |
|---|---|---|
| Bookkeeping | 5 | 2/5 |
| Payroll | 2 | 1/5 |
| Tax filing | 4/3 | 1/4 |
| Client meetings | 1/2 | 3/20 |

The cost shares refer to the cost of a fixed batch of client files when every task is done by workers. Quality is the same with either method, and there are no setup costs. When the two methods cost the same, the task stays with workers.

(a) Write the cost of one task-unit with workers and with AI. Derive the cutoff for A_i above which a task goes to AI, in general notation. Find the set of automated tasks at r = 1000, and say what happens to payroll.

(b) Compute the saving π_i on each task and the fixed-weight saving index G = Σ_i χ_i π_i. The fixed batch costs 250 000 kroner when every task is done by workers. How many kroner does the firm save on the batch?

(c) A new AI contract lowers the rental rate to r = 750, with w, A_i and χ_i unchanged. Find the new automated set, the new savings, G and the saving in kroner on the same batch. Split the change in G into the part from the task that was already automated and the part from the newly automated task.

(d) A union representative says: "The firm saves money, so the wages of its accountants must fall." Explain what your results in (b) and (c) can and cannot tell us about the firm's workers and their wages, using a maximum of 4 sentences.

### Problem 2 (12%)

Kaldland and Varmland make two goods, furniture (x) and salmon (y), with labor alone. Labor moves freely between the two industries in a country, but not between countries. The hours of labor needed per unit and the labor forces are:

| | furniture | salmon | labor force |
|---|---|---|---|
| Kaldland | a_x = 3 | a_y = 3 | E = 30 |
| Varmland | a_x* = 2 | a_y* = 1 | E* = 15 |

Consumers in both countries have the utility function u = x^(1/2) y^(1/2), so each country spends half its income on each good. Salmon is the numeraire, p_y = 1, and p = p_x/p_y is the relative price of furniture.

(a) Draw each country's production possibility frontier with furniture on the horizontal axis and salmon on the vertical axis. Give the intercepts and the slope.

(b) Derive the autarky relative price of furniture in each country from the condition that wages in the two industries are equal. Which country has the absolute advantage, and which has the comparative advantage, in each good?

(c) The countries open to free trade. State which good each country produces, and find the world price p that clears the market for furniture. Show that p lies between the two autarky prices. In your figure for Kaldland from (a), mark the production point B and a consumption point C on the trade line.

(d) Find the wage in each country, measured in salmon. Show with unit costs that each country is the cheaper producer of exactly one good. Explain why Kaldland exports furniture although Varmland needs fewer hours to make a piece of furniture, using a maximum of 3 sentences.

### Problem 3 (8%)

An economy makes furniture (good x) and machinery (good y) with labor and capital. Both industries are competitive, so price equals unit cost and profits are zero. One unit of furniture needs 2 units of labor and 1 unit of capital. One unit of machinery needs 1 unit of labor and 2 units of capital. The economy is small and takes world prices as given. Write w for the wage and r for the rental rate of capital.

(a) Rank the two industries by factor intensity. Write the zero-profit conditions and find w and r at p_x = 9 and p_y = 9.

(b) The world price of furniture rises to p_x = 12, while p_y stays at 9. Find the new w and r. Compute the four percentage changes, arrange them in one chain and name the theorem.

(c) Do workers gain or lose in real terms? Do capital owners? Explain why your answer does not depend on whether a person spends most of their income on furniture or on machinery. Maximum 3 sentences.

### Problem 4 (5%)

Vestøya and Austøya are identical countries. In each of them one differentiated industry, craft beer, operates under monopolistic competition: many breweries, each with its own variety, a fixed cost and a constant marginal cost, free entry and exit, and consumers who love variety. No calculation is needed in this problem. Answer in words, within the sentence limits.

(a) (2 points) Before trade, each brewery sets a price above its marginal cost, yet earns zero profit. Explain how both can be true. Maximum 3 sentences.

(b) (3 points) Vestøya and Austøya open to trade with each other. The elasticity of demand is constant. Explain what happens to the price of a bottle, to the output of each brewery, to the number of breweries in Vestøya, and to the number of varieties a consumer in Vestøya can buy. Where does the gain from trade come from? Maximum 5 sentences.

### Problem 5 (10%)

Ten multiple-choice questions on key concepts, one point each. Exactly one answer is correct.

1. The elasticity of substitution between AI and labor is σ = 1/2. AI becomes cheaper relative to labor. Labor's share of the firm's costs
   (a) rises (b) falls (c) stays the same, because σ is below one (d) cannot be signed without the firm's output
2. An occupation has a high AI exposure score, yet a firm keeps every one of its tasks with workers. Which explanation is consistent with the task model?
   (a) the exposure score must be wrong (b) the firm's productivity must have fallen (c) in each of those tasks, the AI cost per task-unit, r/A_i, is at or above the wage w (d) the workers earn less per hour than the AI rental rate r
3. In the Ricardian model with free trade, a country produces at point B on its production possibility frontier. Its consumption point C lies
   (a) at B, on the frontier (b) inside the frontier (c) at the intercept of the frontier on the vertical axis (d) on the trade line through B with slope −p, outside the frontier
4. In the Ricardian model, country A needs fewer hours than country B to make every good. After the two countries open to trade, country A
   (a) exports both goods (b) has the higher wage, and exports the good in which its advantage is largest (c) gains nothing from trade (d) keeps producing both goods
5. In the Heckscher-Ohlin model, the economy's labor force rises while goods prices stay fixed. Then
   (a) the output of the labor-intensive good rises by more than in proportion, and the output of the capital-intensive good falls (b) both outputs rise in proportion to the labor force (c) the wage falls (d) the rental rate of capital rises
6. Leontief compared capital per worker in U.S. exports with capital per worker in U.S. imports. Leamer (1980) argued that, when a country runs a trade surplus, the right test of whether it is capital abundant compares
   (a) capital per worker in exports and imports, as Leontief did (b) wages in the United States and abroad (c) capital per worker embodied in production and in consumption (d) GDP per capita across countries
7. Gravity with unit elasticities, ln X_ij = k + ln Y_i + ln Y_j − ln d_ij. The exporter's GDP doubles, the importer's GDP rises by half, and the distance between them doubles. Predicted trade changes by a factor of
   (a) 6 (b) 3/2 (c) 3 (d) 3/4
8. The same true border friction gives a larger measured border effect for Canada than for the United States, because
   (a) transport costs per kilometre are higher in Canada (b) distance is measured differently in the two countries (c) U.S. states are closer together than Canadian provinces (d) Canada is the smaller economy, so the border cuts off a larger share of its trading opportunities
9. In the monopolistic competition model, trade between two identical countries is
   (a) two-way trade within the same industry, because each country makes its own varieties (b) zero, because the countries have the same technology (c) one-way, from the country with more firms (d) limited to goods in which one country has a comparative advantage
10. The gravity equation fits trade data well across countries and years. This good fit
   (a) proves that the monopolistic competition model is the right model of trade (b) shows that distance does not matter once GDP is controlled for (c) is consistent with any model in which countries specialize, so the fit alone cannot choose between models (d) shows that trade costs are zero

## 3. My own solution, written before the check

Written by hand on 2026-11-03 and typed in as written.

**Problem 1**
(a) Kostnad med arbeidere: w. Kostnad med AI: r/A_i. Oppgaven går til AI hvis A_i > r/w. Bare bookkeeping automatiseres. Ved r = 1000 blir payroll hos arbeiderne.
(b) π_i: bokføring 3/5, payroll 0, skatt 0, client meetings 0. G = 6/25. Besparelse: 60 000 kroner.
(c) Bokføring og payroll automatiseres denne gangen. Nye π_i: bokføring 0,7, payroll 0,25, resten 0. Ny G = 3/100. Ny besparelse: 82 500. Oppsplitting av endringen i G: bokføring 0,04, payroll 0,05.
(d) Besparelsen viser lavere kostnader. Det forklarer ikke om lønn og sysselsetting faller. Bare kostnader.

**Problem 2**
(a) Kaldland: skjæring (10, 0) og (0, 10), helning 1. Varmland: skjæring (7,5, 0) og (0, 15), helning 2.
(b) Autarkipriser: Kaldland p = 1, Varmland p = 2. Absolutt fortrinn: Varmland. Komparativt fortrinn: Kaldland i møbler, Varmland i laks.
(c) Kaldland produserer møbler, Varmland produserer laks. Verdensprisen p = 1,5. p = 1,5 ligger mellom de to autarkiprisene. Kaldland: B = (10, 0), C = (5, 7,5). Handelslinjen går mellom B og C.
(d) Lønn: Kaldland w = 0,5 laks per time, Varmland w = 1 laks per time. Enhetskostnad møbler: Kaldland 1,5, Varmland 2. Enhetskostnad laks: Kaldland 1,5, Varmland 1. Kaldland er billigst på møbler og Varmland på laks. Pga komparative fortrinn produserer Kaldland møbler og Varmland laks.

**Problem 3**
(a) Maskiner er kapitalintensive, og møbler er arbeidsintensive. Nullprofitt: 2w + r = px og w + 2r = py. px = py = 9 gir w = r = 3.
(b) w = 5, r går fra 3 til 2. Prosentendringer: px 33,33 %, py 0 %, w 66,66 %, r −33,33 %. Kjeden: px > w > py > r. Stolper-Samuelson-teoremet.
(c) Arbeidere vinner. Kapitaleiere taper. Begge prisene ligger mellom gammel og ny faktorinntekt, som vil si at det gjelder uansett din preferanse av maskin og møbler.

**Problem 4**
(a) Begge bryggeriene setter prisen over MC. Siden det er fri konkurranse, med fri etablering blir prisene presset ned til der profitten = 0.
(b) Prisen per flaske faller, og bryggeriene produserer mer. Det blir flere bryggerier og flere varianter på Vestøya. Gevinsten her stammer fra stordriftsfordeler.

**Problem 5**
1 a, 2 c, 3 d, 4 b, 5 a, 6 c, 7 b, 8 d, 9 a, 10 c.

## 4. What the check said, and what I changed

My agent checked the solution with the mst0441 server. mst0441_verify checks numbers. The written answers were marked against the server's rubrics.

**Right:**
- Problem 2: all 13 numbers OK in mst0441_verify.
- Problem 3: w and r OK in mst0441_verify.
- Problem 5: 10 of 10.
- Problem 1 was checked by hand by the agent, because the tool cannot check the task model. The faults it found are listed below. Problem 1 has not been checked by a tool.

**Wrong or weak:**
- 1(c): G written as 3/100.
- 1(d): named the point without explaining it.
- 2(a): the slopes had no minus sign.
- 2(c): the trade line's slope and why C matters were missing.
- 2(d): "komparative fortrinn" does not explain why Kaldland is the cheaper producer of furniture.
- 3(b): the chain was in the wrong order.
- 3(c): did not say plainly why the answer does not depend on what a person buys.
- 4(a): the term "fri konkurranse", and no mention of p = AC.
- 4(b): price, output per brewery and number of breweries were wrong under constant elasticity. The gain was given as scale economies, not more variety.

**What I changed.** I wrote each correction myself, with hints from the agent:
- 1(c): G = 33/100. My first correction was 1/3, which is also wrong.
- 1(d): Besparelsen viser at kostnadene til firmaet synker når man tar i bruk AI. Modellen tar w som gitt, så den kan ikke vise hvordan lønnsnivået blir. Lavere kostnader gjør at produksjonen kan gå opp, som gjør at vi trenger flere arbeidere i de oppgavene som ikke har blitt automatisert.
- 2(a): helningen er −1 for Kaldland og −2 for Varmland.
- 2(c): handelslinjen har helning −1,5. C = (5, 7,5) ligger utenfor Kaldlands PPF, siden 5 + 7,5 > 10.
- 2(d): en arbeidstime koster 0,5 laks i Kaldland og 1 i Varmland. Møbler koster 3 · 0,5 = 1,5 laks i Kaldland og 2 · 1 = 2 i Varmland. Lønnen er høyere i landet med absolutt fortrinn.
- 3(b): kjeden er ŵ > p̂x > p̂y > r̂ (66,7 % > 33,3 % > 0 % > −33,3 %).
- 3(c): prisendringene ligger mellom endringene i w og r. Lønnen øker mer enn begge vareprisene, mens leien på kapital faller. Dette gjelder uansett om personen bruker inntekten på maskiner eller møbler.
- 4(a): hvert bryggeri setter prisen over marginalkostnaden, fordi det er unikt og har noe markedsmakt. Fri etablering presser prisen ned til gjennomsnittskostnaden (p = AC), så påslaget dekker de faste kostnadene.
- 4(b): prisen og produksjonen per bryggeri er uendret. Antall bryggerier på Vestøya er uendret. Forbrukerne får flere varianter gjennom import. Gevinsten er større utvalg.

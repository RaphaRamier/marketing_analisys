# Análise de Marketing

---

# Introdução

O atual projeto tem como intuíto a apresentação e análise dos dados fornecido pela cliente para ajudar a otimização das despezas com Marketing. 

O projeto terá como foco responder as seguintes questões da cliente:

## 1.	Produto
*	Quantas pessoas usam-no cada dia, semana e mês?
*	Quantas sessões ocorrem por dia? (um usuário pode realizar várias sessões).
*	Que comprimento tem cada sessão?
*	Com que frequência os usuários voltam?


## 2.	Vendas
*	Quando as pessoas começam a comprar? (Na análise de KPIs, nós geralmente estamos interessados em saber o período de tempo entre o registro e a conversão - quando o usuário se torna um cliente. Por exemplo, se o registro e a primeira compra de um usuário ocorrem no mesmo dia, ele pode encaixar na categoria de Conversão 0d. Se a compra é realizada no dia seguinte, isso será a Conversão 1d. Você pode usar qualquer abordagem que permita comparar as conversões de diferentes coortes, para que você possa determinar qual coorte ou canal de marketing tem a maior eficiência)
*	Quantos pedidos os clientes fazem durante um determinado período de tempo?
*	Qual é o volume médio de uma compra?
*	Quanto dinheiro eles trazem para a empresa (LTV)?


## 3.	Marketing
*	Quanto dinheiro foi gasto? No total/por origem/ao longo do tempo
*	Quanto custou a aquisição de clientes para cada origem?
*	Os investimentos valeram a pena? (ROI)



---

# Descrição dos dados

A tabela visits (os logs do servidor com dados sobre os acessos ao site):

- Uid — identificador unívoco do usuário
- Device — dispositivo do usuário
- Start Ts — data e hora do início da sessão
- End Ts — data e hora do final da sessão
- Source Id — identificador da origem do anúncio através do qual o usuário chegou
- Todas as datas nesta tabela estão no formato YYYY-MM-DD.

A tabela orders (dados sobre os pedidos):

- Uid — identificador unívoco do usuário que faz um pedido
- Buy Ts — data e hora do pedido
- Revenue — a receita da Y.Afisha com o pedido
- A tabela costs (dados sobre as despesas com marketing):
- source_id — identificador da origem de anúncio
- dt — data
- costs — despesas com esta origem de anúncio neste dia

---

# Conclusão

Inicialmente, deve-se frisar que os investimentos nos veículos de Marketing estão sendo direcionados para os veículos menos lucrativos, como por exemplo o veículo 3, que é uma das veículos menos lucrativas apresentando apenas 4,26% da receita enquanto é investido cerca de 43% do capital destinado ao Marketing. 

Com menos de 20% do capital destinado ao investimento em Marketing as veículos 1 e 2 geram juntas mais de 70% da receita. 

Somente estes números já nos diz que deve-se dar mais atenção a esses veículos que geram mais receita e cogitar zerar o investimento nos outros veículos, ou realocá-los, ou talvez, investir uma quantidade eventual em momentos pontuais como o último trimestre do ano que é o período que o número de vendas dispara, superando e muito os outros meses como foi mostrado gráficamente. 

Portanto, é aconselhado que reveja a politica de investimento em Marketing dos veículos 3 e 4, o mais rápido possível.  

Pois diante do atual cenário de um prejuízo de $-77074.42 em um período de 12 meses, tal prejuízo pode ser irreversível.
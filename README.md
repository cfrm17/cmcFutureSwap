# Commodity Futures Swap Valuation

A commodity futures (contract) swap (CFS) is a linear portfolio of forward contracts on commodity futures (contract) (FCCF). An FCCF belongs to the category of arithmetic average forward contracts. Due to the linearity with respect to underlying asset prices, an arithmetic average forward contract is just a linear combination of ordinary forward contracts. 

The specialities of an FCCF which is matured or settled at a time T are the following. With a specified set of average time points for the FCCF, t1 < ¢ ¢ ¢ < tn < T, the payoff at the maturity or the settlement date T is given by an arithmetic average of values (or prices) of assets, Fcomm(ti)’s, where each Fcomm(ti) is the value at ti of the commodity futures contract which is the nearest related to ti. Such a contract is called the nearest futures related to ti. To be more precise, we denote the value of the nearest futures by Fcomm(ti; I(ti)) where I(ti) is the index of the nearest futures contract related to ti. The average is weighted by time. It should be noted that different ti and tj may be related to the same nearest futures, i.e., I(ti) may be identical to I(tj). 

Let us consider crude oil as an example of commodity. In the crude oil exchange market, futures contracts are available for each calendar month. The roll over dates for MAY-99 and JUN-99 futures contracts are 20-Apr-99 and 20-May-99, respectively. If t1 = 15-Apr-99, t2 = 20-Apr-99 and t3 = 21-May-99, Then the nearest futures for t1 and t2 is the MAY-99 contract, i.e., I(t1) = I(t2) = MAY-99, and the nearest futures for t3 is the JUN-99 contract, i.e., I(t3) = JUN-99.

It is known that the value of a futures contract at a time t is equal to the futures price at that time. If without any confusion, we may also use the notation Fcomm(t; I(ti)) to represent the commodity futures price at time t of the nearest futures corresponding to time ti. Commodity futures prices are quoted as the number of units of a currency per unit amount of a commodity. For an FCCF with a strike of K and maturity of T, the value of the FCCFC, denoted by V , at T can be written as

 

where !i’s are time-weighting factors, Pn i=1 !i = 1, usually !i = 1=n, ¯ is a position index, and P is the commodity principal — the number of units of the commodity in the contract.

Clearly, (1) is the payoff of the FCCF at the settlement. Let t be a valuation time point. If there are m ¸ 0 average time points are prior or equal to t, then the matured payoff (1) can be re-written as

 

and K¤ is deterministic related to the valuation time t. Without the loss of generality, we may assume that the valuation time t is always prior to the first average time point t1, i.e., m = 0 and K¤ = K.

Let us denote C be a quoted cash currency in the commodity market. In the above, dimensions of the commodity price, the strike are the same, i.e., [unit of C/unit of the commodity]. The dimension of he value of the FCCF is [unit of C]. However, in some general cases, there may be more than one currencies involved: one for measuring the value of an FCCF, the second for defining a strike (or equivalently a notional principal) and the third for quoting the commodity futures prices. To clearly indicate currencies used for measuring these variables, we use FCcomm, KCcomm and VC instead. Then, the payoff at the settlement (1) can be re-written as

 

which means a single currency is used for measuring values, a strike and futures prices (see https://finpricing.com/lib/FiBond.html)

Under the assumption of the certainty of drift terms of the commodity price and the currency exchange rate (i.e., deterministic risk free interest rate and cost-of-carry yield of the commodity) and the completeness of market, by the no-arbitragy pricing theory, the value of the ¯-FCCF at the valuation time t can be given by, for t < t1,

 

where dfC1(t; ¢) is the discounting factor at time t for the currency C1, fC2C1 (t; ¢) is the forward
exchange rate at time t and EC2t [ ¢ ] is the conditional expectation operator in the C2-riskneutral
world. If C1 = C2 = C, then (6) reduces to

 

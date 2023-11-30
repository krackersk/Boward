## Thesis
Speculation is one of the only activities in crypto that has found product-market-fit. Exchanges (centralised and decentralised) are the entities which enable this speculation, users pay for this activity making exchanges one of the few profitable entities in crypto.

Thesis: The main decentralised perps exchange will be a blackhole for liquidity and be highly profitable during the next bull run.

The main uncorrelated drivers for the thesis:
1. Crypto volumes will increase
2. Decentralised volumes will increase relative to centralised volumes
3. Decentralised perp volumes will increase relative to decentralised spot volumes
4. Exchanges are a winner take most market
5. Profitability will enable earnings distribution to token holders

How to take advantage of this thesis:
* Invest in the token of the decentralised perps exchange which will dominate on-chain liquidity

### Exploring the thesis drivers
#### 1. Crypto volumes will increase
With each crypto bull run the total volume traded increases in magnitude, and keeps some of that increase during the bear market (see graph below). If we take there will be another bull run as a given, then we can expect volumes to increase by another order of magnitude.
![](/attachments/Screenshot%202023-11-25%20at%209.16.37%E2%80%AFam.png)[^7]

#### 2. Decentralised volumes will increase relative to centralised volumes
CEX’s advantages, _performance_ and _ease of use_, are being eroded as blockchains improve in both these attributes. Blockchain’s advantages, _composability_, _regulation arbitrage_, _tokens_ and _transparency_, will drive users and hence liquidity to DEX’s. See [[Perpetual futures (Perps)/Where do DEX’s and CEX’s differ?]].

#### 3. Decentralised perp volumes will increase relative to decentralised spot volumes
Leverage and accessibility. Perps allow leverage, spot leverage is limited. Perps allow easy accessibility to a range of tokens from different blockchains on the one platform. Spot DEX’s liquidity is segmented between different blockchains. See [[Perpetual futures (Perps)/Why use perps?]].

#### 4. Exchanges are a winner take most market
Monopolies form when there are benefits to economies of scale. More liquidity improves the trading experience through less slippage and larger trades becoming viable, this increases fees without a similar magnitude increase in cost. This effect can be seen in the graph below, with Binance dominating the perps market, while other echange’s volume relatively declines.
![](/attachments/Screenshot%202023-11-25%20at%209.40.28%E2%80%AFam.png)[^7]
#### 5. Profitability will enable earnings distribution
“Clients always pay for leverage,” he said. “That’s why, when I set out to create my own crypto trading platform in 2014, I focused on derivatives. And it’s also why, when I started exploring how to get meaningful exposure to DeFi in 2022, I went the derivatives route then, too. … the [GMX] tokenomics offer an attractive yield, which is another reason why I like this token for my portfolio.”” - Arthur Hayes[^6]

“In 2022, the [dYdX] protocol generated $128.1 million in revenue and paid out $197.3 million in rewards, resulting in a total net loss of $69.3 million.”[^8] 

Some perps DEX’s are paying for users through token emissions (dYdX). While others (GMX) have started paying out profits to token holders. Overtime as DEX’s become more larger and profitable, I predict we’ll see these profits being distributed to token holders.

## What is a perp?
A perp’s value is it’s ‘mark price’, if this varies from the ‘index price’ then, at a certain interval, the system transfers a funding fee (called the funding rate) between those who are long the perp and those who short the perp, depending on the direction of movement. This fee comes from the margin (collateral) in the trader’s account. If the margin gets too low, including a margin of safety, they will automatically be liquidated.
The funding rate is the feedback mechanism to keep the mark price of the perp close to the index price, the more it varies from the underlying, the larger the funding rate difference. The funding rate changes to incentivise either longs or shorts, depending on the balance between the two. Causing traders to bid up or bid down the mark price towards the underlying.
If the market moves too quickly, and the liquidated amount is less than the amount owed, perp exchanges usually have an insurance fund to cover the gap.
[The Cartoon Guide to Perps](https://www.paradigm.xyz/2021/03/the-cartoon-guide-to-perps) is a simple explanation of what a perp is.
## Why use perps?
Derivatives serve two purposes: **hedging** and **speculation**. There are two key reasons why they exist instead of hedging or speculate on the spot market instead: **inaccessibility** to the underlying and **leverage**.
A high-friction spot market creates the demand for liquid derivatives markets. For instance, it is a lot easier to sell wheat futures than it is to take a short position in the underlying wheat market (which would presumably involve borrowing a lot of physical wheat). 
Furthermore, transacting in derivatives is more capital efficient as traders can use leverage, putting down only a small portion of their capital to achieve a notional value that could be sometimes 20x, 50x, or even 200x their margin.[^2]
[Dive into Crypto Derivatives: Perps, Funding & Price Action](https://think10capital.io/dive-into-crypto-derivatives-perps-open-interest-funding-and-price-action/) by Think10 Capital is a good analysis of some of the situations people use perps and the relation to spot price.
## Users of perps
Categories of perps users:
* institution trading firms
* prosumers (advanced consumers), these are the organic taker volume.
Institutions follow where the volume of prosumers are as they are considered ‘dumb’ money, lessoning the risk for institutional market makers. Dydx aims to appeal to prosumers.[^1]

## What do users want in a perps exchange?
Liquidity
* **Liquidity is the most important** - in the end, you want to be able to trade what you want, when you want, for the lowest cost. Liquidity begets liquidity, most of the other attributes bring more liquidity to the exchange which attracts more liquidity.
* Allows higher volumes 
* Tighter bid/ask spreads
* Breadth of assets - can a user trade what they want to?
* Endemic price discovery - an exchange with the highest liquidity may be the place where the price of the asset is determined, eliminating Oracle risk

Capital efficiency
* Efficient capital use - A capital efficient market allows more volume for less locked capital allowing that capital to be used elsewhere. It also reduces cost as the protocol pays often pays for capital use.
* Higher leverage - more capital efficiency allows more leverage, your money works harder for you.

Costs
* Make/taker fees
* Funding rate
* Slippage
* MEV / payment for order flow / exchange trading against you

UX
* Performance
  * Speed (throughput and latency)
    * Institutional market makers need speed for efficient market making[^3]
    * Accurate price - If an exchange price is behind the market there is arbitrage - the highest volume fastest exchange sets the price the others follow and get arb’ed. This is cost to the users.
    * Higher volumes for time-sensitive trades - able to trade when you need it most!
  * Stability - can a user trade when the markets move most, as that is when they need to.
* Ease of use
  * Getting funding on the exchange
  * KYC / geoblocking

Security
* Oracles
  * Price manipulation - price Oracles can sometimes be manipulated which throws off the price on the exchange
* Liquidations
  * Speed - can the price move more than the liquidation engine can handle, causing the exchange to be insolvent?
  * Insurance fund - if the exchange does get a whole, do they have an insurance fund to make good
* Counterparty risk - FTX….
## Where do DEX’s and CEX’s differ?
### CEX advantages
* Performance
  * CEX’s run on centralised servers and will almost always have better speed than blockchains
  * This means CEX’s have more accurate prices, and often better liquidations
  * CEX stats
    * latency: ~100ms[^4]
    * throughput: ~10,000 TPS[^4]
* Ease of use
  * CEX’s are the first touch for users into crypto - you need to bring fiat into them before you can interact with the blockchain, most users will stop there. They will need a compelling reason to move further and understand the complexity of self custody.
### DEX advantages
What are the properties of a DEX where a CEX cannot compete?
* Composability
  * Ecosystem of apps
    * can be used as a permission-less backend for apps, including centralised exchanges
    * features can be added permission-lessly by other teams (eg. Osmosis ecosystem - loans by Mars, Perps by Levana)
  * Outsource functions
    * functions like settlement are outsourced to the blockchain, smart contracts are anecdotally reduce work required 10x
  * Cost
    * The above reduces operating costs (how much? A magnitude?) - these cost savings could be reflected in lower cost to user
* Regulatory arbitrage
  * Global marketplace
    * write once work anywhere - no need to setup entities in different jurisdictions
  * Permission-less listing of assets
    * long tail assets are not on CEX’s due to work created to list and regulatory hurdles (eg. Security or not), or could be listed first due to the permission-less nature of blockchains
  * No-KYC
    * once in the blockchain ecosystem, ease of onboarding due to no KYC
  * Cost
    * The above reduces operating costs
* Token
  * Incentives
    * Good for bootstrapping a user base and creating a feeling of ownership by users / marketing
  * Community building / Creditable neutrality
    * Any entity can own the token and participate in the governance and profits (if they are paying them out to token holders)
* Transparency
  * counter-party risk is removed (but there are other risks, eg. Smart contract risk)
  * Order book entirely open - depending on who you ask, its a feature or a bug - creates social aspects if you can see everyone’s trades, but some institutions/traders might not want their trades known[^4]
### Can DEX’s attract liquidity?
Liquidity begets liquidity. How would a DEX attract enough liquidity that it sucks in most of the rest and becomes the dominant exchange?

Multiple of the following attributes needed to drive users (prosumers), and hence, liquidity:
* Price discovery - ==should probably be liquidity?==
  * Need performance close to as good as CEX’s so no CEX can front run
  * Largest liquidity / volume will mean other exchanges will follow?
  * Need an order book for price discovery[^4] - they are not dependent on other parties for marked price
* Improve customer acquisition 
  * Direct fiat onboarding and abstract away self custody complexity, bypassing the CEX’s
  * or, become the backend for multiple CEX’s (they handle the onboarding, the protocol gets some of the fees)
* Lowest cost exchange
  * Use cost advantages to undercut other exchanges. This will partly depend on liquidity to reduce the spreads
  * High capital efficiency
* Available in user markets CEX’s aren’t 
  * Be the only available option - many small user markets may add up in terms of liquidity?
* Provide functionality CEX’s can’t
  * Long tail assets - users want to speculate on long tail assets as these are where you can make large gains. Uniswap grew due to availability of long tail assets.
  * Other functionality (unknown unknowns 😁) thanks to permission less innovation/faster innovation on blockchains

## Market size
* 1/3 of volume of coins are spot, 2/3 Is perpetuals! [^1] Perpetual futures are the largest traded instrument in crypto. To provide a sense of scale, **futures volume has comprised ~75% of total trading volume for Binance since 2021**.[^2] 
* Just Bitcoin is 50% of the trading volume in crypto trading, so you need to play in this space.[^1]
* Most of the volume of perps is on centralised exchanges[^2]. In Sept 23 CEX Perps volume was $1.5T vs $23B for DEX Perps, which is about 1.5%[^5].
* Spot DEX’s are 10-20% of CEX’s, where as Perps DEX’s are 1-3% of CEX’s[^2] - lots of room for Perps DEX’s to grow.
* Its a winner takes most market, probably due to the advantages of liquidity network effects and economies of scale
![](/attachments/Screenshot%202023-11-01%20at%204.25.49%E2%80%AFpm.png)[^2]
![](/attachments/Screenshot%202023-11-13%20at%203.31.03%E2%80%AFpm.png)[^5]
![](/attachments/DEX%20Perps%20Top%206.png)

[^5]
![](/attachments/Screenshot%202023-11-13%20at%203.30.11%E2%80%AFpm.png)[^5]
![](/attachments/Screenshot%202023-11-13%20at%203.30.26%E2%80%AFpm.png)[^5]
## Potential Market Value
### Revenue
“The Drake Equation for many crypto businesses:  Revenues = P (crypto prices) * V (trading volume) * T (% take rate)
The overwhelming bias for most traditional analysts is to structurally underestimate the size of P and V in the long run.” - [Matt Huang on Twitter](https://twitter.com/matthuang/status/1401240446152548352?s=20)

![](/attachments/3db8082e-1aa6-4361-b952-7eedb3ae9cb3_990x819.png)
[^2]

## Technical design of Perp DEX’s
There dominant DEX designs:
* **Central limit orderbook (CLOB)**
An orderbook that collates all buy and sell orders for an asset, in which trades occur where the buy and sell prices match. CLOB’s need high transaction throughput on the order of 1000’s per second due to bid and asks transactions. Matched transactions are on the order of 10’s per second. Most DEX’s do matching off-chain and settlement on-chain to get around the throughput limitations.
Perp CLOB’s usually rely on Oracles for the price of the asset, and hence have Oracle risk.
* **Oracle based AMMs**
These AMMs are the counterparty to the trader, if user’s lose then they win and vice versa. They can be single-asset, multi-asset pools, or virtual (see [A Deep Dive into our Virtual AMM \(vAMM\)](https://blog.perp.fi/a-deep-dive-into-our-virtual-amm-vamm-40345c522eeb) for info, and [The Quest for Perp AMMs - Deribit Insights](https://insights.deribit.com/market-research/the-quest-for-perp-amms/) for some of the issues). The risk is often compensated for by yield generated by fees. They are good at bootstrapping liquidity like spot AMMs using token incentives, and since the pool takes the other side of the trade, you don't need to match long/short buyers. They are less capital efficient than CLOB’s and the liquidity providers need to be compensated, meaning they have structurally higher costs. Their capacity is also limited by the LP size/vault size (trader provided liquidity) for vAMM.
Since they are based on Oracles, they can only provide trading on assets where an oracle is available and are at risk of oracle manipulation. Another risk is liquidity pool being hacked and assets drained.
Note: GMX somehow removes impermanent loss for LP’s, not sure how, maybe it’s because its not one asset in the pool trading against the other, its the assets trading against the trader, and the risk is not impermanent loss but traders winning vs the pool.
*  **Intent Based**
The user supplies their intent (what they want to do, and for what price) and solvers bid to be able to fill the order. The solver fills it any way they want, the cheaper they do it, the higher they can bid and still make profit. A primer on intents: [Powerful Intents: Part 1](https://brinktrade.medium.com/powerful-intents-part-1-7f97cc6425b3), and a deeper dive into intents architecture: [An introduction to intents and intent centric architectures](https://anoma.net/blog/an-introduction-to-intents-and-intent-centric-architectures)
For simple intents, like a limit order, they are essentially an order book, right!? 
Seems like 'Yes': [Intents are just...](https://medium.com/alliancedao/intents-are-just-7deaeb4336be)
Intent based systems are essentially a perps aggregator, the solvers use existing CEX / DEX / their own market making to fill the order. As it uses these other parties to fill the trade it will always be slower and more expensive them as the middlemen (solvers) need to put a fee on top. Part of this needs to be off-chain and so will not be decentralised and hence maybe not be able to do regulation arbitrage.

Actually pretty good summary of different perps tech from [yieldfarming on X](https://twitter.com/delucinator/status/1728977992758812868):

"so my current opinion of the perps dex meta is:

symm base: binance without kyc but slower and more expensive
orderbook base: might get rugged by black swans like yfi
liquidity base: trash, will be 0 in 12 months

can someone enlighten/convince me otherwise"
## Metrics
All metrics should be looked at overtime.
**Trading volume** - sum of both open and closed long/short positions - can be gamed through wash trading and token price increases - especially if there is an token reward for trading, though takes a loss on the fees
**Open Interest** - sum of only the open long/short positions - Looking at Volume/OI determines frequency of trading and can use it to determine if wash trading is happening on the platform. If the ratio is way out of whack, then there is probably wash trading on the platform to game incentives. See Open interest explanation [Everything you need to know about using open interest in trading](https://woo.org/blog/en/everything-you-need-to-know-about-using-open-interest-in-trading)
**TVL** - this metric should be minimised for capital efficiency, so probably better to look at volume/TVL to find capital efficiency
**Unique Traders** - can look at addresses, but easy to game with the same user/bot having multiple addresses
**Fees** - harder to game, this is a dead weight loss for the trader so incentive is to minimise 
**Earnings** - depends on what is classified as revenue and expenses. Token emissions should probably be included in expenses.
**Developers** - the liveliness of the protocol

**Volume/OI**: eg. Wash trading on Vertex due to ARB incentive program. [vxH0rny.blast on X](https://x.com/veH0rny/status/1729195256359621081?s=20)

![](/attachments/Pasted%20image%2020231130212427.png)
### Dashboards
Artemis
* [Artemis - Perps Dashboard](https://app.artemis.xyz/dashboard/perpetuals/compare) - Trading volume, TVL, Unique traders, Market Cap
Token Terminal
* [Token Terminal - Fees](https://tokenterminal.com/terminal/metrics/fees) - Select Derivatives toggle. Also lots of other metrics dashboards can be chosen
* [Token Terminal -  Derivatives dashboard](https://tokenterminal.com/terminal/markets/derivatives) - TVL, Fees, Active Users, 
* [Token Terminal - dYdX Dashboard](https://tokenterminal.com/terminal/projects/dydx) - Trading volume, TVL, Fees, Earnings, Developers, Market Cap. Also lots of other protocols dashboards.
The Block
* [The Block - DeFi Derivatives](https://www.theblock.co/data/decentralized-finance/derivatives)
* [The Block - DeFi Exchange](https://www.theblock.co/data/decentralized-finance/dex-non-custodial)
* [The Block - Futures](https://www.theblock.co/data/crypto-markets/futures)
Dune analytics
* [Dune analytics - Most Ethereum Perps dashboard](https://dune.com/shogun/perpetual-dexs-overview) - Trading volume, Users, Fees, plus others including open interest, liquidations etc

### Other examples of metrics
[Fair value vs TVL/VOL/Fees/Earnings](https://twitter.com/tumilett/status/1678135182426005507?s=20) - look at what might be moving the market for perp tokens

## Competition
[SymmIO](https://www.symm.io/) - intent based backend OTC aggregator which protocols such as [basedmarkets](https://twitter.com/basedmarkets) (Base L2), [IntentX](https://twitter.com/IntentX_) (Base L2), and [Thena](https://twitter.com/ThenaFi_) (BNB chain) have built 3rd party frontends for. Not sure if it runs on a chain or is totally off-chain, the info in the docs is very sparse. It does have EVM contracts for the protocol suite but this might be just communicating with a off-chain backend? See https://docs.symm.io/protocol-architecture/protocol-introduction/the-protocol-suite
[n\(uh\)z on Twitter](https://twitter.com/uhr3al/status/1567433574156226562?s=20)
MUX is an aggregator - uses other backends as well as it’s own: [Emperor Osmo🧪 \(@Flowslikeosmo\) on X](https://twitter.com/flowslikeosmo/status/1701959078572912875?s=12&t=rsnnu7xzWfoqD1yLiNIXdw)
Synthetix as a backend for perps: [Synthetix V3 Markets: A Comprehensive Guide](https://blog.synthetix.io/synthetix-v3-markets-a-comprehensive-guide/)

![](/attachments/94fad2f1-2722-43ba-8e20-73e948f85f0c_1598x805.png)
[^2]
![](/attachments/Treehouse%20research%20-%20key%20metrics%20of%20perps%20DEXs.png)
[^9]
![](/attachments/Treehouse%20research%20-%20Key%20metrics%20of%20CEXs.png)
[^9]
![](/attachments/image.png)
[tuba 🦈 \(@0xtuba\) on X](https://x.com/0xtuba/status/1567711817178427393?s=20)
Options: [HanSolar.eth on Twitter](https://twitter.com/hansolar21/status/1567750203712897024?s=20)
Synthetix: [Adam Cochran \(adamscochran.eth\) \(@adamscochran\) on X](https://twitter.com/adamscochran/status/1723030687039525262?s=20)
Options vs Perps: [Panoptic \(@Panoptic_xyz\) on X](https://x.com/Panoptic_xyz/status/1720210447666999456?s=20)
Perps DEX’s that have raised money: [Ronin \(@DeRonin_\) on X](https://twitter.com/DeRonin_/status/1726987502924579302?s=20)
[jordan \(@yeak__\) on X](https://twitter.com/yeak__/status/1690092544145715200?s=12&t=rsnnu7xzWfoqD1yLiNIXdw)
IntentX - [slappjakke.eth 🦇🔊 \(@Slappjakke\) on X](https://twitter.com/Slappjakke/status/1709599486878929155?s=20)
Good discussion about liquidity on-chain / off-chain: [Elijah \(🥧. 📈\) \(@PossibltyResult\) on X](https://x.com/PossibltyResult/status/1709733825700405259?s=20)
Vertex - combination orderbook/amm - https://x.com/ThorHartvigsen/status/1729145134862795034?s=20
HyperOracle: https://twitter.com/hmalviya9/status/1719684120606044165
zk tech might be able to be used to improve computation times - possibility for future on-chain perps DEX? https://x.com/hmalviya9/status/1719684133730103729?s=20
## References
[^1]: [Epicentre podcast - Antonio Juliano: dYdX - Decentralised Perpetual Exchanges](https://overcast.fm/+RhzYdB2Wc)
[^2]: [Crypto Derivatives Part 1: Perpetual Growth](https://amberlabs.substack.com/p/crypto-derivatives-part-1-perpetual?utm_source=substack&publication_id=1060002&post_id=135424062&utm_medium=email&utm_content=share&triggerShare=true&isFreemail=true)
[^3]: [Speed is the Future for DEX Liquidity](https://medium.com/derivadex/speed-is-the-future-for-dex-liquidity-e44a8f50b2d6)
[^4]: [dYdX’s Antonio Juliano: The Largest Perpetuals Exchange with $1 Trillion In Cumulative Volume Transitions To A Cosmos Appchain — The Delphi Podcast — Overcast](https://overcast.fm/+O9LIQ-3Ck)
[^5]: [2023 Q3 Crypto Industry Report](https://www.coingecko.com/research/publications/2023-q3-crypto-report)
[^6]: [Hayes Shares Why He Loves GMX and Is Bullish on DeFi](https://thedefiant.io/arthur-hayes-likes-gmx)
[^7]: [CMS Holdings - dYdX](https://cmsholdings.substack.com/p/dydx)
[^8]: [State of dYdX Q4 2022](https://messari.io/report/state-of-dydx-q4-2022?referrer=author:kentrell-key)
[^9]: [A Peep into Perps: Perpetual Futures Explained - Insights - Treehouse Research](https://www.treehouse.finance/insights/a-peep-into-perps-perpetual-futures-explained)
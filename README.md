---
description: v1.1 Aug 10 2020
---

# DeFis Network: An Open Finance System

### Abstract

> That government of the people, by the people and for the people, shall not perish from the earth.                                                             ---- Abraham Lincoln, 1863, Gettysburg, Pennsylvania

Shall the finance of the people, by the people and for the people, perish from the earth? Our answer is no, more importantly, the finance of the people, by the people and for the people is the basis of the cause that mankind has been fighting for generations. 

But for more than 1.5 centuries, worldwide inequality of our finance system has been plundering people's fortune and destroying people's equal rights to benefit from the finance system that people all around the world have been building up together. 

Aug 2020, the founding team of DeFis Network, a small group of innovators, decide to tackle this problem and fundamentally change the inequality of our finance system.  

In the new design, any transaction made in finance system is a measurable value and contribution to the growth of the system that should be fairly rewarded by the system.   



### Introduction

DeFis Network’s mission is to create a new finance infrastructure that of the people, by the people, and for the people around the world. 

Based on the blockchain and other emerging technologies, together, people all around the world can freely and equally own, build and share better assets, better exchanges, better banks, better finance system and better future, so that everyone in the world can enjoy the worldwide equality of this new finance system.

DeFis Network is a on-chain network that aggregates all valuable decentralized finance protocols, allows users to do any financial transaction, investment and asset allocation safely and conveniently while users, as DeFis Network token holders, benefit from the value growth of whole DeFis Network.

DeFis Network is built on EOSIO Blockchain, we believe the stability, high scalability and zero transaction fee of EOSIO will definitely help us to deliver the best possible user-centric financial service and user experience. 



### Features and Protocols Overview

#### Stablecoin issuing protocol: Bank

Bank allows users to mortgage crypto assets through smart contracts to issue universal settlement stablecoin USDD which exists entirely on the blockchain.

Compared with DAI's lending paradigm, it's called saving paradigm. It is designed to make the collateral 100% safe and at the same time users enjoy the benefit of staking income from the relevant public blockchains.

It is a fully on-chain, transparent and decentralized central bank created and owned by all users and minters together. 

#### Liquidity protocol: Swap

Swap allows users freely create trading pairs between any two crypto assets and inject any liquidity fund to form an high efficiency trading and exchanging market.

According to the proportion of the injected liquidity fund, users can fairly share the transaction fees \(currently 0.2%\) generated by the trading pairs.

It is a fully on-chain, transparent and decentralized exchange created by all users and traders together. 

#### Credit protocol: Credit

Credit allows users to borrow crypto assets through public credit pool using another assets as mortgage by paying an interest rate, or to lend crypto assets by earning an interest rate. Algorithm ensures the marketization of the interest rate.

Every user can supply liquidity to credit pool to fairly share the interest that borrowers pay. Credit will ensure the security of assets in the pool, clearing and settlement is in real time including insufficient mortgage.

It is a fully on-chain, transparent and decentralized commercial bank created by all borrowers and lenders together. 

#### Synthetic Asset protocol: Synthesis 

By staking DFS tokens or other supported crypto assets, Synthesis allows users to synthesize, hold and trade a variety of high-quality off-chain assets such as stocks, bonds, commodities, real estate etc, without having to hold actual assets themselves or entrust any custodians. 

Synthetic assets trading does not require a counter-party, the synthetic asset you sell will be converted directly into a short version of the synthetic asset you want to buy which makes the trading has almost unlimited liquidity. Price feeds supplied by oracle.

It is a fully on-chain, transparent and decentralized off-chain assets exchange created by all synthesizers and traders together. 

#### DeFis Network Mining Pools: Mining

Mining allows users to mine and gain DFS tokens fairly through making any possible transactions by using any protocols in DeFis Network as the builders and beneficiaries of the whole DeFis Network. \(DFS is the token of DeFis Network. Please see the details at \[Token and Token Distribution\]\)

Mining sees every micro transaction made and every use of DeFis Network protocols in DeFis network as a value creation and contribution to the whole DeFis Network.

It is a fully on-chain, transparent and decentralized off-chain DFS mining created by all participants and miners together. 

Please see the details below at \[Mining: DeFis Network Mining Pools\]

#### DFS Saving Rate: DSR

DSR allows users to earn guaranteed DFS income by depositing DFS tokens to the public DFS saving pool. 

It is a fully on-chain, transparent and decentralized off-chain public DFS saving pool  created by all depositors together. 

Please see the details below at \[DSR: DFS Saving Rate\]

#### More features and protocols will be added

Because DeFis Network will continuously envolve and innovate as long as it's still  breathing in this new world.



### Token and Token Distribution

#### DeFis Network Token: DFS, Decentralized Finance Share

DFS is the token of DeFis Network, which is the first and only 'BTC' of DEFIs built on EOSIO blockchain that founding team follow the exact same rules to gain DFS tokens with any community member and any one in this world: Buying DFS through trading or mining DFS through participating in DeFis Network. 

DFS tokens are mainly used for:

1. Trading
2. Governance voting
3. Trading incentive
4. Liquidity incentive
5. Stablecoin minting incentive
6. Creating synthetic assets
7. Staking fixed income
8. Community enhancement
9. Partner cooperation

Through the aggregation and innovation of more DeFi protocols in the future, DFS tokens will continue to capture more further value. DFS distribution are executed by smart contracts automatically, so that each DFS holder can share the benefits of DeFis Network development fairly. 

#### DeFis Network Token DFS Distribution: 

**Three rules of DFS distribution:** 

1. Maximum circulation: max\_supply = 10 million
2. Mining difficulty coefficient increase: Mining output automatically decays once every 1 million is issued
3. Automatic adjustment algorithm:

```text
damping = pow(0.75, (int)(current_supply / 1000000)); 
```

DFS will experience a total of 9 decays when the total amount of mining reaches its maximum circulation of 10 million.

```text
> Math.pow(0.75, 0);
1
> Math.pow(0.75, 1);
0.75
> Math.pow(0.75, 2);
0.5625
> Math.pow(0.75, 3);
0.421875
> Math.pow(0.75, 4);
0.31640625
> Math.pow(0.75, 5);
0.2373046875
> Math.pow(0.75, 6);
0.177978515625
> Math.pow(0.75, 7);
0.13348388671875
> Math.pow(0.75, 8);
0.1001129150390625
> Math.pow(0.75, 9);
0.07508468627929688
```

### \*\*\*\*

### **Mining: DeFis Network Mining Pools**

There are 3 major mining pools currently:

1. Trading mining pool \(trading and exchanging incentive\)
2. Liquidity mining pool \(market maker incentive\)
3. USDD minting mining pool \(stablecoin minting incentive\)

More pools will be added.

Trading mining pool will contain an invitation mining system when there is an inviter for a transaction, the invitee will get a 4% extra mining power, the inviter will get 1% extra mining power.

**1. Trading mining pool**

**Design Ideas:**

Any user transactions that make subtle and quantifiable incremental contributions to DeFis Network, even 1 in 10 million, will be captured by the algorithm. After the cature DeFis Network immediately issues DFS tokens and transfers DFS tokens as incentives to relavant user transaction accounts in real time. The Incentive ratio will be calculated automatically by the algorithm. 

As for any transaction of any user made in DeFis Network, the real-time DFS incentive is a discount of transaction fee in short-term, but more importantly it is a kind of value that is not easily valued currently, hopefully priceless, as DeFis Network continuously grows and practices its mission to the world of finance.

When you receive 0.1 DFS through trading in DeFis Network before 2022, it's like when you receive 0.1 BTC through BTC mining before 2011. The only three differences are: DFS has a bigger mission, DFS has broader application context and DFS has stronger usability in lower cost.

**Trading mining algorithm:** 

```text
trading_mining_reward =  
trading_fee / dfs_price * discount * damping * pool_weight;
```

**Example Case:**

Parameter assumptions:

1. average DFS market price: 1 DFS = 0.15 EOS, 
2. transaction volume: 100EOS, the fee is 0.3%, so this transaction generates a fee of 0.3 EOS. 
3. discount: 0.2 
4. damping: 0.75 

Question: For a transaction of 100 EOS, a fee of 0.3 EOS is paid, so how much DFS will be obtained for transaction mining?

**Apply trading mining formula:**

```text
trading_mining_reward = 0.3 / 0.15 * 0.2 * 0.75 = 0.3 DFS 
```

For this transaction, if there is an inviter. Then the calculation power is automatically increased by 5%. 4% of them are for traders and 1% for inviters. Please check below.

**Invitation mechanism for trading mining \(optional\)**

**Design ideas:**

A more open protocol layer design will not only help the protocol be integrated by more third-party applications. It also provides potential partners, such as wallets, exchanges, third-party agents and high-frequencey traders etc.

Maintaining the simplest, most open, most transparent and purest decentralization on chain, is most likely to become the basic liquidity protocol for large-scale use on EOSIO public blockchain. 

**Potential inviters:**

1. Wallets: There are users and traffic. Apply to become an inviter with long-term effective revenue sharing 
2. Exchanges: trading depth can be shared because the protocol is open 
3. Third-party purchasing agent 
4. DEX protocol aggregators 
5. High-frequency quantitative traders and market makers. 

**Invitation Code:**

If you are optimistic about this decentralized transaction network that may be mouth to mouth and spread from person to person.

So it is recommended that you get the invitation code when DFS price is still low. Because when DFS price increases, the invitation code will be more expensive.

Transfer 100 DFS to dfsdfsfamily, you will get a unique invitation code bound to the transfer account \(Invitation codes can be transferred and sold later\).

**Lucky Egg of trading mining \(time-limited\)**

**Design ideas:**

In the Bitcoin mining system, there is the concept of lucky value. On the basis of an average of every ten minutes, there are usually lucky miners who can calculate the hash value in advance within ten minutes and obtain miner rewards in advance. In the DFS trading mining pool, we also retain the concept of "luck". 

On average, every ten minutes, there will be a Lucky Egg. A transaction that meets the following two conditions can be regarded as triggering Lucky Egg receiving additional rewards:

1. The transaction volume is less than 5000 EOS. 
2. The transaction time is within 60 seconds of the first minute of each ten minutes.

**Code example:**

```text
uint64_t lucky_key = current_time_point().sec_since_epoch() / 60;
bool is_lucky_hint = lucky_key % 10 == 0;
double discount = trading_mining_discount; //default 0.2
if (is_lucky_hint && trading_fee.amount <= (5000 * 10000))
{
   discount = 1.5;
}
```

In the trading mining algorithm, there is a discount coefficient, which indicates the discount strength of the transaction fee.

Trigger the reward of Lucky Egg, and you will get a reward of discount=1.5. It means that this transaction fee is not only free, but also an additional DFS token reward.

However, the final DFS rewards obtained by trading mining are still affected by the damping parameters, pool\_weight and dfs\_price parameters.

The same 20% of the DFS from mining will enter the DSR saving pool public account, waiting for DSR allocation

**Example Case:**

1. Transaction amount 1000 EOS -&gt; EOS/DFS, 
2. Handling fee 3 EOS pool\_weight: 1.2 
3. Damping: 0.75 
4. Discount: 1.5 \(default 0.2\) 
5. DFS price: 0.5 

Suppose this transaction triggers a Lucky Egg every ten minutes:

```text
trading_mining_reward = 3 / 0.5 * 1.2 * 0.75 * 1.2 * 0.8 = 6.48 DFS 
```

Suppose this transaction did not trigger Lucky Egg:

```text
trading_mining_reward = 3 / 0.5 * 0.2 * 0.75 * 1.2 * 0.8 = 0.8640 DFS 
```

7.5 times transaction mining income every ten minutes! 

Technical miners can compete with their technologies. Mining machine manufacturers benefits from it. Market makers and liquidity providers have more risk-free profits. DFS buying demand from whales will also be fulfilled.

**2. Liquidity mining pool**

**Design ideas:**

For liquidity providers, there are two considerations.

**The first consideration: Safety**

The swap core module of DeFis Network has withstood a transaction volume of $95 million within 33 hours at its first testing and has a good foundation for security. The security audit of the contract is done by SlowMist, PeckShield, and will be audited by more reputable audit institutions.

With the support of multi-party external audit, the swap core code is reviewed line by line and word by word. The swap core code will eventually become impeccably stable. Just like a streamlined poem, changing any single word is superfluous.

**The second consideration: ROI**

Through providing any possible crypto assets liquidity and funds to Defis Network, liquidity providers, also known as market makers, first gain 0.2% transaction fee as short-term return, at the same time gain DFS tokens through liquidity mining as the long-term return that will continuously increase with the growth of DeFis Network. As mentioned before, DFS token is the first, only and most 'BTC' of DEFIs built on EOSIO blockchain which make its long-term value possible to be 'priceless'. 

Seizing the core needs, here is the Liquidity mining algorithm:

```text
 liquidity_mining_reward = 
 (liquidity * pow(apr_s, time_elapsed) - liquidity) / 
 dfs_price * damping * pool_weight;
```

apr\_s, is a manageable parameter, which represents the annualized rate of return calculated in seconds.

**Example Case:**

Parameter assumptions:

1. Average DFS market price: 1 DFS = 0.15 EOS, 
2. Liquidity mining amount: 10000 EOS. 
3. apr\_s: 1.0000000015471259828814254433382 
4. damping: 0.75 

Question: How much DFS can I get for 10000 EOS and market making in one day?

Apply the liquidity mining formula:

```text
liquidity_mining_reward =  
(10000 * pow(1.0000000015471259828814254433382, 86400) - 10000 )/
0.15 * 0.75  * 1 = 6.6840 DFS
```

Every single DFS in the network will be precious and scarce. 

**3. USDD minting mining pool**

**Design ideas:**

USDD is a stablecoin anchored to 1 USD, USDD minters mortgage other crypto assets to mint USDD through a 300% excess mortgage rate. Unlike DAI, DeFis Network has no forced liquidation when minters encounter unprecedented extreme price fluctuation, because the security of user mortgage assets is more important.   

USDD needs enough scale and more application context to become a highly efficient and mass adoption stablecoin. Therefore, USDD minting mining is precisely to promote the development of USDD. The USDD coin mining algorithm is very simple and similar to trading mining. 

PS: Development team is trying to enhance DFS incentive for users who mortgage EOS to mint USDD.

**USDD Minting mining algorithm:** 

```text
mint_mininng_reward = mint_fee / dfs_price * discount * damping
```

**Example Case:**

Parameter assumptions:

1. Average DFS market price: 1 DFS = 0.15 EOS, 
2. Minting 10000.0000 USDD, fee 0.3% = 30 USDD = 10.7 EOS 
3. Discount: 0.2, 
4. Damping 0.75 

Question: How much DFS can i get for minting 10000 USDD in thie example?

Apply the USDD minting mining formula:

```text
mint_mininng_reward = 10.7 / 0.15 * 0.2 * 0.75 = 10.7 DFS
```

### \*\*\*\*

### **DSR: DFS Saving Rate**

**Design ideas:**

If you are familiar with Ethereum MakerDao. Then you must be familiar with the design of DSR \(DAI Savings Rate\). It is simple, free and powerful.

DFS Saving Rate is also named as DSR, which is one example of how blockchain technology can provide equal financial services to everyone.

DeFis Network's DSR is an underlying protocol with guaranteed income. Not only can it be easily used by individuals, but it can also be easily accessed by third-party such as exchanges and wallets etc.

**DSR income source:**

Every time a DFS is issued, 20% of it will be stored in the public DFS saving pool, and the remaining 80% will be sent directly to all miners.

The DFS accumulated in the DFS saving pool will once again be distributed linearly to all those who deposit DFS in the DFS saving pool through the guaranteed income algorithm. Interest calculated per second. Deposit and withdraw at any time.

The meaning of DSR to DFS is similar to the meaning of REX to EOS. The stronger DSR, the stronger EOS Defi ecosystem.

DeFis Network team has a plan to regularly spend X% profit to repurchase DFS and deposit it in DFS Saving Pool to further empower DFS and DSR. Starting date and X% are to be decided.

### Development Roadmap

1. Stablecoin issuing protocol: Bank \(developed\) 
2. Liquidity protocol: Swap \(developed\)
3. Credit protocol \(under development\)
4. Synthetic asset protocol \(under development\)
5. To be continue

DeFis Network will continuously innovate and develop more protocols to grow the network. 

### Launch Plan

**Launch Time:** 14 Aug 2020

**Launch Statement:**

The source code of DeFis Network is contributed and maintained by enthusiasts of DeFis Network community. The project is started and operated by DeFis Network community and enthusiasts. 

The DFS token distribution method adopts the fair competition distribution method most similar to Bitcoin. The income generated by the protocols is fairly distributed to network contributors, miners, traders and DFS token holders through secure smart contracts.

**Code Copyright Notice:**

All codes under the DeFis Network adopt the GPL open source protocol. Allow any individual or organization \("licensee"\) to research, review and analyze the software in private. The licensee may quote and modify this software under the constraints of the GPL open source agreement. In any case, the copyright owner is not responsible for any damage or other liability arising from or related to the software due to incorrect use, modification, or contract, infringement or other aspects.

**Risk Warning:**  

The smart contract for this project has been audited by professional security teams. But there may still have unexpected risks. Please use at your own risk.

### Conclusion

DFS token is the first and the only 'BTC' of DEFIs built on EOSIO blockchain. 

DeFis Network is currently the most decentralized-finance-protocols aggregated finance network on EOSIO blockchain that will continuously evolve and grow.  

It's just born, an infant. So please forgive us that we can't disappear like Satoshi. Instead the founding team have to live in the birth day for ever to keep exploration, innovation and modesty.

The surprise has not yet begun. 

> The surest way to corrupt a youth is to instruct him to hold in higher esteem those who think alike than those who think differently.          ----  Friedrich Wilhelm Nietzsche, 1881.


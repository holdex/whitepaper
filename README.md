# Holdex Protocol: a community incentives ecosystem

## Abstract
> Whether we are trading commodities, currencies, capital, collectibles, or utilities – the community is paramount to the success of any such market.
The Holdex Protocol is a novel system for community incentives based on the dynamics of trust and influence across Crypto, which we consider a community-powered phenomenon. The purpose of this system is to:
- provide a way to assess engagement from real users;
- reward meaningful engagement with real value; and,
- drive community management models for Blockchain protocols and applications towards being more user-centered. 

The basis of the system is the use of a personal blockchain-based token named `ki` which is unique to each user and represents the level of a user's influence and participation within the community. 

The system is meant to address, from its design, three issues found with existing incentivized community platforms:
- prevent community-level Sybil attacks i.e. fake accounts and manipulation by sockpuppetry;
- provide token-agnostic rewards whose value is *directly* tied to positive community actions; and,
- provide a flexible infrastructure that supports the wide scope of desirable positive community actions, from referrals to publishing to governance. 
No other platform or protocol is designed to address all these issues simultaneously. The above-named issues (together with poor user experience) has so far seen other blockchain-based incentivized community platforms unable to gain widespread adoption, including by "Crypto teams" (i.e. protocol developers and managers) who should be a natural fit for early adopters. The result is that, in the age of nascent "web3" platforms, Crypto teams still rely heavily on a variety of "web2" platforms to carry out the bulk of their community management processes, which are increasingly more important to the success of any protocol in a saturated attention market.

The system is also able to accept external tokens and make them compatible with its internal community incentives economy. Thus, real value can be injected into the system in a permissionless manner. The system provides integrations with DEXs in order to provide convenience to all participants so they can enter and exit the internal marketplace with the tokens of their choice.

To represent trust in the system, an endorsement action named `kudos` facilitates users exchanging their `ki`. A user that receives many 'kudos' has a 'ki' that is more trusted within the system. As more users give `kudos` to each other and become interconnected, personal `ki` converges in a standard to measure positive community actions which can be anchored within the system with real value, for the benefit of users and protocols alike.

## What is the Holdex Protocol?

Since the launch of Bitcoin, the Internet of Value has become an ever-possible realization within our lifetimes. 

At its core, the Internet of Value presents us with an opportunity to create online spaces without middlemen, where people can freely exchange value amongst each other, eliminating third-party costs without a single-point-of-failure. This is naturally a social phenomenon, a community endeavor, as commerce always is. Whether we are trading commodities, currencies, capital, collectibles, or utilities – the community is paramount to the success of any such market.

_Building a community_ and _maintaining a community-oriented ethos_ in any new, growing, or mature Blockchain market _is one of the main challenges_ of any team pushing forward the success of a particular cryptoasset. There are thousands of teams working with increasingly complex stacks of tools to maintain high community engagement. To effectively conduct community-building these teams must: 
- onboard new members and provide support in communication channels;
- launch campaigns to increase awareness and support advocacy; 
- conduct governance. 

Often, explicit incentives are implemented. But programs to correlate incentives with good community outcomes are complex and expensive to implement, so most teams forgo them – casting aside the potential of a strongly-engaged community.

The Holdex Protocol is Blockchain's native community incentives protocol. It is completely permissionless, so anyone can join the network without approval. It is designed to complement the existing reality of the Blockchain space, where cryptoassets can be plugged-in to anchor the value of the ecosystem rewards. Users who perform meaningful community actions are eligible to receive ecosystem rewards. The protocol is based on a social graph with a trust-building mechanism that protects against fake accounts and other attacks that would aim to malignantly seize the value in the system. In this latest regard, we have been inspired by the implementation of the Circles protocol for a *Universal Basic Income (UBI)*.

The overall result is a highly-composable way of rewarding any crypto community for its continued support and engagement.

## Earning incentives

The incentive system is made up of the interactions between individual users in the system. Individual users band together to form communities within the system. A community action is an action that has an effect on other members of the community. Whenever a beneficial community action is performed within the ecosystem, a user is said to earn `ki`. Each user's `ki` is a *personal asset*, which operates under a defined set of rules. Whenever a new user enters the ecosystem, a `ki` personal to himself is created. As a user performs community actions, new units of `ki` (i.e. points) are minted and awarded to that person.

```
Joshua joins the ecosystem, creating 'JoshuaKi'
Joshua performs some community action, worth 5 'ki points'
Joshua now has 5 'JoshuaKi'
```

Note that a user's `ki` is personal to that user. The example below illustrates that.

```
Joshua joins the ecosystem, creating 'JoshuaKi'
Joshua performs some community action, worth 5 'ki points'
Joshua now has 5 'JoshuaKi'
Artur joins the ecosystem, creating 'ArturKi'
Joshua transfers his 5 'JoshuaKi' to Artur
Joshua now has 0 'JoshuaKi' while Artur has 5 'JoshuaKi'
Both Joshua and Artur perform some community action, worth 5 'ki points'
Joshua now has 5 'JoshuaKi' while Artur now has 5 'JoshuaKi' and 5 'ArturKi'
```

### Internal economy: the tokenomics of `ki`

The number of `ki` in the ecosystem is based on the number of community actions done by users and the value of each action. No `ki` is minted outside of providing positive community actions. There is no cap to the supply of `ki`. The "inflation" in the system happens as more users join and as users become more active. The only way to get "diluted" is to remain inactive for long. This is meant to reward activity in the system.

All users start their journey with no `ki` and `ki` cannot be bought from a reserve or a pre-mined source, it can only be earned within the system by performing positive community actions. 

These are examples of actions that earn `ki`. The exact actions are set by protocol governance:
- receiving a `pump` or upvote on a post or comment.
- starting a `thread` that receives high engagement e.g. a high ratio of upvotes, replies, or shares.
- bringing new users into the system, once these users receive enough `kudos` i.e. are trusted by other users.

## Trusting rewards

In order to create a useful rewards ecosystem, users endorse each other. This endorsement is a proxy for trust. When a user trusts another in the community, it is signaling their community actions as "real". They tell the whole ecosystem that the other user's `ki` is as real as theirs. We call this endorsement action a `kudos`. Any other user whose `ki` you trust can automatically trade it for any `ki` on your possession at a one-to-one exchange rate.

```
Artur gives a 'kudos' to Charlie, so Artur trusts 'CharlieKi'
Artur has 10 'JoshuaKi'
Renée has 10 CharlieKi
Renée gives 5 CharlieKi to Artur and takes 5 JoshuaKi from him
Renée now has 5 CharlieKi and 5 JoshuaKi while Artur now has 5 JoshuaKi
```

Giving `kudos` prevents a trivial attack, however one that happens every day in other community platforms. Since any Blockchain wallet can join the system and start minting `ki`, someone can create multiple wallets and perform the same action multiple times to earn themselves a multiplier on `ki` rewards. This devalues the system. Protecting against such attacks is technically called *Sybil resistance*, and the `kudos` mechanism provides that resistance for Holdex.  

### Transitive exchange

A wide network of users who give `kudos` to one another creates utility in the incentives as it allows for complete strangers to measure the *chains of trust* in the network and focus their efforts on earning access to those chains. A mechanism called *transitive exchange* allows the Holdex ecosystem to harness the transitive properties of both social networks and trust itself.

```
Artur gives a 'kudos' to Joshua, so Artur trusts 'JoshuaKi'
Joshua gives a 'kudos' to Charlie, so Joshua trusts 'CharlieKi'
Joshua has 10 'JoshuaKi'
Charlie has 10 'CharlieKi'
Charlie wants to give Artur 5 'ki points'
Charlie gives 5 'CharlieKi' to Joshua and takes 5 'JoshuaKi' from him
Charlie gives 5 'JoshuaKi' to Artur
```

!['transitive exchange' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/transitive-exchange-diagram.png)

This chain of trust can be extended indefinitely.

```
Artur gives a 'kudos' to Joshua, so Artur trusts 'JoshuaKi'
Joshua gives a 'kudos' to Charlie, so Joshua trusts 'CharlieKi'
Charlie gives a 'kudos' to Renée, so Charlie trusts 'RenéeKi'
Joshua has 10 'JoshuaKi'
Charlie has 10 'CharlieKi'
Renée has 10 'RenéeKi'
Renée wants to give Artur 5 'ki points'
Renée gives 5 'RenéeKi' to Charlie and takes 5 'CharlieKi' from him
Renée gives 5 'CharlieKi' to Joshua and takes 5 'JoshuaKi' from him
Renée gives 5 'JoshuaKi' to Artur
```

!['extended transitive exchange' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/extended-transitive-exchange-diagram.png)

Of course, we do not expect these chains of trust to get very long as the system grows. We are informed by the idea of "six degrees of separation" popularized in John Guare's play, by the 'small-world' experiment of Stanley Milgram in the 60s, and more recently by Duncan J. Watts Steven Strogatz at Cornell. Since the Holdex ecosystem finds the shortest route in a chain, a trustworthy individual may need no more than six "hops" in the chain to reach everyone else in the network.

### Limits to trust

Through the `kudos` mechanism, as more trust is built within the Holdex ecosystem, the *fungibility* of `ki` in the system increases, driven by those users able to accrue the most trust / receive the most `kudos`. For new users, this presents the opportunity for a "shortcut": get a `kudos` from a "superconnected user" and then gain access to his chain of trust. This presents a dilemma for the "superconnected user", 

```
25 people trust 'JoshuaKi'
Artur is new, so only Joshua trusts 'ArturKi'
Artur has 100 'ArturKi'
Joshua has 100 'JoshuaKi'
Artur gives 100 'ArturKi' to Joshua and takes 100 'JoshuaKi' from him
Artur can now give 'ki' to 25 people (and their friends, and friends of friends, etc)
Joshua can now only give 'ki' to Artur
```

!['limits to trust' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/limits-to-trust.png)

The superconnected user may indeed have real trust in the new user (possibly know him personally even) and want to give him a headstart with a timely `kudos`, but doing so will potentially result in the superconnected user being locked out of his chain of trust. In order to encourage this type of interaction, the Holdex system allows for *qualifying* a `kudos` by setting a limit to how much of the endorser's wallet can be taken by the recipient's `ki`. The limit can be *relative* (a percentage or share-of-wallet), absolute (a maximum amount), or time-based (e.g. a maximum per month).

```
25 people trust 'JoshuaKi'
Artur is new, so only Joshua trusts 'ArturKi'
Joshua qualifies his 'kudos' to Artur with a limit of 10 `JoshuaKi`
Artur has 100 'ArturKi'
Joshua has 100 'JoshuaKi'
Artur gives 10 'ArturKi' to Joshua and takes 10 'JoshuaKi' from him
Artur can now give one tenth of his 'ki' to 25 people (and their friends, and friends of friends, etc)
Joshua sets aside his 10 'ArturKi' to spend once Artur has received more 'kudos' from other users
Artur gets 10 people to give him 'kudos' and trust 'ArturKi'
Joshua raises his limit for Artur to 100 `JoshuaKi`
```

Qualifying a `kudos` with a limit makes it easier for new users to the system to build their reputation gradually.

### Defending against fakes

As mentioned before, one of the main considerations in designing the Holdex ecosystem is to protect against fake accounts. Let us see what happens when a fake account gets access or is connected to someone in your trusted network.

```
Artur gives a 'kudos' to Joshua, so Artur trusts 'JoshuaKi'
Joshua makes a fake account, and gives it a 'kudos', trusting 'FakeKi'
Joshua has 10 'JoshuaKi'
FakeJoshua has 10 'FakeKi'
Joshua wants to settle a debt to Artur worth 10 'ki points' using 'FakeKi'
FakeJoshua gives 10 'FakeKi' to Joshua and takes 10 'JoshuaKi' from him
FakeJoshua gives 10 'JoshuaKi' to Artur
```

!['fake accounts' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/fake-accounts.png)

Essentially, just like Artur in our example, a user only ever receives `ki` he trusts. Conversely, a user like Joshua can only transfer `ki` that other users trust. The `kudos` mechanism guarantees that, even if a malicious user were to create, say, 100 fake accounts, and give `kudos` to all of them, they would still only be able to transfer their own `ki` (e.g. Joshua would only be able to transfer `JoshuaKi`), since that would be the only `ki` other users have trusted. This is why giving `kudos` is (and should be) a big deal in the Holdex ecosystem.

### Anchoring real value 

In order to provide a way to encourage users in the ecosystem to perform valuable community actions, we allow for a mechanism that allows incentivizers to "anchor" an external incentive (in the form of an ERC-20 token) to the `ki` mechanism.  We call this mechanism *value anchoring*. A user who wants to be an incentivizer provides an incentive and sets a conversion factor between that incentive and `ki`. The system will retain custody of the incentive and create a 'wrapped version' of the incentive for internal exchange. In combination with the `kudos` mechanism, value anchoring can be used to encourage "gatekeeping", or the protection of trust within the community, thus increasing the value on those chains of trust that the incentivizer belongs to.

```
Rune works for Maker and wants to be an incentivizer
Rune provides 1 'MKR' as an incentive, and a 'ki' swap rate of 0.01
The 'MKR' is held in a vault, known as the 'xMKR' vault, and is equivalent to 100 'xMKR'
Rune's 'ki' increases by 100, to 100 'RuneKi'
'RuneKi' can now be exchanged 1:1 with 'xMKR'
Rune starts a competition for a 'guide to the Dai savings rate'
Manny joins the competition is declared the winner
Manny has 100 'MannyKi'
Rune gives a 'kudos' to Manny and sets a limit of 100
Manny gives 100 'MannyKi' to Rune and gets 100 'RuneKi' from him
Manny swaps the 100 'RuneKi' for 100 'xMKR' with the vault
Manny redeems the 100 'xMKR' for 1 'MKR' at the vault
```

!['anchoring real value' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/anchoring-real-value.png) 


Notice that Manny had 100 `ki` to swap with Rune. He may have gained `ki` in the process of the competition (e.g. by receiving `pumps` or upvotes on his submission) or before. With the endorsement of Rune, Manny's `ki` becomes more valuable, as it is now indirectly connected to the `xMKR` vault within Holdex. As Rune and others in the Maker community seek to use the Holdex ecosystem more often to drive their community forward, initial contributors like Manny stand to gain more from the trust they gained early on. As this trust can be withdrawn or increased, Manny has an incentive to act as a gatekeeper himself, even though he did not start out as part of any Maker "team". 

Anchoring value in Holdex is designed so that protocol developers or "Crypto teams" can grow out trust from their core team members and other stakeholders like official community managers, admins, and moderators to special community members and others who can build an ever-stronger "chain of trust". However, any user can become an incentivizer, and there is no requirement for an incentivizer use a particular ERC–20. For example, an activist member of the Maker community can create an incentive based on `DAI`, or `wBTC`, or `wETH`. 

In order to further facilitate the participation of users and Crypto teams alike, convenience functions and native integrations with DEXs are built into the protocol so that entering and exiting the "internal Holdex economy" can be seamlessly done with any ERC–20 token.

### Promoting promoters

As we have seen throughout, the `kudos` mechanism, essentially an endorsement or "vouching" mechanism between users, is the only way to give and gain trust in the Holdex ecosystem. The ability to give, receive, and qualify this trust, as formalized in the `kudos` mechanism, is also the feature that allows for combating fake accounts in the Holdex ecosystem. However, in order to facilitate and encourage users to build trust and interact in the absence of direct trust in certain situations, Holdex provides a variety of trust-building features, as well as user controls for a *permissioned exchange fee*.

```
Manny is well-known, 100+ people trust 'MannyKi'
Adam is relatively new, only 5 people trust 'AdamKi'
Adam wants to be on Manny's 'chain of trust', asks for a 'kudos'
Manny only gives 'kudos' to long-time holders of Ethereum
Adam uploads his self-sovereign identity (SSI) to his profile
Adam verifies the Ethereum Name Service (ENS) address 'adam.eth' as his
Adam receives the 'VerifEyed™' status at Holdex
Manny sees Adam's updated profile, gives Adam a 'kudos'
```

!['getting verifeyed' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/getting-verifeyed.png) 

```
Adam has become well-known, 500+ people trust 'AdamKi', and his 'chain of trust' includes many incentivizers
'AdamKi' is highly fungible, at the moment it can be redeemed for 'xETH', 'xBTC', and 'xUSD'.
Andre is relatively new but very active, he has 105 'AndreKi'
'AndreKi' is on the 'chain of trust' of 'xYFI'
Andre wants 'xETH' but isn't in any 'chain of trust' with 'xETH'
Adam has not given a 'kudos' to Andre, so 'AndreKi' cannot be swapped for 'AdamKi'
Andre requests Adam a 'permissioned swap' of 100 'AdamKi'
Adam sets the 'permissioned exchange fee' at 5%
Under the 'permissioned swap' rules, Andre will get 100 'AdamKi' from Adam, and give Adam 105 'AndreKi' (100 + 5% fee)
Andre accepts, gets 100 'AdamKi' and gives Adam 105 'AndreKi'
Adam swaps his 'AndreKi' for 'xYFI' and uses it to redeem 'YFI'
Andre swaps his 'AdamKi' for 'xETH' and uses it to redeem 'ETH'
```

!['promoting promoters' diagram](https://storage.googleapis.com/holdex-public/thread/Holdex%20Protocol%20Lightpaper/promoting-promoters.png) 

As seen in the example of Adam, there are many opportunities for users to become *superconnectors* within the Crypto–Verse, acting as a link for many communities. Through the mechanism of the *permissioned exchange fee*, this status can be turned into a service where users can be compensated for their risks. The more connections a user has, the more in-demand he will be.

## Governance

The Holdex Protocol, like other decentralized protocols, will allow its main stakeholders to jointly decide on the direction of the protocol, a mechanism known as *governance*. 

As a primer, let us identify the main purpose of governance is to maximize *protocol health*, understood as:
- the capacity for the protocol to grow and to do so sustainably: in no. of users, *total value locked (TVL)*, market capitalization or any other measure that is capable of accurately assessing the overall value of the protocol itself.
- the effectiveness of the protocol in farly rewarding its participants: like highly-active users of the protocol, developers who build on the protocol, and influential community members who take the lead on governance matters.
- the ability of the protocol to thrive when faced with external stressors i.e. shocks, volatility, noise, mistakes, faults, attacks, or failures. This property is known as *antifragility* and goes beyond mere *resilience* or *robustness*. 

The following definitions should be kept in mind:
- *governance token*: a token whose purpose is to provide a right to participate in governance, usually by voting.
- *protocol fees*: fees charged by a protocol whenever a service is provided within the protocol e.g. swapping tokens, wrapping/unwrapping tokens, facilitating a trade. Protocol fees are usually called *admin fees* when the fees are directed to the protocol's treasury.
- *treasury*: in the context of governance, a wallet where funds belonging to the protocol are stored. The amount of protocol fees going to the treasury, and the destination of outlays from the treasury, are decided by governance.

### Governance ethos and philosophy

The protocol will be community-managed by the holders of a governance token called `HLDX`. Holders of `HLDX` will be able to direct the future of the protocol, for example, by voting on *Holdex improvement proposals (HIPs)*, retaining rights to determine whatever controls are built-in the protocol (e.g. for protocol fees), as well as the restructuring the process of governance itself (*meta-governance*).

The `HLDX` governance token will not be pre-mined or for sale, instead, it will be distributed to liquidity providers and users of the protocol in a *liquidity mining program* as well as *community incentives program*. A percentage of the distribution will be sent to a variety of protocol funds set aside for the purposes of operations, incentivization of the internal market, and promoting a healthy ecosystem of partners and dApps building on the protocol.

The holders of `HLDX` should expect to be actively involved in the success of the Holdex Protocol, and to support the mission and vision of Holdex of realizing the Internet of Value within our lifetimes. 

### The `HLDX` token: protocol tokenomics

Using continuous emissions, during the first year, we will issue 1,000,000 $HLDX and distribute it as follows:
- 5% will be sent to the **development fund** to fund regular operations.
- 10% will be sent to the **smart treasury** (please read this [excellent paper on smart treasuries by Placeholder VC](https://www.placeholder.vc/blog/2020/9/17/stop-burning-tokens-buyback-and-make-instead)), which will operate as:
  - a *liquidity provider of last resort*
  - an *automatic buyback machine*
  - a *token issuance pool* for:
    - a *community incentives fund* to provide for special community incentives programs as determined by governance.
    - an *ecosystem fund* to invite the financing of community proposals that aim to improve the Holdex Protocol.
- 20% will be distributed directly as **community incentives program** to celebrate the protocol's launch
- 65% will be distributed directly to liquidity providers as a **liquidity mining program** to bootstrap the initial liquidity of the protocol. The main mechanism will be via an `ETH`–`HLDX` pool (i.e. the power pool), and although there may be other pools rewarded as part of the program, at no point will the `ETH`–`HLDX` power pool receive less than 50% of the distribution.

The Holdex Protocol will collect protocol fees as set by governance. For example, at launch, the following fees will be set by default and come with governance controls so the community can vote to adjust them in time:
- a 5% admin fee to *unwrapping* a Holdex-wrapped token in a Holdex vault.
- a 3% admin fee to *permissioned exchange* transactions.
- a 1% admin fee to using *convenience functions*.
The protocol fees will be collected in `ETH` as the native currency and *sent to the smart treasury*, this creates automatic buyback pressure by default. The smart treasury is controlled by governance so any use of the treasury funds for payments or direct transfers to say, `HLDX` power pool LPs, shall be approved by governance. 

The regular operations to be funded by the `development fund` include:
- running costs of hosting and operating the protocol
- compensating the protocol's core development team
- compensating contractors brought from time to time to aid in the protocol's development
- funding research crucial to the advancement of the protocol
- compensating advisors to the protocol's core development team
The budget of the development fund shall be handled by the protocol's governance.

The `community incentives fund` and `ecosystem fund` are meant to issue grants, the former to finance incentives to users of the Holdex Protocol as rewards for exceptionally positive community actions, the latter to individuals and teams working for the betterment of the Holdex Protocol and its community in the following "areas of improvement":
- integrations (e.g. with other community tools)
- UX/UI design (e.g. for improving the experience of using the protocol)
- tokenomics modeling (e.g. to fine-tune rewards and create an evermore robust ecosystem).
- tooling (e.g. for ease-of-development and novel use cases on the Holdex Protocol).
- growth, governance, and community (e.g. to foster the adoption of the Holdex Protocol).
The issuance of grants shall be handled by the protocol's governance.

The distribution timetable will consist of 20 `tranches` of 50,000 $HLDX each, divided into 12 `epochs`, each corresponding to roughly 1 month, as follows:
- in every `epoch`, a minimum of 1 `tranche` will be distributed – for a subtotal of 12 `tranches`
- an additional 'tranche' will be distributed on the 6th, 9th, and 12th `epoch` – for a subtotal of 3 `tranches`
- during the first 3 `epochs` (the launch period) additional `tranches` will be distributed – for a subtotal of 5 `tranches`
  - an additional 2 `tranches` will be distributed on the 1st `epoch`
  - an additional 2 `tranches` will be distributed on the 2nd `epoch`
  - an additional `tranche` will be distributed on the 3rd `epoch`
  
After the first year, we will target an annual increase of 7% in the supply of $HLDX in perpetuity, so as to reward active participants in the protocol over passive holders. The governance of the Holdex Protocol will decide the manner in which to continue the distribution. 

During the first year, to steer the Holdex Protocol from launch towards a mature *decentralized autonomous organization (DAO)*, a *multisig* "board of directors" will retain effective control over the protocol and its funds, starting with the core development team and adding community members throughout the course of the year, as follows.
- For the first 6 `epochs`, a 2/3 multisig wallet with all members coming from the development team
- At the end of the 6th `epoch`, the 2/3 multisig will be replaced with a 3/5 multisig after the election of 2 community members to join the original 3 members.
- At the end of the 9th `epoch`, a 3/5 multisig will be replaced with a 5/9 multisig after the election of 6 new community members to join the original 3 members. 
- At the end of the 12th `epoch`, the 5/9 multisig will remain but all 9 members will be elected from the community, for 3 `epochs`.
- every 3 `epochs`, the community will elect a new slate of multisig "directors".

To directly participate in governance, `HLDX` holders must provide liquidity in the power pool (i.e. the official `ETH`–`HLDX` pool) and vote-lock their LP tokens on a *voting escrow* contract. In other words, a vote-locking system will be implemented, where power pool LPs can boost their liquidity mining rewards and receive a corresponding amount of `veHLDX` (*voting escrow HLDX*) by time-locking their LP tokens on the voting escrow contract. The more `HLDX` is locked, and the longer it is locked, the more `veHLDX` (i.e. *voting power*) will be received and the higher the boost to liquidity mining rewards.

The base of voting power will be determined by taking the square root of `veHLDX`, a system known as *quadratic voting*. This means the Holdex Protocol will be less biased towards big holders.

### Tying `ki` and `HLDX`

As previous described, `ki` is a personal token earned by each user when performing positive community actions. Furthermore, real value can be anchored into the system by any incentivizer (e.g. a protocol development team, say Maker). 

To launch the protocol, 200,000 $HLDX are set aside from the first-year emissions for a **community incentives program**. This means, the same dynamic to anchor value by incentivizers will be used to inject 200,000 $HLDX into the internal economy of `ki`, with the Holdex Protocol itself as the incentivizer.

We expect the following community actions to be encouraged with these `HLDX` incentives (a detailed list will be available in due time):
- promotion of the Holdex Protocol to incentivizers.
- promotion of the Holdex Protocol to other users in the Crypto-Verse.
- guiding new users in understanding the mechanics of the internal economy of `ki`.
- becoming a *superconnector* that facilitates *permissioned exchange* within the ecosystem.
- actively participating in the governance of the protocol.

To this *initial* 200,000 $HLDX, a *ongoing* incentives will be added, in the forms of grants from the smart treasury, as well as apportionements from the *targeted inflation* in later years. Therefore, from its very beginning, `ki` will be anchored by value with `HLDX` as the first use case of the anchoring mechanism.

--- 

**Conclusion**

The Holdex Protocol is the future of Crypto community incentives, for a variety of reasons:
- Due to in-build *Sybil resistance*, it is capable of encouraging real community actions and measure them free of mass manipulation and fake accounts
- Through the *value anchoring* mechanism, incentives that truly engage the community are possible. The same incentives that would be near-wasted on an airdrop or another mass distribution of valuable tokens can be implemented on Holdex, get the same or more true reach (once you take all the fakes out), plus uniquely reward community members who get involved early.
- With the *permissioned exchange fee* mechanism, highly-active users like promoters and other *superconnectors* across the Crypto community can monetize their influence and access.

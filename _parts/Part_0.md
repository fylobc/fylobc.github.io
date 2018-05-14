---
layout: collection
title: "The Minimum You Need to Know"
---

<h2>How Bitcoin works</h2>

<p>Bitcoin is a digital payment system developed in 2009 by an anonymous person, or group of people, going under the name <a href="https://en.wikipedia.org/wiki/Satoshi_Nakamoto">Satoshi Nakamoto</a>. Owners of Bitcoin have an address – a set of alphanumeric characters which identify their account – to which Bitcoin can be added or taken away. Each account is part of a global ledger which contains all of the account addresses, the number of Bitcoin in each account and all of the transactions that have taken place on the network. Bitcoin are divisible, so an account could have 4.2 Bitcoin in it, for instance, and they don't actually represent anything; they're just numbers on the ledger.</p>

<p>When one account (account A) sends a Bitcoin to another account (account B), a message is broadcast to the entire Bitcoin network (i.e., everyone who has the ledger) to update the ledger so that one Bitcoin is removed from account A and one Bitcoin is added to account B. But this message is encrypted using account A’s private key, which is like a digital signature that is unique to account A, and the message must be decrypted before the ledger can be updated.</p>

<p>Bitcoin “miners” have a copy of the ledger and race to decrypt the message by solving a math problem (they don't need to know the private key to decrypt the message). Decrypting the message verifies the transaction and every copy of the ledger is then updated to include the transaction. Because every member of the network has a copy of the ledger, they can all check to make sure that nothing fishy has happened, like someone trying to go back and undo a transaction that happened a few days ago.</p>

<p>The miner who solved the problem is rewarded with some newly minted Bitcoin as well as a transaction fee, which are the incentives for miners to maintain the ledger. Importantly, the Bitcoin protocol is set up so that if someone tries to cheat the system by double-counting or committing fraud in some way, their message won’t be decrypted. The difficulty of the math problem is also adjusted to make sure that a new Bitcoin is mined roughly every ten minutes.</p>

<p> The last thing to know is that the total number of Bitcoin is fixed at 21 million, and about 17 million have been mined so far. Once all of the Bitcoin have been mined, miners will only compete for the transaction fees.</p>

<p>So Bitcoin has a few important properties:
<ul style="font-size:x-large;">
  <li>it lives entirely on the internet</li>
  <li>it’s anonymous (each account is just an address)</li>
  <li>it’s decentralized (no one person controls the network)</li>
  <li>it's transparent (anyone can look at the ledger)</li>
  <li>it’s very hard to cheat, fake or commit fraud</li>
  <li>there’s a limited supply, and new Bitcoin are minted at a constant rate.</li>
</ul>
</p>

<p>One issue is conglomerates of miners: groups of miners who pool their resources together. If the conglomerate becomes too big (basically if 51% of the miners team up) it can control the mining process and do naughty things like double spend, commit fraud, etc. Basically, Bitcoin wouldn’t be decentralized anymore. This is another danger of Bitcoin: you have to trust that no single entity will dominate the mining. <a href="https://en.wikipedia.org/wiki/Ghash.io">A conglomeration of miners did get too big once</a>, but miners voluntarily left in order to keep the Bitcoin network safe.</p>


<h2>The Blockchain Technology</h2>

<p>The key technology underlying Bitcoin is the way the decentralized ledger is set-up. This technology is called the blockchain. You can think of <i>blocks</i> as being individual transactions, which are linked together because when one transaction is verified all of the transaction that happened before it are also verified.</p>

<p>Besides digital money, there are many other things the blockchain technology could be applied to: land registration, health records and online voting. With all the excitement around it, one has to think carefully about when its appropriate to use blockchains; many current applications are probably a waste of time, or may make underlying problems worse. The key is to think about trust: every transaction can be verified, it's impossible to cheat the system and the network does not rely on a central authority. To take the example of medical records, you wouldn't have to worry about a patient or doctor altering someone's records. On the other hand, if you aren't so worried about trust then it may be better to use a centralized network, which is easier to maintain. <a href="https://medium.com/@jimmysong/why-blockchain-is-hard-60416ea4c5c">This article by Jimmy Song</a> is a good reference for thinking about these things.</p>














---
layout: collection
title: "Part 0: The Minimum You Need to Know About Bitcoin"
---


<p>Bitcoin is a digital payment system. Owners of Bitcoin have an address – a set of alphanumeric characters which identify their account – to which Bitcoin can be added or taken away. Each account is part of a global ledger, which has all of the account addresses and the number of Bitcoin in each account (note that Bitcoin are divisible, so an account could have 4.2 Bitcoin in it, for instance).</p>

<p>When one account (account A) sends a Bitcoin to another account (account B), a message is sent to the entire Bitcoin network (everyone who has the ledger) to update the ledger so that one Bitcoin is removed from account A and one Bitcoin is added to account B. This message is encrypted using account A’s private key, which is like a digital signature except.</p>

<p>Bitcoin “miners” have a copy of the ledger and race to decrypt the message by solving a math problem. Decrypting the message verifies the transaction and every copy of the ledger is then updated to include the transaction. If someone tries to cheat the system by double-counting or committing fraud in some way, their message won’t be decrypted. The miner who solved the problem is awarded some new Bitcoin as well as a transaction fee as an incentive for miners to maintain the ledger.</p>

<p>(The total number of Bitcoin is fixed at 21 million, and about 17 million have been mined so far. Once all of the Bitcoin have been mined, miners will only compete for the transaction fees.)</p>

<p>From this, you can see that Bitcoin has a few important properties:
<ul style="font-size:x-large;">
  <li>it lives entirely on the internet</li>
  <li>it’s anonymous (each account is just the address)</li>
  <li>it’s decentralized (no one person controls the network)</li>
  <li>it’s very hard to fake or commit fraud</li>
  <li>there’s a limited supply.</li>
</ul>
</p>


















---
layout:     post
title:      "Timestamping hashes"
subtitle:   "on the blockchain"
author:     "Riccardo"
---

## Timestamping hashes on the blockchain

You can now hash documents and commit them to the blockchain simply by sending an email:

<h4>
<div class="alert alert-info center-block text-center" role="alert">
  <span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> <a class="alert-link" href="mailto:timestamp@eternitywall.it">timestamp@eternitywall.it</a>
</div>
</h4>

*A hash of a document in the blockchain acts as a proof of existence of the document at a certain point in time.*

Beware that this feature is only in **Beta** right now, as such we only commit document hashes once a day.

### Let me know the details

At Eternity Wall we recognise that there is a big difference between putting an entire document in the blockchain and putting a hash of a document in the blockchain.

### Data in the blockchain

By putting the entire document in the blockchain, you get eternal storage, uncensorability, independence and a provable creation date.

### Hash of data in the blockchain

Alternatively, putting the hash of a document in the blockchain means you, or somebody you trust, has to keep the original document around so you can still have a provable creation date. You are losing the independent, uncensorable and eternal properties of the blockchain, right?

### So, why should I not just put everything on the blockchain?

The blockchain is expensive. Decentralization is a tough business. It takes a lot of resources for each node within a trustless network to come to a complete consensus on what data exists in the blockchain. You must pay the network for every byte in a transaction, and that can make document storage quite expensive.

Additionally, putting everything in the blockchain means anyone, anywhere can read it at any time - by computing the hash and sticking that in the blockchain instead, the contents of your document remain completely private.

### Why timestamping hashes?

The merkle tree data structure means you can create a tree of multiple hashes representing a file and simply commit the root hash to the blockchain. The hash in the root of the tree acts as proof of each hash within the tree's branches. This makes it even cheaper, as you only have to commit a single hash.

### What about ownership?

It's up to the user, but with our current email API to sign documents with a PGP key or an Estonian E-residency to prove ownership.

### Is Eternity Wall storing the documents?

Eternity Wall only keeps your documents for as long as it takes to compute the hash. They are deleted immediately after the hash is computed.

However attachments in emails are readable during transit across the internet, so if you are really concerned about flawless privacy you should encrypt your data or wait for our client-side hashing service, which will be available soon.

### Try it now, it's free :)

<h4>
<div class="alert alert-info center-block text-center" role="alert">
  <span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> <a class="alert-link" href="mailto:timestamp@eternitywall.it">timestamp@eternitywall.it</a>
</div>
</h4>


<br>

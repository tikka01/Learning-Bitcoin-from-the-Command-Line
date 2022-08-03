# Understanding Schnorr Signatures

The Bitcoin system, or cryptocurrencies in general, revolve around the concept of digital signatures. The blockchain ledger encrypts the ownership of digital assets. Unlike  traditional notions of ownership, which are enforced by legal documents and physical signatures, the ownership of a digital currency is proven by means of digital signatures.
Varieties of Digital Signature algorithms exist  throughout, each with their own advantages and disadvantages. Since it's inception, Bitcoin has used the ECDSA scheme for the purpose of Digital Signature. 
Within the biggest proposed protocol update being discussed in the community -Taproot, is a a new digital signature algorithm called Schnorr(invented by Claus-Peter Schnorr, a German mathematician and cryptographer, back in the 1980s).

> :book: ***What is a Schnorr signature Scheme?*** Similar to the ECDSA scheme used by Bitcoin, the Schnorr signature algorithm generates cryptographic signatures for a given message, but with several advantages.A proposed future extension, it gives a new method to generate signatures (R,s) on a hash h.

>Known for its simplicity,efficiency and short signatures, Schnorr is among the first schemes whose security is based on the intractability of discrete logarithm problems.  

> It was covered by U.S. Patent that expired in February 2008.The first talk of implementing Schnorr signature on Bitcoin protocol came up in the bitcoin-talk forum in 2014. Four years later Blockstream engineer Pieter Wuille made the first draft proposal for a schnorr signature scheme in Bitcoin. In Jan 2020, it was numbered BIP340, that describes the full technical definition of Schnorr Signature in Bitcoin.

>The specific version of the algorithm proposed in BIP340 is tailor-made for Bitcoin’s requirement. Reviews and changes are still going on as the proposal is still pretty much work in progress. Schnorr signature, along with Taproot and Tapscript,is proposed as a combined upgrade package for the SegWit Version 1 Bitcoin protocol.
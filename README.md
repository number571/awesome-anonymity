# Awesome-Anonymity
> A curated list of anonymity networks

Each anonymous network can be attributed to a specific problem (or to a hybrid of certain problems). Currently, there are five anonymization problems: Onion, Proxy, DC, QB, EI. If the network does not belong to one of these problems, it means that either the network is not anonymous, or a new anonymization problem has been opened. In the latter case, it is necessary to prove that the new anonymization problem actually implements an algorithm for obfuscating/hiding routing.

### Examples of non-anonymous networks

* All centralized services: Telegram, Facebook, Github, ...
* Client-secure applications: Bitmessage, RetroShare, Freenet ...

## Onion

### Research papers
* [Untraceable Electronic Mail, Return Addresses, and Digital Pseudonyms](https://dl.acm.org/doi/10.1145/358549.358563)

### Networks
* [Tor](https://www.torproject.org/ru/)
* [I2P](https://geti2p.com/)
* [Mixminion](https://github.com/mixminion/mixminion)

## Proxy

### Research papers
* [Crowds: Anonymity for Web Transactions](https://web.archive.org/web/20051212103028/http://avirubin.com/crowds.pdf)

## DC
> dining cryptographers problem

### Research papers
* [The Dining Cryptographers Problem: Unconditional Sender and Recipient Untraceability](https://www.cs.cornell.edu/people/egs/herbivore/dcnets.html)
* [Herbivore: A Scalable and Efficient Protocol for Anonymous Communication](https://www.cs.cornell.edu/people/egs/herbivore/herbivore.pdf)
* [Dissent in Numbers: Making Strong Anonymity Scale](https://dedis.cs.yale.edu/dissent/papers/osdi12.pdf)

### Networks
* [Herbivore](https://www.cs.cornell.edu/people/egs/herbivore/faq.html)
* [Dissent](https://github.com/dedis/Dissent)
* [PriFi](https://github.com/dedis/prifi)

## QB
> queue based problem

### Research papers
[Анонимная сеть «Hidden Lake»](https://github.com/number571/go-peer/blob/master/docs/hidden_lake_anonymous_network.pdf)

### Networks
* [Hidden Lake](https://github.com/number571/go-peer/tree/master/cmd/hidden_lake)

## EI
> entropy increase problem

### Research papers
[Анонимная сеть с теоретически доказуемой моделью на базе увеличения энтропии](https://habr.com/ru/articles/743630/)


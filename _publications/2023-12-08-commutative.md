---
title: "Commutative Cryptanalysis Made Practical"
collection: publications
category: manuscripts
permalink: /publication/2023-12-08-commutative
excerpt: 
date: 2023-12-08
venue: 'IACR Transactions on Symmetric Cryptology'
slidesurl: 'https://tosc.iacr.org/index.php/ToSC/article/view/11290/11534'
paperurl: 'https://doi.org/10.46586/tosc.v2023.i4.299-329'
citation: 'Baudrin, J., Felke, P., Leander, G., Neumann, P., Perrin, L., & Stennes, L. (2023). Commutative Cryptanalysis Made Practical. IACR Transactions on Symmetric Cryptology, 2023(4), 299-329. https://doi.org/10.46586/tosc.v2023.i4.299-329'
coauthors: 'Jules Baudrin, Patrick Felke, Gregor Leander, Léo Perrin, Lukas Stennes'
eprinturl: 
---

About 20 years ago, Wagner showed that most of the (then) known techniques used in the cryptanalysis of block ciphers were particular cases of what he called commutative diagram cryptanalysis. However, to the best of our knowledge, this general framework has not yet been leveraged to find concrete attacks.
In this paper, we focus on a particular case of this framework and develop commutative cryptanalysis, whereby an attacker targeting a primitive E constructs affine permutations A and B such that E ○ A = B ○ E with a high probability, possibly for some weak keys. We develop the tools needed for the practical use of this technique: first, we generalize differential uniformity into “A-uniformity” and differential trails into “commutative trails”, and second we investigate the commutative behaviour of S-box layers, matrix multiplications, and key additions.
Equipped with these new techniques, we find probability-one distinguishers using only two chosen plaintexts for large classes of weak keys in both a modified Midori and in Scream. For the same weak keys, we deduce high probability truncated differentials that can cover an arbitrary number of rounds, but which do not correspond to any high probability differential trails. Similarly, we show the existence of a trade-off in our variant of Midori whereby the probability of the commutative trail can be decreased in order to increase the weak key density. We also show some statistical patterns in the AES super S-box that have a much higher probability than the best differentials, and which hold for a class of weak keys of density about \\(2^{−4.5}\\).

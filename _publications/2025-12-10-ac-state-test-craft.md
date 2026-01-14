---
title: "The State-Test Technique on Differential Attacks: a 26-Round Attack on Craft and Other Applications"
collection: publications
category: conferences
permalink: /publication/2025-12-10-ac-state-test-craft
excerpt: 
date: 2025-12-10
venue: 'ASIACRYPT'
slidesurl: '/files/slides/2025-12-10-ac-state-test-craft.pdf'
paperurl: 'https://doi.org/10.1007/978-981-95-5018-0_9'
citation: 'M’Foukh, D., Naya-Plasencia, M., Neumann, P. (2026). The State-Test Technique on Differential Attacks: a 26-Round Attack on Craft and Other Applications. In: Hanaoka, G., Yang, BY. (eds) Advances in Cryptology – ASIACRYPT 2025. ASIACRYPT 2025. Lecture Notes in Computer Science, vol 16245. Springer, Singapore. https://doi.org/10.1007/978-981-95-5018-0_9'
coauthors: ' Dounia M’Foukh, María Naya-Plasencia'
eprinturl: 'https://eprint.iacr.org/2025/1597'
---

The state-test technique, originally introduced in the context
of impossible-differential cryptanalysis and recently used as an improvement for truncated-differential Meet-in-the-Middle attacks, has proven to be useful for reducing the complexity of attacks. In essence, the idea is to guess parts of the state instead of the key during the key-guessing stage of an attack, ultimately reducing the number of guesses needed.
We generalize the idea of the state-test technique, allowing it to be applied not only to impossible-differential and  truncated-)differential Meet-in-the-Middle, but also to differential and differential-linear cryptanalysis, proposing also a new performant technique exploiting the state-test technique and probabilistic key-recovery. Additionally, we provide insights on the interaction between cipher and difference needed for the state-test technique to be applicable, finding it to be a promising option for many ciphers.
To illustrate our findings, we provide 3 new applications of the state-test technique: we show how it can be used to improve the best known attack on the block cipher Pride, how it can be used to improve a step in the best known attack on Serpent, and use it to present the first known attacks on 24, 25 and 26 rounds of CRAFT (out of 32), improving by up to three rounds over the previous best ones.

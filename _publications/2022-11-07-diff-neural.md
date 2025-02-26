---
title: "An Assessment of Differential-Neural Distinguishers"
collection: publications
category: manuscripts
permalink: /publication/2022-11-07-diff-neural
excerpt: 
date: 2022-11-07
venue: 'Cryptology ePrint Archive'
slidesurl: 
paperurl: 
citation: 
coauthors: 'Aron Gohr, Gregor Leander'
eprinturl: 'https://eprint.iacr.org/2022/1521'
specialtype: 'Pre-Print'
---

Since the introduction of differential-neural cryptanalysis, as the machine learning assisted differential cryptanalysis proposed in [Goh19] is coined by now, a lot of followup works have been published, showing the applicability for a wide variety of ciphers. In this work, we set out to vet a multitude of differential-neural distinguishers presented so far, and additionally provide general insights.
        
Firstly, we show for a selection of different ciphers how differential-neural distinguishers for those ciphers can be (automatically) optimized, also providing guidance to do so for other ciphers as well. Secondly, we explore a correlation between a differential-neural distinguisher's accuracy and a standard notion of difference between the two underlying distributions. Furthermore, we show that for a whole (practically relevant) class of ciphers, the differential-neural distinguisher can use differential features only. At last, we also rectify a common mistake in current literature, and show that, making use of an idea already presented in the foundational work[Goh19], the claimed improvements from using multiple ciphertext-pairs at once are at most marginal, if not non-existent.

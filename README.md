# Discrete choice theory vs Neural Networks
Comparison of the NN approach with the classic logit-choice model on the traffic assignment task

## Plan
1. Read the [article](https://deliverypdf.ssrn.com/delivery.php?ID=508086097113085103071013092066084113017050018065023030127019099013107042100048034023012094111004073101002005111086034075005125090044118102069071088016069067085081093080094004004117019116029117100024083023105121116070064099121012075065084022121068087089108099013084125098002089125071&EXT=pdf&INDEX=TRUE), that suggests a way to implicitly set agent preferences in the _traffic assignment_ task;
2. Implement the approach described in the article by training a neural network on a dataset [Sioux Falls Network](https://github.com/bstabler/TransportationNetworks/tree/master/SiouxFalls);
3. Compare the proposed approach with the _classic logit-choice model_ for the traffic assignment task;
4. To understand how robust this neural network approach is (for example, whether there will be problems when changing the city for modeling).

## References
1. [Модели равновесного распределения транспортных потоков в больших сетях](https://arxiv.org/vc/arxiv/papers/2003/2003.12160v3.pdf): учебное пособие / А. В. Гасников, Е. В. Гасникова. – Москва : МФТИ, 2020. – 204 с.ISBN 978-5-7417-0737-1
2. Zhichen L. et. al., End-to-End Learning of User Equilibrium with Implicit Neural Networks, Transportation Research Part C: Emerging Technologies, Volume 150, 2023, 104085, ISSN 0968-090X, https://doi.org/10.1016/j.trc.2023.104085

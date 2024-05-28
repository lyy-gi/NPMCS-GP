# NPMCS-GP: Non-overlapping Pattern Matching Cross Sequences Based on Gapped Penalty Strategy
## Abstract
The research extended the non-overlapping pattern matching on multiple sequences with a crossing manner, which not only corresponds to meiosis and independent assortment of genes but also the purchase sequences of customers. Non-overlapping pattern matching involves retrieving data in a manner where no two instances can share the same individual element, meaning they cannot be positioned at the identical location in the pattern. Regarding its merits of time-saving and rich information, prior researchers have raised approaches in mining the support or number of occurrences under non-overlapping conditions. However, contrasting with the state-of-the-art works that retrieved the occurrences on a single sequence, there are still challenging operations across sequences for non-overlapping matching. Inspired by the non-overlapping definition, this study proposed an approach called NPMCS-GP which is based on a second-order Hyper Nettree index structure. This approach adopted a gapped penalty strategy and pruning operation to fix the non-overlapping pattern matching problem across two sequences under the gap and length constraints. NPMCS-GP initially constructed the Hyper Nettree index with two target sequences and the given pattern. Contrasting with non-overlapping matching on a single Nettree to seek the rightmost parent and child node, NPMCS-GP explored the Hyper Nettree. With the gapped penalty strategy, it realized matching cross sequences until an occurrence was obtained, which strictly satisfied the non-overlapping constraint. Finally, the completeness and complexity of NPMCS-GP were analyzed. Extensive experiments have been conducted to prove the correctness and efficiency of the proposed algorithm.

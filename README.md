# Feature-Interaction Aware Configuration Prioritization
In a configurable software system, unexpected interactions among 
features might induce bugs. The exhaustive analysis approach is 
prohibitively costly because of the exponential number of all 
possible configurations. The sampling techniques to select a subset 
of configurations for testing are still limited because they do not 
examine the source code and do not provide an assessment of 
potential buggy configurations. In this paper, we propose CoPo, a 
novel formulation of feature-interaction bugs via common program 
entities enabled/disabled by the features. Leveraging that 
knowledge, we develop efficient feature-interaction-aware configuration 
prioritization technique for a configurable system by ranking the 
configurations according to their total number of potential bugs. We 
conducted several experiments to evaluate CoPo in two complementary 
settings: detecting configuration-related bugs in a benchmark 
and real-world open-source systems. We found that CoPo outperforms 
the other techniques. In 85% of the cases, it ranks the buggy 
configurations at the top 3 positions. Interestingly, it is able to 
detect 17 not-yet-discovered, high-degree, feature-interaction bugs.

# CUD-Research

In recent years, attitudes toward marijuana are changing and marijuana use is increasingly viewed as harmless. However, along the side of the increasing marijuana use there has been an rise in prevalence of DSM-5 *cannabis use disorder* (or CUD).  This disorder is associated with adverse consequences such as cognitive decline, impaired educational or occupational attainment, impaired driving ability, emergency room visits, psychiatric symptoms and risk of addiction or substance use disorders. To learn more [1](https://pubmed.ncbi.nlm.nih.gov/26551358/)[2](https://www.sciencedirect.com/science/article/pii/S0376871613000264).

In this work, we examine possible mediators for developing CUD using (Wave 1) of the National Epidemiological Survey of Alcohol and Related Conditions (NESARC-III) dataset. 
We take a partial correlation approach for analysis of different trios which may exhibit a causal relationship. These trios are modeled as partial graphs, in which information can flow in different paths: $A->B->C, A->C, A->B, A->C->B$, where $A$ is an "anchor node" - and event that clearly preceeds $B$ and $c$. 


In the given dataset, $A$ can be an demographic feature (age or sex) or an early adverse event (EAE). Each time correlation is conditioned on a different node, blocking the respective information path, aming to revel the true stracture of the trio. 

This code allows to examine mutiple trios and outputs a table which quatifies correlation reduction.

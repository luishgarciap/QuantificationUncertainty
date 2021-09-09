# Quantification of uncertainty to support NFRs trade-offs for self-adaptation: a Partially Observable Markov Decision Process approach 

## Abstract  

Self-adaptive and autonomous systems (SASs) are expected to self-adapt based on incomplete information and unanticipated events. As such, the decision-making of a SAS is challenged by the underlying uncertainty. We focus on the uncertainty associated with the satisfaction of the quality goals, i.e. the non-functional requirements (NFRs) in a SAS, due to adaptation actions. Approaches that support the decision making of a SAS, often consider an idealized reality where (i) the system’s state is treated as fully observable by the monitoring infrastructure, and (ii) adaptation actions are assumed to have known, deterministic effects over the system. However, the system’s state may not be fully observable in practice, and adaptation actions may produce different unexpected effects due to uncertain factors. Further, adaptation actions may have different levels of desirabilities by the stakeholders over time. 

In this paper, we extend the standard specification of Partially Observable Markov Decision Processes (POMDPs) to develop a novel probabilistic approach to quantify over time the uncertainty associated with the effects on the system’s state of executing adaptation actions. Supported by the use of Bayesian inference, these probabilistic effects can be translated into satisfaction levels of the NFRs of a SAS, to therefore support decision making. Results show that our approach to quantify uncertainty is soundness and statistically significant. An online POMDP solver tool is used to identify the optimal policy measured against the quality goals of a SAS. A substantial case study and its analysis and validation through simulation have been presented to demonstrate our proposal’s utility.


Paper submitted to http://www.jot.fm/

[1] Luis Garcia-Paucar, Nelly Bencomo. Quantification of uncertainty to support NFRs trade-offs for self-adaptation: a Partially Observable Markov Decision Process approach 

## Acknowledgements 

This work has been partially funded by the Leverhulme Trust Research Fellowship (Grant No. RF-2019-548/9) and the EPSRC
Research Project Twenty20Insight (Grant No. EP/T017627/1).




 ## Log files
The log files used to generate the results depicted in [1] have been organized in three categories:

* Remote Data Mirroring (RDM) Self Adaptive System (SAS) under different Dynamic Contexts (folders DynamicContext_DC1 to DynamicContext_DC2)
* RDM SAS under other Service Level Agreements (SLAs) (folder OtherSLAs)
* RDM SAS under stable conditions (folder _StableConditions)

## Logs for the RDM SAS under different dynamic contexts

Figures 7 and 8 correspond to the log files:
<ul>
<li>/DynamicContext_DC1/_logi_c1_s10_YesDNoJ.json </li>
<li>/DynamicContext_DC1/_logi_c1_s10_YesDYesJ.json</li>
</ul>


Figures 9 and 10, correspond to the log files:
<ul>
<li>/DynamicContext_DC3/_logi_c3_s10_YesDNoJ.json</li>
<li>/DynamicContext_DC3/_logi_c3_s10_YesDYesJ.json</li>
</ul>


Figures 11 and 13, correspond to the log files:
<ul>
<li>/DynamicContext_DC2/_logi_c2_s10_YesDNoJ.json</li>
<li>/DynamicContext_DC2/_logi_c2_s10_YesDYesJ.json</li>
</ul>


Figures 12 and 14, correspond to the log files:
<ul>
<li>/DynamicContext_DC4/_logi_c4_s10_YesDNoJ.json</li>
<li>/DynamicContext_DC4/_logi_c4_s10_YesDYesJ.json</li>
</ul>

Figures 15 and 16, correspond to the log files:
<ul>
<li>/DynamicContext_DC5/_logi_c5_s10_YesDNoJ.json</li>
<li>/DynamicContext_DC5/_logi_c5_s10_YesDYesJ.json</li>
</ul>


Figures 17 and 18, correspond to the log files:
<ul>
<li>/DynamicContext_DC6/_logi_c6_s10_YesDNoJ.json </li>
<li>/DynamicContext_DC6/_logi_c6_s10_YesDYesJ.json</li>
</ul>


## Logs for the RDM SAS under other SLAs

Figures 22, 23 and 24 correspond to the log files:
<ul>
<li>/OtherSLAs/logi_s100_(0.7_0.80_0.60).json </li>
<li>/OtherSLAs/logi_s100_(0.8_0.95_0.85).json</li>
<li>/OtherSLAs/logi_s100_(0.8_0.99_0.85).json</li> 
</ul>
 

## Log for the RDM SAS under stable conditions

Figures 5 and 6 correspond to the log file:
<ul>
<li>/_StableConditions/_logi_sc_s10_NoDNoJ.json </li>
</ul>



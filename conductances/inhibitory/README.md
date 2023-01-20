# SPN - SPN

dSPN-dSPN is exactly like Planert et al 2010, but 20% (approximately) too small for Taverna et al 2008 (although they do not report LJP, that would just account for some of the differences).



# FS - SPN

### Gittis et al 2010

FS - SPN connection 7.8nS +- 11.2nS in the model this has become a conductance of (1.1-1.5 nS per FS synapse) as we assume the average
number of synapses representing this connection is 7.8/1.3 = 6 synapses (1.3 is the mean of 1.1-1.5). If this is not true anymore, the conductance has 
to be changed.

A pair of FS - SPN should on average have around 550 pA (but a large standard deviation of 700-800 pA)

In Gittis et al 2010, in Figure 7, the report a preference for FS to dSPN with on average 77 pA more than FS->iSPN (not currently implemented). This would result in FS-dSPN - about a 10% increase in single synapse conductance i.e from [1.1-1.5] to [1.2-1.65]

Important when analysing the effect of FS, to look at highly connected populations - the core of the network.

## FS have a non-uniform distribution of FS-SPN pairs currents - we capture the average, not the extremly large currents.



There is a possibility to increase FS - MSN by 20%

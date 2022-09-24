# Terp-Net Scavenger Hunt

Welcome! Thank you for joining us on our journey to create the hyperfocused ecosystem for all things terpene! This 2-week event serves 4 purposes:

- 1. Introduce TERPNET & the nessary de-fi tooling to interact with Terp-Core.
- 2. Provide an incentive to accompish various tasks that benefit Terp-Core users.
- 3. Provide an opportunity to recieve feedback on tooling deployed by participants.
- 4. Grant participants eligibility to TERPNET's stakedrop allocations.


## When? 

### Phase-1:
- Start: Sept 27th, 2022
- End: Oct 4th, 2022  
### Phase-2:
- Start: Oct 7th, 2022
- End: Oct 14th, 2022


## What will it look like?

Well, the plan is to break it into two, week-long phases:

- Week 1: Function Test
- Week 2: Stress Test    

### Week 1: Function Test.

Week 1 will be development & deployment oriented. The goal is to deploy tooling & expand the test network infrasturctre, which will give new community members a place to test deploying on Terp Network, or even just a better understanding of how this platform can be utilized. 

These specific dapps are planned to use for creating an opportunity to become eligible for the upcoming airdrop. 

- DAO-DAO UI 
- Block Explorer 
- Staking Interface 
- On Chain Swap

In order to build up the community governance, in a way that is fair & utilizes the technology at hand, this procedure was drafted:


    1. IBC Relayer's connected from Chronic Network Main net [Morocco-1] to Terp Network Test-Network [Athena-1].
    2. A DAO gets instantiated on the new Test Network. 
    3. CGAS holders transfer tokens from Chronic Network, to Terp Test network.
    4.Participants will be able to stake CGAS in order to become a member of the DAO. Yes, CGAS!!

    By staking CGAS (which is vested for 1 year), this will be another way for participants to become exposed to the airdrop.

    *note: distribution calculations will be made after the test network scavenver hunt sprints have ended.*



## Development Hunt Week 1:

list of items for development hunt:

- Code contributions:
    - Useful Documentation  
    - Workflow Automation (TBD)
    - Suggestions & improvements to available stack
- Infrastructure Deployments:
    - Nodes, Validators , Relayers
    - RPC's, REST, LCD's 
    - Snapshot provider 
    - Any contribution improving the projects resources



### Week 2: Stress Test.

This week will be used to prove the strength of the tools we plan to use to build with. We are looking to collaborate with professionals for this process, but essentially an array of attacks will be attempted on the network & tooling used. 

In parrallel with this, coordinated attacks via community members is also how participants are eligible to the airdrop allocation. 

This still needs some work, but something like trying to mint a bunch of NFTs , or everyone trying to swap into the same token could be some ways that we can have confidence in the funciton of these tools


## Gaguing Contributions & Airdrop Distributions

Contributions & Participation of this event will be tracked on a point based system. Upon the end of phase 2, the total results will be compared, & the proportion of contribution points that were earned will be used to calculate the proportion of fairdrop tokens allocated. 

All decisions are to be finalized via consnensus of Test-Net DAO members. 

## Ratios

Test Net Contributors & Participants: [13%]
- Infrastructures [5%]
    - node,validator: +1 point
    - relayer provider: +1 point 
    - dapp contribution: +1 point 
- Terp-Core Contributors: [3%]
    - documentation resources: +1 point
    - suggestions & improvements: +1 point
- CGAS Depositors [5%] 
    - We use piecewise linear curves for all items, constant above a minimum and a maximum. 

Given user X is percentile /rho in some metric (ie. CGAS deposit amount), we define the reward formula as : 

``` 
Reward(R)= func(p, a, b, min, max)

    =a ; if p < min
    =b ; if p > max 
    =a + ((b-a) * (p-min)/(max-min)) ; otherwise 
``` 

keep an eye our for a csv tracking contributions, it will mosgt likely end up [here](/contribution-tracking.csv)




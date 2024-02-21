# ZenIP Template

*If this is your first time writing a ZenIP, the structure and format may look intimidating. But really, it's just meant to reflect common-sense practice and some technical conventions. This template is meant to be a starting point for you to structure your ideas. It might help to sort the different aspects of your proposal into the structure below in order get your idea across efficiently. The community and ZenIP editors will help you figure things out and get your proposal into a proper shape later.*

## Header Preamble

    ZenIP: Unassigned (numbers are assigned by ZenIP editors)
    Title: *Something Short and To the Point*
    Owners: nikvladan(Alias Trololino) lordhakkira@yahoo.com
    ...
    Status: Draft
    Category: (Consensus | Standards Track |Informational | Process)
    Created: 2020-10-04
    License: MIT (see the licensing section of ZenIP-42000)

## Table of Contents

-Terminology 
-Abstract 
-Motivation 
-Requirements 
-Specification
-References

## Terminology

The key words "MUST", "MUST NOT", "SHOULD", and "MAY" in this document are to
be interpreted as described in [RFC 2119](#references).

The terms below are to be interpreted as follows:

- Term to be defined
  - definition
- Another term
  - another definition

## Abstract


This proposal suggests a change in daily distribution of Horizen rewards and changing requirements for hosting secure nodes and supernodes. Specifies a time when this change should activate.


## Motivation


After Horizen halving which will happen in approximately 58 days from today, rewards for holders that host secure nodes and supernodes will reduce in half. Due to price of Zen dropping so low as to bellow 5.3$ as it is at this moment of writting this project, hosting secure nodes as well as supernodes will become unprofitable. 
Secure nodes and super node owners pay for hosting each month (as well as domain name each year for supernodes). Increased rewards have to come from somewhere, and in this proposal its suggested they are taken from miners. Ever since Q1 2018 when ASIC miners first appeared on Equihash network, they have been decreasing the price of Zen without any sign of stopping. This will also decrease their selling pressure on the markets, as well as halving event. As for security, measures are implemented to aid against 51% attack already. Additional measures can be taken, but this is not the point i want to discuss in this proposal. 
Horizen fauced which has been mentioned a lot of times in weekly/quarterly reports and streams is irrelevant atm and rewards are not even worth opening the page. Making some of the rewards go directly to Horizen faucet will get a lot of people involved in ZEN, who don't have any means of buying ASIC miners, and will increase the community involvement.

## Requirements

For this proposal, I assume hard fork is needed to redistribute the rewards. Hard fork would happen right after the halving (71 days from now). 
Requirements for hosting secure nodes will rise accordingly:
1) 84 ZEN for secure nodes,
2) and 1000 ZEN for SuperNodes.


## Specification

After Halving event, daily inflation on Horizen network will drop to 3600 ZEN. I propose the rewards be distributed in following manner:
1) 20% (720 ZEN) to the team for development purposes 
2) 20% (720 ZEN) to secure nodes (same as it is now before halving) 
3) 20% (720 ZEN) to super nodes (same as it is now before halving) 
4) 35% (1250 ZEN) to miners for securing the network, 
5) 5% (180 ZEN) directly to zen faucet to get new community members.

## References

[1] ZenIP-42000 - https://github.com/HorizenOfficial/zenips/blob/master/zenip-42000.md/#zenip-licensing

[2] RFC2119 - Key words for use in RFCs to Indicate Requirement Levels https://tools.ietf.org/html/rfc2119

[3] https://github.com/HorizenOfficial/ZenIPs/blob/master/zenip_template.md

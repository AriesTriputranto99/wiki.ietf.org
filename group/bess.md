---
title: BESS WG - BGP Enabled ServiceS
description: This wiki is for the BESS WG.
published: true
date: 2025-06-25T00:13:29.015Z
tags: 
editor: markdown
dateCreated: 2022-11-05T16:17:26.188Z
---

# BESS WG detailed Status


## Critical items (<span style="color:red">RED FLAG</span>)
* Consistency checks required between editors of BESS YANG models to ensure a similar way of configuring and operations VPN models.
* If new Path Attributes are specified, IDR review is mandatory.

## Items to note

* YANG models: there are some dependencies with other models (BGP...).

## WG adoption checklist

* Idnits checking
* Grammar checking (e.g., Grammarly)
* 5-author guideline (need justification for more than 5 front-page authors, e.g., specific ideas and/or significant text contribution)
* IPR declaration
* Cross-review or joint-call by relevant WGs (e.g., IDR)

## WG LC checklist

* Idnits verbose checking
* Grammar checking (e.g., Grammarly)
* 5-author guideline
* IPR declaration
* Implementation status
* GenArt and RtgDir early review
* Cross-review or joint-call by relevant WGs (e.g., IDR)

## On going polls
| Document Name | Poll type | Chair in Charge | Start date | End date | Comment | 
| --- | --- | --- | --- | --- | --- |
| 
{.dense}



## Action items
This section lists actions other than document updates

| Action | Owner | Start date | Expected date | Done|
| --- | --- | --- | --- | --- | 



## Early allocations

| Document Name | Request date (by authors) | Status | AD approval date | IANA first allocation date | Renewal date | Expiration date |
| --- | --- | --- | --- | --- | --- | --- |


|draft-ietf-bess-evpn-ipvpn-interworking] |07/03/19|Allocated|07/05/19||05/26/20|07/08/21|
{.dense}


## Latest RFCs

* RFC 9746 BGP EVPN Multihoming Extensions for Split-Horizon Filtering
* RFC 9744 EVPN Virtual Private Wire Service (VPWS) Flexible Cross-Connect (FXC) Service
* RFC 9721 Extended Mobility Procedures for Ethernet VPN Integrated Routing and Bridging (EVPN-IRB)
* RFC 9722 Fast Recovery for EVPN Designated Forwarder Election


## Documents in RFC editor queue

* draft-ietf-bess-evpn-pref-df-13
* draft-ietf-bess-evpn-virtual-eth-segment-19 
* draft-ietf-bess-evpn-mh-pa-13 
* draft-ietf-bess-bgp-srv6-args-10
* draft-ietf-bess-evpn-redundant-mcast-source-15

## Documents sent to IESG
Shepherd's name indicated within parenthesis.
* draft-ietf-bess-vpls-multihoming (Matthew):
* draft-ietf-bess-bgp-sdwan-usage (Matthew)
	- Telechat on 2/29
  - park it for now (09/06)
* draft-ietf-bess-evpn-ipvpn-interworking-14


## Documents under Shepherds Review

- draft-ietf-bess-evpn-bfd-10 (Matthew):
- draft-ietf-bess-evpn-mvpn-seamless-interop-08 (Matthew): 
- draft-ietf-bess-ebgp-dmz-06 (Matthew): 
- draft-ietf-bess-evpn-unequal-lb (Stephane):
  - the document has a lot of normative dependencies that are not ready yet
  - An outstanding comment from Jeffrey about inconsistent/inappropriate use of "ECMP"
  - Review requested to IDR chairs
  - RTGDIR and GENART review requested => comments addressed
- draft-ietf-bess-mvpn-evpn-sr-p2mp-12 (Stephane):
- draft-ietf-bess-rfc7432bis-12 (Jeffery):
- draft-ietf-bess-evpn-dpath-02 (Jeffery):
- draft-ietf-bess-evpn-geneve: (Matthew)
  - Moved to experimental now , Matthew to write up and move to next step (09/06)


## Documents that failed Working Group Last Call 

- draft-ietf-bess-evpn-l2gw-proto:
	- no objection during WGLC but too few replies from WG
  - Implementations exist
  - Luc Andre addressed RTGDIR comments
  - Hold on until we can assess that there is more support

- draft-ietf-bess-evpn-ipvpn-interworking:
  - Jeff Haas needs to do another top-to-bottom review of the draft


## Documents candidates for Working Group Last Call


* draft-ietf-bess-evpn-ac-aware-bundling (Jeffrey)
  - Outstanding questions/comments from Jeffrey
  - Action : Mankamana / Jeffery meeting during IETF 121 to discuss comments. 
  - Expired, working on It. 
  
* draft-ietf-bess-evpn-per-mcast-flow-df-election
	- RTGDIR review comments provided. Discussion is not closed yet.Draft update in progress.
  - Mankamana meeting Acee during IETF 121 to discuss the comments provided 
  - Plan to have presented in IETF 123
  
* draft-ietf-bess-extended-evpn-optimized-ir-06 
	- RTGDIR and GENART review passed
  
* draft-ietf-bess-rfc7432bis
	- RTGDIR review comments received but no reply from authors. Some offline comments to address as well.
  - Draft being updated as of 11/2 
  - Mankamana to check with Ali about if its ready. 
  - Matthew to review the draft 
  

* draft-ietf-bess-bgp-multicast-controller
  - GenArt early review passed
  - Revision -12 posted on 12/30/23 to address RtgDir early review comments. No acknowledgement from reviewer yet.
  - Requested Susan for IDR review for both bgp-multicast drafts.
  - Susan comment has been addressed, waiting for her comment. 

* draft-ietf-bess-bgp-multicast
  - GenArt and RtgDir early review passed ( revision -07)
  - Susan comment has been addressed, waiting for her comment. 

* draft-ietf-bess-evpn-mvpn-seamless-interop
  - Ready for WGLC 

* draft-ietf-bess-evpn-bfd
  - Needs joint WG LC with BFD WG (will CC rtg-bfd@ietf.org) (Matthew)
  - early review to be started 
 * draft-ietf-bess-mvpn-evpn-sr-p2mp-09 
   - Early review requested 
* draft-ietf-bess-evpn-vpws-seamless-01

  
## Recently adopted documents
* draft-ietf-bess-evpn-fast-reroute-00
* draft-ietf-bess-evpn-vpws-gateway-00


 
## Documents requested for Working Group adoption (Non Expired drafts only)


* draft-wang-bess-mvpn-upstream-df-selection  
 - Expired 

* draft-mackenzie-bess-evpn-l3mh-proto (Jeffrey)
  - update may be needed - depending on ac-aware-bundling discussions
* draft-mpmz-bess-mup-safi:
  - implementation/prototype exists, authors would like to move forward
  - Need to reduce to 5 authors
  - Depends on architecture draft being adopted in dmm (draft-mhkk-dmm-mup-architecture-00)

* draft-sajassi-bess-rfc8317bis-02
* draft-sajassi-bess-evpn-umr-mobility-02
* draft-sajassi-bess-evpn-first-hop-security-03
## Documents that failed WG adoption
* draft-wang-bess-sbfd-discriminator
* draft-thubert-bess-secure-evpn-mac-signaling (3/13/24)

## Working group document status (Non Expired only)

(Removed as this is tracked in datatracker)






{.dense}



## IDR/BESS cross WG reviews 
https://trac.ietf.org/trac/idr/wiki/Feedback%20for%20BESS%20drafts


&nbsp;
&nbsp;
&nbsp;

---

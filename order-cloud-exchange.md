---

copyright:
  years: 2017, 2018, 2019
lastupdated: "2019-02-26"

keywords: order, provider, capabilities, Exchange, cross-connect, locations, PoP, datacenter, data, center, pricing

subcollection: direct-link

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# How to order IBM Cloud Direct Link Exchange
{: # how-to-order-ibm-cloud-direct-link-exchange}

1. Verify your network provider's capabilities to reach the appropriate PoP and cross-connect into the associated Exchange provider.
2. Use the [Customer Portal ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://control.softlayer.com/) to open an {{site.data.keyword.cloud}} Direct Link Exchange request and complete the requested information. (Assistance from IBM sales engineers can be requested.) If you use the Equinix provider, you can use [automated ordering](/docs/infrastructure/direct-link?topic=direct-link-provisioning-ibm-cloud-direct-link-exchange-for-equinix).
3. Contact your Exchange provider and negotiate connectivity to your exchange.
4. Order connectivity between your network provider and the Exchange provider.
5. Order a "virtual circuit" through the Exchange provider, and refer the Ticket ID of the {{site.data.keyword.BluSoftlayer_notm}} Direct Link request as your "Request ID" or "Authorization ID"
6. IP assignment on the {{site.data.keyword.BluSoftlayer_notm}} networking infrastructure will be completed within 3 business days after the virtual circuit request is complete.
 
## Locations
 
 The table shows which IBM Cloud datacenters offer Direct Link Exchange connectivity:
 
| Exchange Provider	| IBM Data Center Code |
|-------------|-----------------------|
| AT Tokyo | TOK02 |
| Ascenty | SAO01* |
| Cologix | MON02, TOR02 |
| Cyrus One | DAL13 |
| DE-CIX | FRA01 |
| Equinix | HKG01,SNG02, SYD02, TOK01, AMS02, PAR02, CHI01, DAL03, NYC02, NYC03, SAO02, SJC02, TOR02, WDC02, LON01, FRA03 |							
| InterXion | FRA01, STO01 |
| KINX	| SEO02 |
| NextDC | MEL02, SYD03* |
| SK C&C | SEO01 |

* Coming Soon

## Pricing

For pricing information, please refer to the [pricing document](/docs/infrastructure/direct-link/pricing.html).

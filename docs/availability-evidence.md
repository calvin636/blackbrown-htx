# Availability evidence and maintenance

This is a bounded snapshot, not a live inventory feed. Main baseline: 33afde4748833d4de0c543f67257c33e958bf05d.

Verified October 12, 2026 by direct inspection of the linked eBay offers: 23 active/purchasable offers and one ended offer. Five Search Console examples are included. The other 131 product pages have no new availability claim (three requests returned access 403; verification stopped without bypassing access controls).

## Freshness policy

Recheck each changed exact offer and every advertised variant immediately before merging or publishing if the evidence is more than 24 hours old. Do not publish stale assertions. After publication, review at least weekly and whenever a listing ends, sells out, or changes variants. Update the JSON-LD and visible dated wording together. If current stock cannot be verified, remove offers.availability and the corresponding visible availability paragraph; retain the general marketplace-check notice. Missing optional availability is preferable to an invented or stale claim. This policy requires an owner before publication; no automatic refresh or expiry exists in this static repository.

Do not infer availability from a quantity label alone. Require active/purchasable status and source evidence for the exact offer and variants. Ended linked offers map to OutOfStock, not Discontinued. No stock statement here applies to the separate Walmart purchase link.

## Validation

All 24 changed pages were parsed and checked against exact offer URLs. Only offers.availability and one dated visible paragraph were added. Reversing those insertions reconstructs the original page byte-for-byte, preserving branding, prices, descriptions, images, product brands, canonical URLs, purchase links and prior fixes. The remaining 166 existing repository files are inherited unchanged from the base tree. This is source validation, not a Google Rich Results Test or Search Console recrawl confirmation.

Google references: [Product snippets](https://developers.google.com/search/docs/appearance/structured-data/product-snippet), [Schema.org ItemAvailability](https://schema.org/ItemAvailability).

## Verified mapping

```json
[
  {
    "sku": "PLENA-178448388642",
    "source": "https://www.ebay.com/itm/178448388642",
    "retrievedAt": "2026-10-12T22:51:03Z",
    "availability": "https://schema.org/OutOfStock",
    "variantsVerified": false,
    "reason": "Visible seller-ended notice; ENDED status; no purchase controls; source schema OutOfStock."
  },
  {
    "sku": "PLENA-178450196881",
    "source": "https://www.ebay.com/itm/178450196881",
    "retrievedAt": "2026-10-12T22:51:03Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450221270",
    "source": "https://www.ebay.com/itm/178450221270",
    "retrievedAt": "2026-10-12T22:51:03Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": false,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450277610",
    "source": "https://www.ebay.com/itm/178450277610",
    "retrievedAt": "2026-10-12T22:51:09Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450291237",
    "source": "https://www.ebay.com/itm/178450291237",
    "retrievedAt": "2026-10-12T22:51:09Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450361024",
    "source": "https://www.ebay.com/itm/178450361024",
    "retrievedAt": "2026-10-12T22:51:10Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": false,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450403356",
    "source": "https://www.ebay.com/itm/178450403356",
    "retrievedAt": "2026-10-12T22:51:18Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450445596",
    "source": "https://www.ebay.com/itm/178450445596",
    "retrievedAt": "2026-10-12T22:51:18Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178450781918",
    "source": "https://www.ebay.com/itm/178450781918",
    "retrievedAt": "2026-10-12T22:51:18Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": false,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178451083688",
    "source": "https://www.ebay.com/itm/178451083688",
    "retrievedAt": "2026-10-12T22:51:24Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178451101418",
    "source": "https://www.ebay.com/itm/178451101418",
    "retrievedAt": "2026-10-12T22:51:25Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178506515762",
    "source": "https://www.ebay.com/itm/178506515762",
    "retrievedAt": "2026-10-12T22:51:24Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178506807554",
    "source": "https://www.ebay.com/itm/178506807554",
    "retrievedAt": "2026-10-12T22:51:31Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178506836701",
    "source": "https://www.ebay.com/itm/178506836701",
    "retrievedAt": "2026-10-12T22:51:31Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508184577",
    "source": "https://www.ebay.com/itm/178508184577",
    "retrievedAt": "2026-10-12T22:51:31Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": false,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508188866",
    "source": "https://www.ebay.com/itm/178508188866",
    "retrievedAt": "2026-10-12T22:51:37Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508190924",
    "source": "https://www.ebay.com/itm/178508190924",
    "retrievedAt": "2026-10-12T22:51:37Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508205390",
    "source": "https://www.ebay.com/itm/178508205390",
    "retrievedAt": "2026-10-12T22:51:37Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508229540",
    "source": "https://www.ebay.com/itm/178508229540",
    "retrievedAt": "2026-10-12T22:51:43Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508259479",
    "source": "https://www.ebay.com/itm/178508259479",
    "retrievedAt": "2026-10-12T22:51:43Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": false,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508300121",
    "source": "https://www.ebay.com/itm/178508300121",
    "retrievedAt": "2026-10-12T22:51:43Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508309772",
    "source": "https://www.ebay.com/itm/178508309772",
    "retrievedAt": "2026-10-12T22:51:49Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508344205",
    "source": "https://www.ebay.com/itm/178508344205",
    "retrievedAt": "2026-10-12T22:51:50Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  },
  {
    "sku": "PLENA-178508371247",
    "source": "https://www.ebay.com/itm/178508371247",
    "retrievedAt": "2026-10-12T22:51:49Z",
    "availability": "https://schema.org/InStock",
    "variantsVerified": true,
    "reason": "ACTIVE status; visible purchase controls; source schema InStock; all offered variants verified where present."
  }
]
```

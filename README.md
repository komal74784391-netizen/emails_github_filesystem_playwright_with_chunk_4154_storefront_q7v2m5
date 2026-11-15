# Storefront Artifact Snapshots

Each folder under `storefront/<record_id>/` belongs to one partner offer.

- `metadata.json` carries the publication state for the offer.
- `page.html` is the product-page snapshot that customers would see.

Only offers whose `metadata.json` has `"state": "published"` are live and may be
referenced from the partner catalog. Draft folders are placeholders for offers
that have not been released.

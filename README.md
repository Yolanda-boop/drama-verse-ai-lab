# Drama Verse AI Lab

Private workspace for Drama Verse demos and internal prototypes.

## Demo

- `Demo/ai-subtitle-qc-2/`: AI subtitle QC 2.0 editor interaction prototype.
- `Demo/external-admin-role-online-increment/`: External admin role and export workflow incremental prototype.

## Secure sharing recommendation

Deploy this private repository with Cloudflare Pages, then protect the Pages domain or path with Cloudflare Access.

Suggested Access policy:

- Allow: specific R&D emails or company email domain / SSO group
- Block: everyone else

The demo page includes `noindex,nofollow`, and `_headers` adds the same search-indexing protection at response level. These are not access control; do not rely on them instead of Cloudflare Access.

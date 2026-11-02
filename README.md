# BF Linkbase

A searchable link directory and infrastructure registry for Blueberry Fruitsy.

Live site: https://links.bbryftsy.site

The initial registry was seeded from the canonical Blueberry Fruitsy source file, the MusicBrainz links file, and the connected Cloudflare account's Worker/domain inventory on 2026-11-02.

The site provides searchable categories and a read-only JSON endpoint at `/api/links`.

This is a curated snapshot, not a live browser-history collector. A future authenticated sync can refresh Worker domains and Pages projects. Never put Cloudflare API tokens in this repository or browser code.

Deploy with Wrangler: `npx wrangler deploy`.

# Brand and profile maintenance

## Source evidence

Product descriptions and logo geometry were checked against `Struktahub/struktahub-webpage` main on 6 October 2026:

- `src/content.ts`: One documents and drawings; Flow orchestration across industries; Log construction work records and time.
- `src/Brand.tsx`: approved building emblem, navy #0f172a and blue #4141fd.
- `AGENTS.md` and `docs/brand-sources.md`: all products use the same building emblem; only the suffix changes.

This repository contains public marketing copy and selected logo geometry only. It does not contain application source, internal plans or customer data. No legal company name, address, public email, domain or production availability was assumed.

## Profile settings

- Display name: Strukta
- Bio: Give work structure. StruktaOne for documents and drawings, StruktaFlow for workflow orchestration, and StruktaLog for work records and time.
- Website, location and email: blank until a real public value is supplied.
- Avatar: `profile/assets/strukta-avatar.png`.

## Publishing

GitHub shows `profile/README.md` from the default branch of the public `.github` repository. Merge the profile PR to publish the overview. Asset URLs intentionally target main so they continue working after the branch is removed.

The avatar must be uploaded through organisation Settings → Profile. Keep release claims current and update the profile when access is announced.

## Asset exports

SVGs preserve the source building geometry. PNGs are raster exports of the SVGs using Sharp; the avatar uses a pale background for contrast.


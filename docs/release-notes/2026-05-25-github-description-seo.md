# Release notes: 2026-05-25 — github-description-seo

**Status:** Ready for review  
**Repo:** li-langverse/li-std-core  
**Author:** agent (WP-A4)

## Summary (one sentence)

Replace template GitHub description with core stdlib blurb for HPC, scientific computing, and AI.

## Agent continuation (required)

1. Read: `.github/repo-description`.
2. Run: `gh repo view li-langverse/li-std-core --json description`.
3. Then: stdlib API expansion on `main`.
4. Blocked on: WP-H2 — **none**.

## Changed (specific)

- `.github/repo-description`, `README.md`, `CHANGELOG.md`.

## Not changed (scope fence)

- `src/`, `lic` std proofs, `li-std-math` — **not** touched.
- LICENSE policy — WP-H2.
- Coverage gates — unchanged.

## Breaking changes

None.

## Security

N/A.

## Performance

N/A.

## Downstream

N/A.

# Reviewer Entry Points

This file gives the shortest serious route into the additional-problems tranche of the canonical-lane library.

## Fast Review Order

1. Read the main [README](README.md) to see the grouped problem families and the live repo list.
2. Read [PUBLIC_OVERVIEW.md](PUBLIC_OVERVIEW.md) if you need the tranche-level purpose before opening individual repos.
3. Use one super-repo and one standard-lane repo as the minimum audit pair:
   - super-repo: [local-langlands-canonical-lane](https://github.com/HautevilleHouse/local-langlands-canonical-lane)
   - standard-lane: [yau-tian-donaldson-canonical-lane](https://github.com/HautevilleHouse/yau-tian-donaldson-canonical-lane)
4. Then compare against the parent method in [manifold-constrained-core](https://github.com/HautevilleHouse/manifold-constrained-core).

## What To Look For

- the same parent method is present,
- the later tranche stays within the canonical review surface,
- the growth layer is indexed separately from the earlier main library,
- super-repos are used where the subject is genuinely umbrella-level,
- standard lanes remain compact where the endpoint is sharp.

## Suggested Audit Pairings

- birational growth: `abundance-conjecture-canonical-lane` + `minimal-model-program-canonical-lane`
- anabelian growth: `section-conjecture-canonical-lane` + `anabelian-hyperbolicity-canonical-lane`
- arithmetic-geometry growth: `bombieri-lang-conjecture-canonical-lane` + `zilber-pink-conjecture-canonical-lane`
- local/global representation growth: `artin-holomorphy-conjecture-canonical-lane` + `local-langlands-canonical-lane`
- p-adic representation growth: `local-langlands-canonical-lane` + `p-adic-langlands-canonical-lane`
- differential-geometry growth: `chern-conjecture-canonical-lane` + `yau-tian-donaldson-canonical-lane`

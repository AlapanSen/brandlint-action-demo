# BrandLint Action demo

A throwaway repository that shows the BrandLint GitHub Action on a real runner.

It checks the copy in `docs/` on every pull request against the rules of a BrandLint workspace.
The action comes from https://github.com/AnoushkaSundar/brandlint (`integrations/github-action`),
pinned by commit. A pull request that breaks a rule fails the **BrandLint** check, annotates the
line, and links to the finding.

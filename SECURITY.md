# Security policy

This policy applies to every repository of the LedgerDirect organisation that does not have one of
its own.

## Reporting a vulnerability

Please do not report a security problem in a public issue, pull request or discussion. Report it
privately, in one of two ways:

- **GitHub:** open the Security tab of the affected repository and choose "Report a vulnerability".
- **E-mail:** write to [info@ledger-direct.com](mailto:info@ledger-direct.com).

Please include the repository and version, what an attacker can do, and the steps to reproduce it.

## What to expect

We confirm receipt within 5 business days and keep you informed while we investigate and fix the
problem. Please give us the time to publish a fix before you disclose it. There is no bug bounty.

## Supported versions

Security fixes go into the latest release of the payment core (`hardcastle/ledger-direct-core`), of
each shop plugin (Shopware, Magento, WooCommerce, PrestaShop) and of the Laravel package. Please
check that the problem still occurs with the latest release.

## Scope

In scope: the payment core, the shop plugins, the Laravel package, the payment page
(`ledger-direct-payment-ui`) and the end-to-end test harness (`ledger-direct-e2e`).

Out of scope: third-party wallets, the ledgers themselves (the XRP Ledger, Xahau and others), and
their public test networks and faucets. A vulnerability in a third-party dependency belongs to its
maintainers; tell us as well if LedgerDirect is affected by it.

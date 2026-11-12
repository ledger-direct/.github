# Security policy

Security matters to us: LedgerDirect moves real payments. No matter how careful we are,
vulnerabilities can still slip through, and we are grateful for every report that helps us find
them. This policy applies to every repository of the LedgerDirect organisation that does not have
one of its own.

## Supported versions

Security fixes go into the latest release of the payment core (`hardcastle/ledger-direct-core`),
of each shop plugin (Shopware, Magento, WooCommerce, PrestaShop) and of the Laravel package.
Please check that the problem still occurs with the latest release.

## Reporting a vulnerability

Please do not report a security problem in a public issue, pull request or discussion. Report it
privately, in one of two ways:

- **GitHub:** open the Security tab of the affected repository and choose "Report a vulnerability".
- **E-mail:** write to [info@ledger-direct.com](mailto:info@ledger-direct.com).

Please include the repository and version, what an attacker can do, and the steps to reproduce it.

## Responsible disclosure

We confirm receipt within 5 business days, investigate the report privately and keep you informed
while we fix it. Please do not disclose the vulnerability until a fix is published and users have
had time to upgrade. Test only against your own installations and on test networks, never against
other people's systems or with funds on a main network, and refrain from anything that puts our
users, the project or its maintainers at risk.

## Scope

In scope: the payment core, the shop plugins, the Laravel package, the payment page
(`ledger-direct-payment-ui`) and the end-to-end test harness (`ledger-direct-e2e`).

Out of scope: third-party wallets, the ledgers themselves (the XRP Ledger, Xahau and others), and
their public test networks and faucets. A vulnerability in a third-party dependency belongs to its
maintainers; tell us as well if LedgerDirect is affected by it.

## Thank you

We appreciate every responsible report and credit you in the security advisory, unless you prefer
not to be named.

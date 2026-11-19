# Unique.domains Datasets

Domain data you can load in one line. The lists of one-word domain names below are public extracts of what [Unique.domains](https://unique.domains/domains?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=top_open_search) reads every day: which names are free to register, what they cost in the first year and what they renew at. They are rebuilt every night, in CSV and JSON, free under CC BY 4.0; the other datasets say how often they change and under which terms in their own README.

Need more than a file? The same rows answer with no key at `https://api.unique.domains/v1/domains`, from Node (`npm install @uniquedomains/sdk`), Python (`pip install uniquedomains`) or an AI assistant (`https://mcp.unique.domains/mcp`). Every ending Unique.domains tracks is on [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=related_hub).

## General

| Dataset                                                                    | Rows  | Live names  | Page                                                                                                                                                | Median ask |
| -------------------------------------------------------------------------- | ----- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| [All](https://github.com/UniqueDomains/oneword-domains)                    | 1,000 | ~16,700,000 | [Open the page](https://unique.domains/domains?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)            | ~$146.37   |
| [Expired](https://github.com/UniqueDomains/expired-oneword-domains)        | 1,000 | 10,860      | [Open the page](https://unique.domains/domains/expired?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)    | $781.51    |
| [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)      | 1,000 | 52,494      | [Open the page](https://unique.domains/domains/expiring?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)   | $20,825.23 |
| [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)    | 1,000 | ~227,000    | [Open the page](https://unique.domains/domains/brandable?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)  | ~$285.97   |
| [Positive](https://github.com/UniqueDomains/positive-oneword-domains)      | 1,000 | ~5,470,000  | [Open the page](https://unique.domains/domains/positive?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)   | ~$165.26   |
| [Short](https://github.com/UniqueDomains/short-oneword-domains)            | 1,000 | ~6,790,000  | [Open the page](https://unique.domains/domains/short?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)      | ~$198.47   |
| [Actionable](https://github.com/UniqueDomains/actionnable-oneword-domains) | 1,000 | ~2,490,000  | [Open the page](https://unique.domains/domains/actionable?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page) | ~$180.23   |
| [Domain hacks](https://github.com/UniqueDomains/hacks-oneword-domains)     | 1,000 | 1,446       | [Open the page](https://unique.domains/domains/hacks?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)      | $3,474.28  |

## By TLD

| Dataset                                                      | Rows  | Live names | Page                                                                                                                                     | Median ask |
| ------------------------------------------------------------ | ----- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| [.COM](https://github.com/UniqueDomains/com-oneword-domains) | 1,000 | 3,826      | [Open the page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page) | $7,325.77  |
| [.AI](https://github.com/UniqueDomains/ai-oneword-domains)   | 1,000 | 18,086     | [Open the page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)  | $88.20     |
| [.IO](https://github.com/UniqueDomains/io-oneword-domains)   | 1,000 | 21,042     | [Open the page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)  | $107.94    |
| [.APP](https://github.com/UniqueDomains/app-oneword-domains) | 1,000 | 22,851     | [Open the page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page) | $37.81     |
| [.CO](https://github.com/UniqueDomains/co-oneword-domains)   | 1,000 | 21,901     | [Open the page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page)  | $482.68    |
| [.XYZ](https://github.com/UniqueDomains/xyz-oneword-domains) | 1,000 | 24,871     | [Open the page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=open_the_page) | $445.70    |

## Other datasets

| Dataset                                                                                                 | Contents                                                 | Page                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Trending domains and business ideas](https://github.com/UniqueDomains/trending-domains-business-ideas) | The 5 open names of each daily edition, with their trend | [Open the page](https://unique.domains/trending-domains?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=other_dataset_page) |
| [New gTLD applications 2026](https://github.com/UniqueDomains/new-gtld-applications-2026)               | The applications ICANN published for the 2026 round      | [Open the page](https://unique.domains/tld/applications?utm_source=github&utm_medium=referral&utm_campaign=org_profile&utm_content=other_dataset_page) |

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install @uniquedomains/sdk`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`

# Snowpark Container Services (SPCS) Security Whitepaper

A personal, best-effort collection of information about the security architecture of Snowflake's Snowpark Container Services (SPCS), together with general guidance for operating SPCS workloads in production.

> ## Disclaimer
>
> **This is a personal project of the author. It is not an official Snowflake publication and has not been reviewed, endorsed, or approved by Snowflake.**
>
> The content gathers publicly available information, field experience, and the author's own validation testing on a best-effort basis. **No guarantee is given that any of it is correct, complete, or up to date.** Snowflake features and behavior change frequently. Always validate statements against the current [Snowflake documentation](https://docs.snowflake.com/) and, where relevant, with Snowflake directly before relying on them.
>
> Nothing in this repository constitutes legal, compliance, or security advice, or a contractual commitment by Snowflake. Opinions expressed are the author's own.

## Documents

| Document | Description |
|---|---|
| [SPCS Security Architecture (PDF)](spcs-security-whitepaper.pdf) | How SPCS is secured: compute pools, services, image registry, network and communication paths, runtime hardening, observability, and operational caveats |
| [SPCS Security Best Practices (PDF)](spcs-security-best-practices.pdf) | General guidance and an informal helper checklist for customers taking SPCS workloads into production. These are guidelines, not hard requirements. |

## Feedback

Corrections and suggestions are welcome. Please open an issue.

## License

Released under the [MIT License](LICENSE).

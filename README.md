\# AI Robots Communication Standard (airobots.md)



A comprehensive, community-driven framework for AI agent permissions, resource sharing, and inter-AI communication





\## Why airobots.md?



Traditional 'robots.txt' was designed for simple web crawling in the 1990s. Today's AI ecosystem needs something far more sophisticated:



\- \*\*Granular Permissions\*\*: Different rules for training vs. inference vs. research

\- \*\*Economic Framework\*\*: Licensing, attribution, and compensation mechanisms  

\- \*\*AI-to-AI Communication\*\*: Standardized protocols for resource sharing and collaboration

\- \*\*Dynamic Negotiation\*\*: Real-time permission elevation and capability exchange



\## Key Features



\### 🎯 \*\*Multi-Scope Permissions\*\*

\### Model Training

\*\*Scope: training/\*\*

\- Allow: /articles/, /images/

\- License: CC-BY-SA-4.0

\- Commercial: Restricted

\- Attribution: Required



\### Research Access  

\*\*Scope: research/\*\*

\- Allow: /datasets/

\- Registration: Required

\- Collaboration: Open

```



\### 🤝 \*\*AI-to-AI Communication Protocol\*\*

\- Standardized agent identification and capabilities

\- Resource discovery and sharing mechanisms

\- Real-time research collaboration frameworks

\- Secure communication channels (TCP 8367)



\### 💰 \*\*Economic Integration\*\*

\- Micropayment systems for training data usage

\- Flexible licensing terms and attribution requirements

\- Support for both free and commercial access models



\### 🔒 \*\*Enhanced Security\*\*

\- Cryptographic agent authentication

\- Rate limiting and abuse prevention

\- Privacy-preserving data access controls



See our Examples directory for common use cases.
https://github.com/pchavez67/ai-robots-communication-standard/tree/main/examples



\### Multi-Platform Discovery



airobots.md supports flexible discovery across different platforms:



\# Primary: Well-Known URI (RFC 8615)

https://example.com/.well-known/airobots.md



\# Secondary: DNS TXT Record  

dig TXT \_airobots.example.com

\# Returns: "v=airobots1; policy=https://example.com/.well-known/airobots.md"



\# Fallback: Root Directory

https://example.com/airobots.md



\# Legacy: Traditional robots.txt

https://example.com/robots.txt



This approach works across:

\- \*\*Web servers\*\* (/.well-known/ standard)

\- \*\*IoT devices\*\* (DNS-based discovery)

\- \*\*Mobile apps\*\* (platform-specific endpoints)

\- \*\*API services\*\* (native integration)

\- \*\*Edge computing\*\* (distributed discovery)



\## Example: News Website



\# AI Robots Communication Standard - News Corp Example



\## Permissions



\### Web Crawling

\*\*User-agent: \*/\*\*

\- Allow: /articles/

\- Disallow: /subscriber-content/

\- Crawl-delay: 2s



\### Model Training

\*\*Scope: training/\*\*

\- Allow: /articles/published-before/2023/

\- License: Custom license required

\- Contact: licensing@newscorp.com

\- Attribution: Required



\### Research Access

\*\*Scope: research/\*\*

\- Allow: /articles/

\- Registration: academic-license@newscorp.com

\- Embargo: 7-days

\- Commercial: Prohibited





\## Why Community-Driven?



Unlike corporate-controlled standards, airobots.md is built through:



\- \*\*Open Development\*\*: All changes discussed publicly

\- \*\*Multi-Stakeholder Input\*\*: AI companies, publishers, researchers, civil society

\- \*\*IETF-Style Consensus\*\*: No single entity controls the standard

\- \*\*Rough Consensus and Running Code\*\*: Technical merit drives decisions



\## Current Status



🚧 \*\*Internet-Draft Available\*\*: View the full specification - https://github.com/pchavez67/ai-robots-communication-standard/blob/main/AI%20Robots%20Communication%20Standard.md



📋 \*\*Seeking Community Input\*\*: We want your feedback before formal standardization



🤝 \*\*Building Working Group\*\*: Join discussions about governance structure



\## Get Involved



\- \*\*💬 \[Join Discussions]\*\* - Share ideas and feedback

\- \*\*📝 \[Review the Draft]\*\* - Comment on technical details  

\- \*\*📧 \[Contact Us](mailto:paul@chavezailabs.com)\*\* - Interested in the working group?



\## Roadmap



\- \*\*Phase 1\*\*: Community feedback and iteration

\- \*\*Phase 2\*\*: Reference implementation and tooling

\- \*\*Phase 3\*\*: IETF working group formation

\- \*\*Phase 4\*\*: Industry adoption and deployment



\## Comparison with Existing Solutions



| Feature | robots.txt | llms.txt | airobots.md |

|---------|------------|----------|-------------|

| \*\*Discovery Methods\*\* | Root only | Root only | Multi-platform |

| \*\*Granular Permissions\*\* | ❌ | ⚠️ Limited | ✅ Full |

| \*\*Economic Framework\*\* | ❌ | ❌ | ✅ Built-in |

| \*\*AI-to-AI Protocol\*\* | ❌ | ❌ | ✅ Complete |

| \*\*Dynamic Negotiation\*\* | ❌ | ❌ | ✅ Supported |

| \*\*Platform Flexibility\*\* | ❌ | ❌ | ✅ Cross-platform |

| \*\*Community Governance\*\* | ❌ | ⚠️ Limited | ✅ Core Design |



\## Implementation Support



\- \*\*Parsing Libraries\*\*: Python, JavaScript, Go implementations

\- \*\*CMS Plugins\*\*: WordPress, Drupal, Ghost integrations  

\- \*\*Validation Tools\*\*: Syntax checkers and best practice guides

\- \*\*Migration Utilities\*\*: Convert from robots.txt



\## About



Created by Paul Chavez at \[Chavez AI Labs](https://chavezailabs.com) with community input.



\*\*Why we're doing this\*\*: AI is transforming how we interact with information. We need standards that respect content creators while enabling legitimate AI innovation. airobots.md provides that balance through community-driven governance.



\## License



This standard is released under the \[MIT License](LICENSE) to ensure maximum adoption and community contribution.



---



\*\*⭐ Star this repo if you believe AI needs better standards!\*\*



\*\*🔗 Share with others working on AI governance and web standards\*\*



\*\*💬 Start a discussion about your use case\*\*


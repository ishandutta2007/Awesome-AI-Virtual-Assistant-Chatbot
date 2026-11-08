# Awesome-AI-Virtual-Assistant-Chatbot

# Awesome-AI-Virtual-Assistant-Chatbot

# Awesome-AI-Virtual-Assistant-Chatbot

**Top AI Virtual Assistant Chatbot (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Conversational AI, Visual Flow Builders, Voice Assistants & Self-Hosted Agent Frameworks*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Virtual Assistant & Chatbot**. These tools enable organizations to build, deploy, and manage conversational agents across text and voice channels—from fully managed platforms with LLM-native assistants and outcome-based pricing to open-source frameworks that give teams complete control over their conversation data and model choice.



**Examples** include Kore.ai, IBM watsonx Assistant, Zoho SalesIQ Zia Agents, Yellow.ai, LivePerson, Intercom Fin, Zendesk AI, Ada, Freshworks Freddy, and Drift (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted virtual assistants, voice agents, and open conversational AI. **Critical note**: The open-source landscape is genuinely functional—**Cel.ai** is a modern framework specifically designed for omnichannel assistants with multi-assistant routing and LangChain integration , while **Rasa** remains the enterprise NLU standard with a large community and full self-hosting control . **Botpress** offers a visual flow builder and deployment options, though its v12 self-hosted documentation is the primary open reference . No open-source project matches Kore.ai's enterprise contact center depth or IBM watsonx's Conversational Search RAG, but for core assistant functionality, the options are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Kore.ai**

  **Enterprise virtual assistant platform** with self-service and enterprise tiers. **Pricing**: **Pay-as-you-go model**—start with **5,000 free sessions**, then reload accounts from **$100** and pay only for consumed sessions . **Free tier**: Yes, 5,000 sessions (max 5 bots per account) . **Best for**: enterprises wanting full control over conversation design, NLP training, and deployment—**trade-off**: session-based metering; enterprise features gated by plan tier.



- **IBM watsonx Assistant**

  **Conversational AI platform** with generative AI and voice add-ons. **Pricing**: **Lite (free)**—basics for building chatbots; **Plus**—**starts at $140/month including 1,000 MAUs**; additional MAUs **$14 per 100 MAUs**; **Resource Units (RUs)** billed at **$0.60 per 1,000 RUs** (1 RU = 1,000 tokens); **Voice add-on $9 per 100 voice MAUs** . **Free tier**: Yes, Lite plan. **Best for**: organizations wanting IBM's enterprise governance and optional voice—**trade-off**: MAU and RU metering requires usage modeling; voice adds cost .



- **Zoho SalesIQ (Zia Agents)**

  **AI agents within Zoho's customer engagement platform**. **Note**: Search results surface Zoho Virtual Assistant consultation services on Upwork, not a standalone Zoho virtual assistant product . Zoho's actual AI agent capability is Zia Agents within SalesIQ; verify current product positioning directly with Zoho. **Free tier**: SalesIQ Free plan available. **Best for**: Zoho ecosystem users wanting agents within their customer engagement stack.



- **Yellow.ai**

  **Conversational AI platform** with freemium and premium tiers. **Pricing**: **Freemium**—**5,000 monthly bot conversations**, unlimited agent seats, **500 chat/email tickets/month**, 2 channels, FAQ module; **Premium**—custom pricing via sales. **Free tier**: Yes, 5,000 conversations/month. **Best for**: teams wanting a genuine free tier to evaluate conversational AI—**trade-off**: freemium lacks Doc Cog, Data Explorer, SMS, and Voice; premium requires sales engagement.



- **LivePerson**

  **Conversational Cloud** for enterprise messaging. **Pricing**: **Bronze/Silver/Gold tiers**; **Engagement Credits per Daily Active Relationship (DAR)**; **SMS/WhatsApp channel fees plus 15% handling fee**; Intent Manager adds **0.2 credits per DAR** for listening. Reviewers note standalone cost as expensive with non-straightforward integration . **Free tier**: None. **Best for**: large enterprises wanting messaging-first engagement across channels—**trade-off**: channel fees and handling fees stack; credit-based pricing requires volume modeling.



- **Intercom Fin**

  **AI-first support platform** with Fin AI Agent. **Pricing**: **Essential from $0.99/seat/month** (annual) plus **Fin at $0.99 per outcome**; **Advanced $85/seat/month**; **Expert $132/seat/month**; **Copilot add-on $29/agent/month**. **Free tier**: No permanent free tier; trial available. **Best for**: teams wanting AI resolution priced per successful outcome—**trade-off**: seat + per-outcome costs stack; minimum monthly commitment applies.



- **Zendesk AI**

  **AI agents within Zendesk** with outcome-based pricing. **Pricing**: **Support Team $19/agent/month**; **Suite $55**; AI agents included with **automated resolution allowance per agent**; overages **$1.50 committed or $2.00 pay-as-you-go**. **Free tier**: No free plan; trial available. **Best for**: Zendesk customers wanting AI resolution integrated with their helpdesk—**trade-off**: resolution definition is contractual; commitments lock in volume.



- **Ada**

  **Agentic customer experience** platform. **Pricing**: **AWS Marketplace entry $33,000/year for 60,000 conversations**; Capterra/GetApp list starting at **$60,000 annually**. **Free tier**: **No free plan, no free trial**. **Best for**: enterprises wanting deep system integrations for end-to-end resolution—**trade-off**: high entry price; implementation adds $15,000–$100,000+.



- **Freshworks Freddy AI**

  **AI agent within Freshworks**. **Pricing**: **Freddy AI Agent $49 per 100 sessions**; **Copilot $29/agent/month**; Growth plan **$19/agent/month** (annual). **Free tier**: Free plan up to 10 agents; 14-day Enterprise trial. **Best for**: SMBs wanting accessible AI chatbot at per-session pricing—**trade-off**: AI sessions metered separately from seats.



- **Drift**

  **Conversational AI and sales engagement** platform. **Pricing**: **Free** (10 queries/month); **Pro $29.99/month** (unlimited queries); **Standard $9.99/month** (50 queries). **Free tier**: Yes, 10 queries/month. **Best for**: teams wanting quick AI chat with a usable free tier—**trade-off**: query limits on free/standard; Pro subject to fair use.



## Open-Source GitHub Projects



- **Cel.ai**

  **Open-source framework for omnichannel AI virtual assistants** (open source) — **the most purpose-built open-source framework for multi-channel assistants**, designed for self-hosting and flexibility . **Features**: **Multi-assistant router**—logic router based on state variables, **agentic router based on user intent and context** (keeps prompts small and focused), semantic router coming soon; **Connectors**—WhatsApp, Telegram, VAPI.ai (voice), Chatwoot; **Powered by LangChain** with LangSmith user tracing; moderation and blacklist middlewares; invitations; Ngrok native integration; user sequential message processing . **Tech stack**: Python. **Deploy**: `pip install celai`; self-hosted. **Trade-off**: **Newer framework**—smaller community than Rasa or Botpress; requires Python and connector-specific setup. **Best for**: developers wanting to build omnichannel assistants (messaging + voice) with a modular, router-based architecture—especially those wanting to avoid hosted platform lock-in .



- **Rasa**

  **Open-source machine learning framework for automated text and voice conversations** (Apache 2.0) — **the enterprise NLU standard**, with a large community and full self-hosting control . **Features**: **NLU and dialogue management**—train custom models for intent recognition and entity extraction; **connect to Slack, Facebook, and more**; **create chatbots and voice assistants**; enterprise deployment features in Rasa Pro (commercial). **Tech stack**: Python. **Deploy**: `pip3 install rasa`; self-hosted . **Trade-off**: **Framework, not a product**—no inbox, no widget, no helpdesk; you build the application layer. **Best for**: banks and regulated enterprises with ML teams needing full control over their NLU pipeline—especially those already invested in the Rasa ecosystem.



- **Botpress**

  **Visual chatbot builder** (open source) — **the most accessible open-source visual flow builder** for designing chat flows without coding everything by hand. **Features**: **Visual flow editor**; multi-channel deployment (Slack, MS Teams, website, Telegram); built-in NLU; native extensions . **Tech stack**: TypeScript, Node.js. **Deploy**: Self-hosted (v12 documentation available) or Botpress Cloud . **Trade-off**: **v12 self-hosted documentation is the primary open reference**; newer versions are Cloud-first. **Best for**: teams wanting a visual builder on self-hosted infrastructure—verify current self-hosting support directly with Botpress.



### Additional Strong Open-Source Options



- **elizaOS (eliza)** — Open-source framework for AI agents (open source, TypeScript). Multi-platform agent runtime with plugins for Discord, Twitter, Telegram, and more; CLI scaffolding and local mock stack . **Note**: **General-purpose agent framework**—not a customer support platform; broader than virtual assistants. **Best for**: developers wanting a flexible, multi-platform agent foundation.



**Frameworks for building custom systems**: Combine **Cel.ai** for omnichannel routing with **Rasa** for custom NLU and **Botpress** for visual flow design—creating a layered open-source virtual assistant stack. **None match Kore.ai's contact center depth or watsonx's Conversational Search RAG**, but for core assistant functionality, the options are production-capable.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Virtual assistant platforms handling customer conversations must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "enterprise platform" vs. "omnichannel framework" vs. "NLU framework" vs. "visual builder" distinction is critical.** **Kore.ai, IBM watsonx, Yellow.ai, LivePerson, Intercom Fin, Zendesk AI, Ada, Freshworks Freddy, and Drift** are **enterprise platforms**—they provide contact center integrations, voice channels, and governance . **Cel.ai** is an **omnichannel framework**—it routes messages across channels with multi-assistant orchestration . **Rasa** is an **NLU framework**—it trains custom models but requires you to build the application layer . **Botpress** is a **visual builder**—it provides flow design with deployment options . **Choose based on whether you need a turnkey enterprise platform, omnichannel routing, custom NLU, or a visual builder.**

- **Kore.ai's pay-as-you-go model is the most accessible enterprise entry point**—**5,000 free sessions**, then reload from **$100** and pay only for consumed sessions . **The trade-off**: session-based metering; enterprise features gated.

- **IBM watsonx Assistant's Plus plan starts at $140/month for 1,000 MAUs**—additional MAUs are **$14 per 100**, and RUs for generative features are **$0.60 per 1,000** . **Voice adds $9 per 100 voice MAUs** .

- **LivePerson's cost is noted as expensive** by reviewers, with non-straightforward integration to other platforms . **Model your channel mix and DAU before committing.**

- **Cel.ai is the most purpose-built open-source omnichannel framework**—multi-assistant routing, LangChain integration, and connectors for WhatsApp, Telegram, and voice . **The trade-off**: newer project with smaller community.

- **Rasa remains the enterprise NLU standard** with full self-hosting control . **The trade-off**: framework, not product; you build the application layer.

- **Botpress's self-hosting story is v12-focused**—verify current support before committing to self-hosted deployment .

- Self-hosted open-source solutions require proper infrastructure (Python for Cel.ai and Rasa, Node.js for Botpress), security hardening, and ongoing maintenance. **Virtual assistant data includes customer conversations and PII**—ensure your deployment meets your organization's privacy and compliance requirements before handling live customer interactions.



---



**Made for conversational AI developers, support teams, and organizations building transparent virtual assistant solutions.**

Let's make AI Virtual Assistant Chatbots more open, data-driven, and conversation-friendly.

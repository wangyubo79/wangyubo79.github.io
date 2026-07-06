# Developer Relations in the AI Era

## From platform evangelism to trust-building for AI-augmented developers

The developer has changed.

That sentence sounds dramatic, but it is now a practical hiring reality. In 2026, a "developer" can mean a senior staff engineer maintaining a mature codebase, a startup founder building a prototype with Cursor, Codex, or Claude Code, a product manager wiring together a demo with a cloud database and deployment stack, a designer turning an idea into a working app through prompts, or a non-programmer who cannot explain the framework they used but can still ship a functional product with AI.

This shift matters for Developer Relations because DevRel has always been downstream of one question: who is the developer, and what does that developer need in order to adopt a platform?

For a long time, the answer was familiar. Developers needed documentation, sample code, conference talks, tutorials, community spaces, and someone credible enough to translate between the product team and the outside world. That work still matters. But AI coding has changed the moment of need. The bottleneck is no longer only "How do I call this API?" It is increasingly "Can I trust this generated implementation?", "What should I ask the model to do?", "How do I evaluate the result?", "What parts of this workflow should stay human?", and "How do I turn a magical demo into a maintainable system when I may not understand every line of code?"

That is why Developer Advocate and Developer Relations Engineer roles are not disappearing in the AI Era. They are becoming more technical, more workflow-oriented, and more tied to trust.

The new DevRel mandate is not simply to make developers aware of a product. It is to help a wider, AI-augmented builder population adopt tools safely, productively, and with judgment. Some of those builders are expert programmers. Some are "vibe coders" whose primary interface to software is natural language in tools such as Codex, Claude Code, Cursor, Replit, or Lovable.

## Where DevRel came from

Developer Relations did not begin as a polished function with dashboards, community programs, and lifecycle metrics. It began as platform survival.

The roots are usually traced to Apple in the early 1980s. Apple needed third-party developers to build software for the Macintosh before the Mac had an obvious installed base. The term "software evangelist" is commonly credited to Mike Murray at Apple, with Mike Boich and Guy Kawasaki becoming closely associated with the early practice of persuading developers to bet on the Mac platform. Kawasaki later popularized technology evangelism more broadly through his work around Macintosh adoption.

The point was not content marketing in the modern sense. It was ecosystem creation. A platform without applications was not a platform. Evangelism was the human layer that helped make a risky technical bet feel credible.

The model spread. Microsoft built developer programs around Windows and its tools. Netscape trained technology evangelists in the 1990s, with Wired describing a "charm school" for people who needed technical fluency, presentation skill, partner management, and media confidence. The pattern was already visible: the best evangelists were not just speakers. They were technical translators, adoption strategists, and relationship builders.

In the 2010s, the center of gravity moved from operating systems and packaged software to APIs, cloud platforms, open source, and developer-first SaaS. Twilio's famous "Ask Your Developer" positioning captured a broader truth: developers had become influential buyers and architects of business capability. Stripe made documentation and API design part of the product experience. GitHub turned collaboration into a developer social graph. Cloud providers scaled developer programs globally. Open-source companies learned that community was not a side channel; it was the distribution model.

That is where the language changed. "Evangelist" did not disappear, but "Developer Relations" and "Developer Advocate" became more common because the job was no longer only persuasion. It was education, feedback, community, developer experience, and trust.

A useful way to split the modern titles:

- **Developer Advocate**: outward-facing education, community, talks, demos, tutorials, feedback collection, and public credibility.
- **Developer Relations Engineer**: more engineering-heavy, with emphasis on sample apps, SDKs, integrations, reference architectures, docs, developer experience, and technical adoption.

The thread running through both is this: DevRel exists when developer adoption is strategically important but cannot be won by product alone.

## What the old JD asked for

Before AI coding became mainstream, a strong Developer Advocate job description usually asked for some combination of:

- technical credibility with the target developer audience
- public speaking and conference presence
- blog posts, tutorials, videos, and workshops
- sample code and demo apps
- community engagement across Discord, Slack, GitHub, forums, meetups, and social channels
- product feedback from external developers back into engineering and product teams
- comfort moving between engineering, marketing, product, and sales-adjacent conversations

The metrics were often fuzzy but recognizable: developer signups, API keys created, SDK downloads, GitHub stars, docs traffic, event attendance, community growth, content reach, activated users, and qualitative product feedback.

That old job was already hybrid. It sat between education and marketing, engineering and community, product and support. But the core assumption was that the developer wanted to understand and use the product directly.

AI coding complicates that assumption. Developers are no longer always hand-writing the first draft. They may be prompting Codex or Claude Code, accepting a generated patch, asking an IDE to explain a codebase, generating tests, or letting a tool scaffold an entire application. Some may not know the programming language, framework, database model, or deployment target in any serious way. They can still produce something that looks and behaves like software. That changes what "education" means. A tutorial that only shows the happy path is less useful when the user's actual workflow includes AI-generated uncertainty.

The new question is not only "Can the developer use the tool?" It is "Can the developer and their AI assistant use the tool correctly enough to create durable software?"

## Classic DevRel vs AI-era DevRel

| Dimension | Classic DevRel | AI-era DevRel |
|---|---|---|
| Primary audience | Professional developers using APIs, SDKs, platforms, or open-source tools | Professional developers plus founders, product builders, AI-native teams, non-traditional builders, and non-programmers building through prompts |
| Core job | Explain the product and inspire adoption | Shape workflows that combine human judgment, AI tools, and product primitives |
| Main artifacts | Talks, blog posts, tutorials, sample apps, docs, workshops | Live build sessions, AI-assisted reference workflows, eval examples, agent patterns, guardrails, migration guides |
| Proof of value | "Look how easy this API is" | "Look how reliably this workflow ships under real constraints" |
| Product feedback | Bugs, missing docs, confusing APIs, feature requests | Model failure modes, context gaps, evaluation pain, generated-code risks, trust barriers |
| Community role | Convene and educate developers | Help builders compare practices, verify outputs, and build confidence under uncertainty, including when they did not write the code themselves |
| Success metric | Awareness, activation, community growth | Activation plus durable adoption, repeated workflow use, developer trust, reduced confusion, better feedback loops |

The shift is subtle but important. Classic DevRel often helped developers cross the gap between ignorance and usage. AI-era DevRel helps developers cross the gap between usage and confidence.

## What hot-company hiring signals show

Public job descriptions change quickly, and not every company uses the exact title "Developer Relations Engineer." So the right way to read the market is not to overfit to one posting. It is to look for repeated signals across developer-facing AI and infrastructure companies.

Here are three companies worth watching. This is intentionally a small set: the goal is not to catalog every AI developer-tool company, but to identify what the most visible AI platforms are asking developer-facing teams to do now.

| Company | Public hiring or ecosystem signal | Audience | What the role seems to require | What changed from classic DevRel |
|---|---|---|---|---|
| OpenAI | OpenAI's developer ecosystem now spans APIs, ChatGPT, Codex, agent-building surfaces, and software-development workflows. Public product signals around Codex show OpenAI treating coding agents as a mainstream developer interface, not a niche assistant. | API developers, AI app builders, professional engineers adopting Codex, startups, and non-programmer builders using ChatGPT/Codex to create software | Ability to teach agentic development, API integration, prompt-to-product workflows, evaluation, safety constraints, and the difference between demos and production systems | DevRel must explain a fast-moving platform where the "developer tool" may be an API, an agent, a chat interface, or a coding environment |
| Anthropic | Business Insider reported an "Applied AI Claude Evangelist" role with a $240k-$315k salary range, focused on startups, technical onboarding, demos, tutorials, live sessions, and feedback to internal teams. | Startup founders, developers, accelerators, venture ecosystem | High technical fluency, room-commanding communication, hands-on onboarding, ability to turn curiosity into active building | DevRel becomes a live adoption catalyst for AI workflows, not just a content function |
| Google | Current Google Careers postings for Senior Developer Relations Engineer roles in AI Infrastructure and AI Developer Tools make the requirement explicit: DevRel now sits close to Gemini, Google Cloud, DeepMind, GKE, GPUs/TPUs, and AI developer tooling. | Cloud, AI/ML, infrastructure, enterprise architect, and developer-tool builders | Technical role experience, programming ability, AI/ML workload fluency, GPUs/TPUs, Kubernetes or GKE, developer content, sample code, community engagement, and feedback into product teams | DevRel moves from ecosystem navigation to builder-first proof: running real workloads, exposing scaling friction, and turning hard infrastructure problems into teachable developer practice |

The strongest signal is not that DevRel is becoming one single role. It is that the biggest AI platforms need people who can combine product fluency, engineering taste, live teaching, and ecosystem sense.

Google's current DevRel postings make that shift unusually concrete. The AI Infrastructure role asks for hands-on experience running training, fine-tuning, or inference workloads on GPUs or TPUs, including orchestration with Kubernetes or GKE, plus the ability to turn those workflows into developer content. The AI Developer Tools role is broader but points in the same direction: write sample code, troubleshoot developer problems, represent developer and enterprise architect needs internally, and influence the roadmap for first-party AI Dev Tools. That is a deeper requirement than "explain Gemini." It is closer to proving that the platform works under production-shaped constraints, then translating the proof into docs, demos, workshops, and product feedback.

This suggests a useful split in AI Era DevRel. One side is AI workflow adoption: helping builders use models, agents, tools, and coding assistants with judgment. The other is AI infrastructure credibility: showing that the systems underneath the magic can scale, be debugged, and survive real workloads. The best Developer Relations Engineers will be able to move between both modes. They will not only tell the story of the product; they will create the evidence that makes the story believable.

OpenAI is the broadest version of the problem. Its developer surface is no longer just "call this model API." It includes ChatGPT as a builder interface, Codex as an agentic coding environment, APIs for app developers, and workflow tools for teams trying to decide how much autonomy to give AI. A Developer Relations Engineer in this world has to teach not only syntax and endpoints, but also taste: when to let the agent act, when to constrain it, how to evaluate output, and how to move from a prompt-generated prototype to something maintainable.

Anthropic's role is especially revealing because it revives the "evangelist" language in a context where technical belief is expensive. A developer does not merely need to know Claude exists. They need to believe it can fit into their workflow, understand where it fails, and see a path from demo to production. The reported responsibilities - technical onboarding, demos, tutorials, live events, feedback loops - are classic DevRel ingredients, but the intensity is higher because the adoption curve is compressed.

Google shows the scale and infrastructure version of the same challenge. Gemini is not one developer product. It is an ecosystem spanning AI Studio, Gemini API, Vertex AI, Android, Workspace, Chrome, coding assistance, AI developer tools, and the cloud infrastructure underneath production AI. That makes DevRel less about announcing features and more about reducing cognitive load while increasing confidence. The developer-facing job is to help builders answer: which Google AI surface should I use, how do I prototype, how do I integrate, how do I run or tune this workload at scale, and how do I avoid using a powerful model in a brittle or irresponsible way?

## The AI Era adoption paradox

The reason DevRel is changing is not simply that AI tools are popular. It is that AI coding is both useful and hard to trust.

The [2025 Stack Overflow Developer Survey](https://survey.stackoverflow.co/2025/ai/) found that 84% of respondents were using or planning to use AI tools in their development process, up from 76% the year before. Among professional developers, 50.6% reported daily usage. But the same survey found that positive sentiment had dropped from above 70% in 2023 and 2024 to about 60% in 2025. More importantly, Stack Overflow reported that more developers distrusted AI tool accuracy than trusted it: 46% actively distrusted accuracy, while 33% trusted it, and only 3.1% highly trusted the output.

That is the DevRel opening. Adoption is high. Trust is not.

The productivity story is also more complicated than the hype cycle suggests. A 2025 randomized controlled trial by METR studied 16 experienced open-source developers working on 246 tasks in mature repositories. Developers expected AI tools to reduce completion time by 24%. Afterward, they still believed AI had reduced time by 20%. But the measured result went the other way: tasks took 19% longer when AI tools were allowed.

That does not prove AI coding is bad. It proves that the adoption problem is not solved by access. Experienced developers still need workflows for context, review, cleanup, testing, and judgment. In other words, the market needs education around practice, not just tooling.

GitLab's 2026 DevSecOps research, as covered by TechRadar, points in the same direction: organizations are using multiple AI coding tools, developers report faster code writing, but review, validation, and governance are becoming bottlenecks. The output layer accelerates; the accountability layer strains.

Vibe coding research gives this a useful vocabulary. In the empirical paper ["Vibe coding: programming through conversation with artificial intelligence"](https://arxiv.org/abs/2506.23253), Advait Sarkar and Ian Drosos describe a workflow where programmers alternate between prompting, scanning, testing, and manual intervention. Their core conclusion is not that expertise disappears. It moves. Programming expertise shifts toward context management, rapid evaluation, debugging judgment, and knowing when to move from AI-driven generation back to manual control.

But the social consequence is bigger than a workflow change for existing engineers. AI coding lets people who do not know programming create apps anyway. With tools like Codex and Claude Code, a builder can describe intent, ask the agent to modify files, run tests, fix errors, and iterate toward a working product. That is the most disruptive part for DevRel. The developer audience now includes people who can describe intent, inspect behavior, and iterate through prompts, but who may not know how to reason about dependency risk, data modeling, authentication, permissions, deployment, or long-term maintainability. They are builders, but not necessarily programmers. They can create value, but they are also exposed to a new kind of fragility.

That is exactly where DevRel has to evolve. If the developer's new work is supervisory, evaluative, and workflow-driven, then DevRel's teaching must become supervisory, evaluative, and workflow-driven too.

## North America and APAC are showing different adoption surfaces

North America remains the most visible market for frontier AI labs and AI-native developer tool companies. That is where the highest-signal public roles tend to appear first: AI evangelists, developer advocates, developer experience roles, community engineers, and deeply technical content roles. The pattern is especially strong around San Francisco, New York, and remote-first developer tooling companies.

The North American signal is: explain the frontier, win the startup ecosystem, and convert intense curiosity into repeatable building behavior.

APAC looks different. The hiring and expansion signal is more regional. Cursor's reported hiring push across Singapore, Japan, Sydney, Melbourne, and India shows how AI coding companies are moving from early adopter concentration into market-by-market adoption. In APAC, developer-facing roles often need more localization, partner awareness, enterprise onboarding, and sensitivity to different developer communities. A workshop that works in San Francisco may not map cleanly to Singapore, Tokyo, Bengaluru, or Sydney.

The APAC signal is: translate the product into local developer workflows, local trust networks, and local enterprise constraints.

This difference should not be overstated. North America also has enterprise adoption work; APAC also has frontier builders. But the public hiring signals suggest different emphasis. North America is where many AI DevRel narratives are born. APAC is where they must become operational across languages, cultures, sectors, and maturity levels.

## The new DevRel skill stack

So what should DevRel professionals learn next?

First, learn AI coding tools as workflows, not toys. It is not enough to say "I use Cursor" or "I tried Claude Code." The useful skill is being able to demonstrate when AI helps, when it misleads, how to structure context, how to review generated code, and how to recover from wrong turns.

Second, learn evaluation. AI-era DevRel needs to explain not only how to build, but how to know whether the thing works. That includes test design, eval datasets, golden paths, regression checks, observability, and human review. For agentic systems, evaluation is not a footnote. It is the product experience.

Third, keep engineering taste sharp. AI makes it easier to produce code, which makes taste more valuable. A Developer Relations Engineer who can look at a generated implementation and say "this will fail in production because the auth boundary is wrong" is far more valuable than one who can only produce a polished demo. This matters even more when the person building the app cannot independently spot that boundary.

Fourth, become bilingual between builders and internal teams. AI coding surfaces strange feedback: model confusion, docs ambiguity, SDK affordances that mislead agents, examples that generate bad patterns, and product gaps that only appear when a user prompts instead of reads. DevRel is well positioned to turn those observations into product intelligence.

Fifth, practice live building. In AI, a static tutorial ages quickly. Live sessions, workshops, office hours, and "build with me" formats reveal the real adoption friction: environment issues, unclear prompts, missing context, security decisions, and evaluation gaps. Anthropic's reported emphasis on moving developers from curiosity to active building in a single event is a strong sign of where the craft is going.

Sixth, learn to teach judgment without killing momentum. The best AI-era DevRel will not be scolds. Developers and non-programmer builders are using AI because it gives them speed, flow, and creative leverage. The job is not to shame that instinct. The job is to help builders preserve the speed while adding enough structure to avoid fragile systems.

## The role is moving closer to the moment of adoption

Developer Relations has always been about making developers successful so the platform succeeds.

In the Apple era, that meant convincing developers to build for a new platform. In the API-first era, it meant helping developers understand, integrate, and advocate for tools inside their companies. In the open-source era, it meant growing ecosystems where community participation was part of the product.

In the AI Era, it means something sharper: helping developers, non-programmer builders, and AI tools build together without losing judgment.

That changes the job description. The best Developer Advocates will still write, speak, demo, and build community. But the center of the role is moving from content to practice. The best Developer Relations Engineers will not merely create sample apps. They will create reference workflows that show how to prompt, generate, inspect, test, deploy, monitor, and revise.

The developer has changed. DevRel has to change with them.

Not by abandoning its roots, but by returning to the original reason the function existed: when a new platform changes what builders can do, someone has to stand at the edge of the ecosystem and help developers cross over.

## Sources

- [Developer relations](https://en.wikipedia.org/wiki/Developer_relations)
- [Technology evangelist](https://en.wikipedia.org/wiki/Technology_evangelist)
- [Guy Kawasaki](https://en.wikipedia.org/wiki/Guy_Kawasaki)
- [Netscape Charm School Trains Evangelists, Wired, 1997](https://www.wired.com/1997/02/netscape-charm-school-trains-evangelists/)
- [Stack Overflow Developer Survey 2025: AI](https://survey.stackoverflow.co/2025/ai/)
- [Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity, METR](https://arxiv.org/abs/2507.09089)
- [Vibe coding: programming through conversation with artificial intelligence](https://arxiv.org/abs/2506.23253)
- [TechRadar coverage of GitLab AI coding governance findings](https://www.techradar.com/pro/speed-without-control-is-a-liability-not-an-advantage-gitlab-study-reveals-ai-code-generation-is-outpacing-controls)
- [Business Insider coverage of Anthropic's Claude Evangelist role](https://www.businessinsider.com/anthropic-hiring-claude-evangelist-salary-2026-5)
- [Business Insider coverage of Cursor's APAC hiring expansion](https://www.businessinsider.com/cursor-hiring-asia-pacific-singapore-japan-australia-india-roles-gtm-2026-5)
- [OpenAI Codex developer docs](https://developers.openai.com/codex)
- [Google Gemini API docs](https://ai.google.dev/gemini-api/docs)
- [Google AI Studio quickstart](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart)
- [Google Careers: Senior Developer Relations Engineer, AI Infrastructure](https://www.google.com/about/careers/applications/jobs/results/81735991508771526-senior-developer-relations-engineer-ai-infrastructure?q=Developer+Relations+Engineer)
- [Google Careers: Senior Developer Relations Engineer, AI Developer Tools](https://www.google.com/about/careers/applications/jobs/results/101104966868837062-senior-developer-relations-engineer-ai-developer-tools?q=Developer+Relations+Engineer)
- [Supabase homepage](https://supabase.com/)
- [LangGraph](https://www.langchain.com/langgraph)
- [Hugging Face Hub docs](https://huggingface.co/docs/hub/index)
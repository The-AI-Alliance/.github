<!-- NOTE to page contributors: please keep this page simple and focused on guiding people to discover, use, and contribute to projects. -->

# Welcome to the AI Alliance

You found the [AI Alliance](https://thealliance.ai) Github organization, where you can learn, use, and contribute to our open source AI projects.

The projects on this page are a prioritized set from across our community, including two types: **Supported Projects** are led and managed by a Member(s) of the AI Alliance (a company, a non-profit, etc.). **Managed Projects** are owned by the AI Alliance. Both types of projects commit to minimum requirements on transparency, contributor opportunity and IP, permissive use licensing, and community conduct. Learn more about our project governance [here](https://thealliance.ai/governance).

<!--
WARNING: Don't remove the next comment nor the "end: focus areas" comment below. They are used for automated copying of this content to the-ai-alliance.github.com GitHub Pages repo.
-->
<!-- start: focus areas -->
# The Open Agent Lab

<a id="open-agent-lab-description" class="anchor"></a>

### Collaborate, Experiment, and Build Production-ready Open Source Agents

The Open Agent Lab is a collaborative community of open source AI projects and domain-specific work groups that seek to make AI Agents successful in the real world through fast experimentation and distillation of learning into usable reference architectures and implementations, and build out of new tools to enable development and deployment.

## Agent Reference Application Hub
(In progress - coming soon!) The agent reference application hub is a repository of continually updated domain-specific implementaitons and architectural components for developing and deploying agents based on the output of our work groups, which include AI researchers, engineers, and subject matter experts from industry leading organizations. Here is some of our initial work:

**Industrial AI / Semiconductors:** check out [SemiKong](https://github.com/aitomatic/semikong) a foundation model for semiconductor process agents.

**Expert knowledge / Legal:** try [Bartlebot](https://github.com/The-AI-Alliance/bartlebot) if you want to work with case law and other legal topics.

**Finance:** see [Example Application for AI in Finance](https://the-ai-alliance.github.io/ai-in-finance-example-app/), a new collaboration between finance and AI experts in the Alliance to explore the practical challenges of building and running trustworthy, production-quality AI-based finance applications.

**Geospatial:** check out projects like [GeoBench](https://github.com/ServiceNow/geo-bench) and [TerraTorch](https://github.com/IBM/terratorch).

<!--
**Chemistry and Materials:** take a look at new science foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted).
-->

**(Coming soon.)** Materials, Health, and Time Series work groups.

## Llama Stack and Llama Stack Agents

The [Llama Stack](https://github.com/meta-llama/llama-stack) project provides standardized APIs, component abstractions, integrations with other open source tools and managed services to help developers build and deploy AI applications and agents.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          Llama Stack Agents <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Deployable, domain-specific use case applications demonstrating the use of <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a>. See also the <a href="#llama-stack">Llama Stack</a> section below.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          Llama Stack
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/meta-llama/llama-stack">repo</a>
            </li>
            <li>
              <a href="https://github.com/meta-llama/llama-stack/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/meta-llama/llama-stack/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Advancing the core <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> project.
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Model Context Protocol (MCP) Ecosystem and Related Projects

The [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) from [Anthropic](https://www.anthropic.com/) is quickly becoming an industry standard for communications between models, agents, data repositories, and other tools. The AI Alliance seeks to advance this protocol and foster a robust suite of tools around it to enable broad, trusted, and high-value use in production.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://ibm.github.io/mcp-context-forge/">MCP Gateway</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/IBM/mcp-context-forge">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/IBM/projects/118">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/IBM/mcp-context-forge/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/IBM/mcp-context-forge/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
           A Model Context Protocol (MCP) Gateway that serves as a central management point for tools, resources, and prompts. It can be accessed by MCP-compatible LLM applications. It converts REST API endpoints to MCP, composes virtual MCP servers with added security and observability, and converts between protocols (e.g., stdio, SSE, etc.). (Principal developer: <a href="https://ibm.com">IBM</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/lastmile-ai/mcp-agent">LastMile AI MCP Agent</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/lastmile-ai/mcp-agent">repo</a>
            </li>
            <li>
              <a href="https://github.com/lastmile-ai/mcp-agent/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/lastmile-ai/mcp-agent/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Build effective agents using Model Context Protocol and simple workflow patterns. (Principal developer: <a href="https://www.lastmileai.dev/">LastMile AI</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/enkryptai/secure-mcp-gateway">Enkrypt AI Secure MCP Gateway</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/enkryptai/secure-mcp-gateway">repo</a>
            </li>
            <li>
              <a href="https://github.com/enkryptai/secure-mcp-gateway/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          A secure MCP gateway built with authentication, automatic tool discovery, caching, and guardrail enforcement.
          It sits between your MCP client and MCP servers. So, by its nature, it also acts as an MCP server as well as an MCP client.
          When your MCP client connects to the gateway, it acts as an MCP server. When the gateway connects to the actual MCP server, it acts as an MCP client.
          (Principal developer: <a href="https://www.enkryptai.com/">Enkrypt AI</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

### The NLIP Project

The <a href="https://nlip-project.org/">NLIP project</a> is facilitating the development of an open-source protocol for intelligent agents to communicate with each other and with humans using natural language.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://nlip-project.org/">NLIP Project</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/nlip-project">GitHub org</a>
            </li>
            <li>
              <a href="https://github.com/nlip-project/ecma_draft1">NC-56 NLIP draft</a>
            </li>
            <li>
              <a href="https://github.com/orgs/nlip-project/projects/3">Dashboard</a>
            </li>
            <li>
              <a href="https://github.com/nlip-project/documents">Other Documents</a>
            </li>
          </ul>
        </td>
        <td>
          The <a href="https://nlip-project.org/">NLIP project</a> is facilitating the development of an open-source protocol for intelligent agents to communicate with each other and with humans using natural language. NLIP is designed to perform the role of a meta-protocol that allows agents from other ecosystems to communicate with one another including interfaces with other protocols such as A2A, ACP, AGNTCY, MCP, NANDA, etc.
          <br/><br/>
          One outcome will be a new <a href="https://ecma-international.org/">ECMA</a> standard, <a href="https://github.com/nlip-project/ecma_draft1">TC-56 NLIP, Natural Language Interaction Protocol</a>. The organization is also developing reference implementations of the protocol and end-points. See the <a href="https://github.com/nlip-project">GitHub organization</a> for details on these implementations.
        </td>
      </tr>
    </tbody>
  </table>
</div>

## AI-Powered Programming Language for Agents

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://aitomatic.github.io/opendxa/">OpenDXA with Dana</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://www.linkedin.com/posts/ctnguyen_aialliance-danalanguage-opendxa-activity-7344578841706708992-_c3X)" target="_blank">Announcement</a>
            </li>
            <li>
              <a href="https://docs.google.com/forms/d/e/1FAIpQLSewvrs-L1XEabZWxljO8ogB4236HMNxzieQt6E4eXON8sPC_g/viewform?pli=1">Interest form</a>
            </li>
          </ul>
        </td>
        <td>
          Domain Expert Agents (DXA) for industrial AI moves beyond AI coding assistants. It helps you write agents that learn, adapt, and improve themselves in production. The Dana language bridges the gap between AI coding assistance and autonomous agents through agent-native programming: native <code>agent</code> primitives, context-aware <code>reason()</code> calls that adapt output types automatically, self-improving pipelines with compositional <code>|</code> ("pipe") operators, and functions that evolve through POET feedback loops (an automated prompt improvement technique). (Principal developer: <a href="https://aitomatic.com/">Aitomatic</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Agent Knowledge and Tool Foundations

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/The-AI-Alliance/agent-lab-ui/">Agent Lab UI</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/agent-lab-ui/">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/agent-lab-ui/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/agent-lab-ui/discussions">discussions</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/agent-lab-ui/wiki">wiki</a>
            </li>
          </ul>
        </td>
        <td>
          AgentLabUI is a web-based interface designed to simplify the creation, management, and deployment of AI agents. It supports integration with Gofannon tools, enabling developers and researchers to rapidly prototype and experiment with sophisticated AI agent architectures.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/gofannon/">Gofannon</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/gofannon/">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/gofannon/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/gofannon/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          A repository of functions consumable by other agent frameworks.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/proscenium/">Proscenium</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/proscenium/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/34/views/2?filterQuery=repo%3A%22The-AI-Alliance%2Fproscenium%22">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/proscenium/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/proscenium/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Collaborative, Asynchronous Human/Agent Interactions.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/lapidarist/">Lapidarist</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/lapidarist/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/34/views/2?filterQuery=repo%3A%22The-AI-Alliance%2Flapidarist%22">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/lapidarist/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/lapidarist/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Document enrichment and knowledge structure (eg knowledge graph) extraction and resolution.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ai-in-finance-example-app/">Example Application for AI in Finance</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-in-finance-example-app/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/42/views/1">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-in-finance-example-app/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-in-finance-example-app/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The <a href="https://the-ai-alliance.github.io/ai-in-finance-example-app/">Example Application for AI in Finance</a> project is a collaboration between finance and AI experts in the Alliance to explore the practical challenges of building and running trustworthy, production-quality AI-based finance applications.
        </td>
      </tr>
      <!--
      <tr>
        <td class="project-title" colspan="2">
          Llama Stack Use Cases <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-usecase1/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Deployable, domain-specific use case applications demonstrating the use of <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a>. See also the <a href="#llama-stack">Llama Stack</a> section below.
        </td>
      </tr>
      -->
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/applying-ai-guide/">The Living Guide to Applying AI</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/applying-ai-guide/">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/applying-ai-guide/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/applying-ai-guide/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Tips from experts on using AI for various applications, including popular <i>design patterns</i>.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/The-AI-Alliance/AllyCat/">AllyCat</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/AllyCat/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/36/views/1">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/AllyCat/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/AllyCat/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          (Beginner friendly!) Get started with a simple and fun end-to-end RAG application that scrapes your website so you can ask it questions.
        </td>
      </tr>
    </tbody>
  </table>
</div>


# Governance, Evaluation and Safety

Safety, accuracy, red-teaming, security, compliance and more are required for successful AI applications. How do we know that AI applications are _trustworthy_, that they are _safe_, meaning free of harmful outputs, that they correctly implement the required behaviors? The following projects address these concerns.

<!-- obsolete...
Deploying a trusted AI system or agent is complex and the gap from prototype to production is still large for most organizations. The AI Alliance has several projects aimed at ensuring agents in production deliver as advertised and can become a trusted foundation to build a business, educate students, perform scientific research, and much more.
-->

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/trust-safety-evals/">Trust and Safety Evaluation</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-evals">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/23">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-evals/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-evals/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Trust and Safety Evaluation addresses two problems: 1) many AI application builders don't know what they should do to ensure trust and safety and 2) it should be as easy as possible add trust and safety capabilities to AI applications. Our projects:
          <ul>
            <li>
              <strong>Catalog of Evaluations:</strong> <a href="https://the-ai-alliance.github.io/trust-safety-evals/taxonomy/taxonomy/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/23/views/1?filterQuery=label%3Ataxonomy">current work</a>
            </li>
            <li>
              <strong>Evaluation Implementations:</strong> <a href="https://the-ai-alliance.github.io/trust-safety-evals/evaluators/evaluators/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/23/views/1?filterQuery=label%3Aevaluators">current work</a>
            </li>
            <li>
              <strong>Leaderboards:</strong> <a href="https://the-ai-alliance.github.io/trust-safety-evals/leaderboards/leaderboards/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/23/views/1?filterQuery=label%3Aleaderboards">current work</a>
            </li>
            <li>
              <strong>Reference Runtime Stack:</strong> <a href="https://the-ai-alliance.github.io/trust-safety-evals/ref-stack/ref-stack/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/23/views/1?filterQuery=label%3A%22reference+stack%22">current work</a>. Key components include <a href="https://www.eleuther.ai/projects/large-language-model-evaluation">lm-evaluation-harness</a> and <a href="https://www.unitxt.ai/">unitxt</a> (see also below).
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ai-application-testing/">Achieving Confidence in Enterprise AI Applications</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-application-testing/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/31">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-application-testing/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-application-testing/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Are you an enterprise developer? How should you test AI applications? You know how to write <em>deterministic</em> tests for your "pre-AI" applications. What should you do when you add generative AI models, which aren't deterministic? This project adapts existing evaluation techniques for the "last mile" of AI evaluation; verifying that an AI application correctly implements its requirements and use cases, going beyond the general concerns of evaluation for safety, security, etc. We are building nontrivial, reusable examples and instructional materials, so you can use these techniques effectively in combination with the traditional tools you already know.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ranking-safety-priorities/">Ranking AI Safety Priorities by Domain</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/ranking-safety-priorities">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/32">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ranking-safety-priorities/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ranking-safety-priorities/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          What are the most important safety concerns for your specific domain and use cases? This project explores these questions in several industries, healthcare, finance, education, and legal, with more to come.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/trust-safety-user-guide/">The AI Trust and Safety User Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-user-guide">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-user-guide/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/trust-safety-user-guide/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Introduction to T&amp;S with guidance from diverse experts.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://www.unitxt.ai/">unitxt</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/IBM/unitxt">repo</a>
            </li>
            <li>
              <a href="https://github.com/IBM/unitxt/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/IBM/unitxt/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
           Unitxt is a Python library for enterprise-grade evaluation of AI performance, offering the world's largest catalog of tools and data for end-to-end AI benchmarking. (Principal developer: <a href="https://research.ibm.com/">IBM Research</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

# Open Trusted Data and Tooling

Good datasets are essential for building good models and applications. The AI Alliance is cataloging datasets, and in some cases building them, that have clear licenses for open use, backed by unambiguous provenance and governance constraints.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/open-trusted-data-initiative/">The Open, Trusted Data Initiative</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-trusted-data-initiative">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/28">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-trusted-data-initiative/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-trusted-data-initiative/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          <em>Open data</em> has clear license for use, across a wide range of topic areas, with clear provenance and governance. OTDI seeks to clarify the criteria for openness and catalog the world’s datasets that meet the criteria. Our projects:
          <ul>
            <li>
              <strong>Open Dataset Catalog:</strong> <a href="https://the-ai-alliance.github.io/open-trusted-data-initiative/catalog/catalog/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/28/views/1?filterQuery=label%3A%22dataset+catalog%22">current work</a>
            </li>
            <li>
              <strong>Define Openness Criteria:</strong> <a href="https://the-ai-alliance.github.io/open-trusted-data-initiative/dataset-requirements/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/28/views/1?filterQuery=label%3A%22dataset+requirements%22">current work</a>
            </li>
            <li>
              <strong>Find Diverse Datasets:</strong> <a href="https://the-ai-alliance.github.io/open-trusted-data-initiative/contributing/#what-kinds-of-datasets-do-we-want">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/28/views/1?filterQuery=label%3A%22diverse+datasets%22">current work</a>
            </li>
            <li>
              <strong>Data Pipelines to Validate Datasets:</strong> <a href="https://the-ai-alliance.github.io/open-trusted-data-initiative/our-processing/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/28/views/1?filterQuery=label%3A%22data+pipelines%22">current work</a>
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://docling-project.github.io/docling/">Docling</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/docling-project/docling/">repo</a>
            </li>
            <li>
              <a href="https://github.com/docling-project/docling/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/docling-project/docling/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Docling simplifies document processing, parsing diverse formats — including advanced PDF understanding — and providing seamless integrations with the gen AI ecosystem. Docling is a key tool for the project <em>Parsing PDFs to Build AI Datasets for Science</em>, discussed above. (Principal developer: <a href="https://research.ibm.com/">IBM Research</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>


# Open Models and Tooling for New Domains and Modalities

The AI Alliance is building new models for many domains and modalities at the intersection of research and engineering. Our projects include models for industrial AI, molecular discovery, geospatial, and time series applications.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://thealliance.ai/focus-areas/foundation-models-datasets">Open Models</a>
        </td>
      </tr>
      <tr>
        <td>
        </td>
        <td>
          Several AI Alliance work groups are collaborating on the development of domain-specific models:
          <ul>
            <li>
              <a href="https://www.semikong.ai/">Semikong</a> - The world's first open LLM tuned specifically for the semiconductor industry. (Principal developers: <a href="https://aitomatic.com/">Aitomatic</a>, <a href="https://www.tel.com/">Tokyo Electron Ltd.</a>, <a href="https://fptsoftware.com/">FPT Software</a>, and  <a href="https://thealliance.ai">The AI Alliance</a>)
            </li>
            <li>
              Llamarine (coming soon!) - An LLM tuned specifically for the needs of the maritime industry.
            </li>
            <li>
              <a href="https://thealliance.ai/working-groups/materials-and-chemistry">Materials and Chemistry work group</a> (Several developers, including <a href="https://research.ibm.com/">IBM Research</a>):
              <ul>
                <li>
                  <a href="https://huggingface.co/ibm/materials.smi-ted">smi-ted</a> - SMILES-based Transformer Encoder-Decoder (SMILES-TED) is an encoder-decoder model pre-trained on a curated dataset of 91 million SMILES samples sourced from PubChem, equivalent to 4 billion molecular tokens. SMI-TED supports various complex tasks, including quantum property prediction, with two main variants (289M and 8×289M).
                </li>
                <li>
                  <a href="https://huggingface.co/ibm/materials.selfies-ted">selfies-ted</a> - SMI-SSED (SMILES-SSED) is a Mamba-based encoder-decoder model pre-trained on a curated dataset of 91 million SMILES samples, encompassing 4 billion molecular tokens sourced from PubChem. The model is tailored for complex tasks such as quantum property prediction and offers efficient, high-speed inference capabilities.
                </li>
                <li>
                  <a href="https://huggingface.co/ibm/materials.mhg-ged">mhg-ged</a> - SELFIES-based Transformer Encoder-Decoder (SELFIES-TED) is an encoder-decoder model based on BART that not only learns molecular representations but also auto-regressively generates molecules. Pre-trained on a dataset of ~1B molecules from PubChem and Zinc-22.
                </li>
                <li>
                  <a href="https://huggingface.co/ibm/materials.smi_ssed">smi-ssed</a> - Molecular Hypergraph Grammar with Graph-based Encoder Decoder (MHG-GED) is an autoencoder that combines a GNN-based encoder with a sequential MHG-based decoder. The GNN encodes molecular input to achieve strong predictive performance on molecular graphs, while the MHG decodes structurally valid molecules. Pre-trained on a dataset of ~1.34M molecules curated from PubChem.
                </li>
              </ul>
            </li>
            <li>
              More to be announced soon.
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/IBM/terratorch">TerraTorch</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/IBM/terratorch">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/IBM/projects/89">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/IBM/terratorch/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/IBM/terratorch/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          TerraTorch is a library based on <a href="https://lightning.ai/docs/pytorch/stable/">PyTorch Lightning</a> and the <a href="https://github.com/microsoft/torchgeo">TorchGeo domain library</a> for geospatial data. (Principal developer: <a href="https://research.ibm.com/">IBM Research</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/ServiceNow/geo-bench">GEO-bench</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/ServiceNow/geo-bench">repo</a>
            </li>
            <li>
              <a href="https://github.com/ServiceNow/geo-bench/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          GEO-Bench is a General Earth Observation benchmark for evaluating the performance of large pre-trained models on geospatial data. (Principal developer: <a href="https://servicenow.com/">ServiceNow</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

# Deployment and Scaling

[Deploying and scaling AI systems](https://thealliance.ai/focus-areas/hardware-enablement), especially to the growing diversity of hardware accelerators for AI, and efficiently scaling from PoCs and single node deployments to large numbers of users and distributed deployments are a key set of challenges.

<div class="table-wrapper">
  <table>
    <thead>
      <tr>
        <th>Links</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ai-accelerator-software-ecosystem-guide/">The AI Accelerator Software Ecosystem Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-accelerator-software-ecosystem-guide">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-accelerator-software-ecosystem-guide/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/ai-accelerator-software-ecosystem-guide/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          A guide to the most common AI accelerators and the software stacks they use to integrate with tools you know, like PyTorch.
        </td>
      </tr>
    </tbody>
  </table>
</div>


<!--
WARNING: Don't remove the next comment nor the "start: focus areas" comment above. They are used for automated copying of this content to the-ai-alliance.github.com repo.
-->
<!-- end: focus areas -->

# AI Alliance Regional Chapters

The AI Alliance is a global organization. However, localization matters and is key to representation. To ensure effectiveness, relevance, and impact across diverse markets and communities, regional chapters of the AI Alliance exist and more are planned:

* [Japan](https://the-ai-alliance.github.io/japan/)
* India - coming soon!
* Paris - coming soon!

## Events
Come meet us and learn about AI! See our [full list](https://thealliance.ai/events) of Alliance-sponsored and third-party AI events.


## Additional Information
* The [AI Alliance GitHub Organization](https://github.com/The-AI-Alliance/)
    * [Contributing](https://github.com/The-AI-Alliance/community/CONTRIBUTING.md) to the AI Alliance [community](https://github.com/The-AI-Alliance/community).
    * The [microsite template](https://github.com/The-AI-Alliance/microsite-template): The template used for Alliance projects, including all the websites listed above. See the [README-template.md](https://github.com/The-AI-Alliance/microsite-template/blob/main/README-template.md) for instructions.
* The [AI Alliance website](https://thealliance.ai): About the AI Alliance, our goals and initiatives.
    * Learn more about [getting involved](https://thealliance.ai/community).

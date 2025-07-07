<!-- NOTE to page ontributors: please keep this page simple and focused on guiding people to discover, use, and contribute to projects. -->

# Welcome to the AI Alliance

You found the [AI Alliance](https://thealliance.ai) Github, where you can learn, use, and contribute to our open source AI projects.

The projects on this page are a prioritized set from across our community, including two types: **Supported Projects** are led and managed by a Member(s) of the AI Alliance (a company, a non-profit, etc.). **Managed Projects** are owned by the AI Alliance. Both types of projects commit to minimum requirements on transparency, contributor opportunity and IP, permissive use licensing, and community conduct. Learn more about our project governance [here](https://thealliance.ai/governance). 

<!--
WARNING: Don't remove the next comment or the "focus areas: end" comment below.
They are used for automated copying of this content to the-ai-alliance.github.com repo.
-->

<!-- focus areas: start -->
# The Open Agent Lab

<a id="open-agent-lab-description" class="anchor"></a>

### Collaborate, Experiment, and Build Production-ready Open Source Agents

The Open Agent Lab is a collaborative community of open source AI projects and domain-specific work groups that seek to make AI Agents successful in the real world through fast experimentation and distillation of learning into usable reference architectures and implementations, and build out of new tools to enable development and deployment.

## Agent Reference Application Hub
(In progress - coming soon!) The agent reference application hub is a repository of continually updated domain-specific implementaitons and architectural components for developing and deploying agents based on the output of our work groups, which include AI researchers, engineers, and subject matter experts from industry leading organizations. Here is some of our initial work:

**Industrial AI / Semiconductors:** check out [SemiKong](https://github.com/aitomatic/semikong) a foundation model for semiconductor process agents.

**Expert knowledge / Legal:** try [Bartlebot](https://github.com/The-AI-Alliance/bartlebot) if you want to work with case law and other legal topics.

**Finance:** coming soon!

**Climate and Geospatial:** check out projects like [GeoBench](https://github.com/ServiceNow/geo-bench) and [TerraTorch](https://github.com/IBM/terratorch).

<!-- **Chemistry and Materials:** take a look at new science foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted). -->

**(Coming soon.)** Materials, Health, and Time Series work groups.





<!--don't think we need this
The _Open Agent Lab_ builds with open weight models from our members, including **Llama, Granite, AI2, ServiceNow,** and more as well as other open source AI projects from the AI Alliance and community.


## Agent Projects

These projects are divided into three tables, one table for the _Open Agent Lab_, one table for projects related to [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) and a third table for the more general-purpose agent projects.

### Agent Lab Experimentation Platform

The _Open Agent Lab Platform_ is a project that provides a platform to support the work of our working groups and projects, as discussed [above](#open-agent-lab-description).

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
          <a href="https://the-ai-alliance.github.io/open-agent-lab/">Open Agent Lab</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-agent-lab">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/41/views/2">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-agent-lab/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/open-agent-lab/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The Open Agent Lab aims to provide cluster and software resources for R&D in AI agent technologies and demonstration applications for effective use of agents in real-world contexts. Hence, it promotes both the evolution of effective agent technologies and it provides educational resources for developers using agent technologies. The Lab supports many other initiatives and projects in the Alliance, as discussed below.
        </td>
      </tr>
    </tbody>
  </table>
</div>

-->

## Llama Stack and Llama Stack Agents

(Onboarding...) The [Llama Stack](https://github.com/meta-llama/llama-stack) project provides standardized APIs, component abstractions, integrations with other open source tools and managed services to help developers build and deploy AI applications and agents.

<div class="table-wrapper">
  <table>
    <thead>
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



## Model Context Protocol and Tooling Ecosystem
MCP from Anthropic is quickly becoming an industry standard for agentic tool-calling and data interactions. The AI Alliance is striving to advance this protocol and establish a robust set of tooling around it to enable broad, high value trusted use in production. Here is a start of that:

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
           A Model Context Protocol (MCP) Gateway. Serves as a central management point for tools, resources, and prompts that can be accessed by MCP-compatible LLM applications. Converts REST API endpoints to MCP, composes virtual MCP servers with added security and observability, and converts between protocols (stdio, SSE).  (Principal developer: <a href="https://ibm.com">IBM</a>)
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

## AI-Powered Programming Language for Agents

<div class="table-wrapper">
  <table>
    <thead>
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
      <!--
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
      -->
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

Safety, accuracy, red-teaming, security, compliance and more. Deployng a trusted AI system or agent is complex and the gap from prototype ot prodcution is still alrge for most people and organizations. The AI Alliance is supporting and creating a set ofproject and work groups aimed at ensuring agents in production deliver as advertised and can become a trusted foundation to build a business, educate students, perform scientific research, and much more.

<!-- above replaced the below
How do we know that applications built with AI are _trustworthy_, that they perform as required, in particular that they are _safe_, free of harmful outputs? Our [Evaluation and Safety](https://thealliance.ai/focus-areas/trust-and-safety) projects and initiatives address these concerns.

Trust actually has a broad interpretation. Increasingly, organizations moving from proofs of concept to production are not only concerned about evaluating their chosen models and applications for safety, but also for general _alignment_; do they actually perform well for the specific use cases implemented? This focus area is now exploring these areas of evaluation, in general terms and for specific domains.
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
          <a href="https://the-ai-alliance.github.io/trust-safety-evals/">AI Alliance Evaluation Hub</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
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
          The AI Alliance evaluation hub seeks to define the <em>global</em> taxonomy of evaluations (from safety to performance to efficacy), a catalog available of implementations of them, and provide a reference stack of industry-standard tools to run the evaluations. Our projects:
          <ul>
            <li>
              <strong>Taxonomy:</strong> <a href="https://the-ai-alliance.github.io/trust-safety-evals/taxonomy/taxonomy/">details</a>, <a href="https://github.com/orgs/The-AI-Alliance/projects/23/views/1?filterQuery=label%3Ataxonomy">current work</a>
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
      <!--
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
      -->
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ai-application-testing/">AI Application Testing for Developers</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
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
          If you are a software developer, you are accustomed to writing deterministic tests. What do you do when generative models aren't deterministic? This project adapts AI evaluation techniques for the "last mile" of evaluation; how do you verify that an AI application correctly implements its specific requirements and use cases, beyond the general concerns of common evaluation? This project also aims to educate developers on how to use these techniques effectively in combination with the traditional tools they already know.
        </td>
      </tr>
      <!-- --
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/red-teaming-work-group/">Red Teaming Work Group</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/red-teaming-work-group">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/37">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/red-teaming-work-group/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/red-teaming-work-group/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Red Teaming is a group activity that seeks to discover vulnerabilities in systems that could be exploited to make them behave in undesirable ways. Generative AI introduces new potential vulnerabilities, especially through prompts. The work of this group of experts consists of educational material and tools for doing red teaming work.
        </td>
      </tr>
      -->
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

# Open Trusted Data and Models

The [Open, Trusted Data and Models](https://thealliance.ai/focus-areas/foundation-models-datasets) focus area has projects to build a variety of multilingual, multimodal, and domain-specific models. Examples include models for molecular discovery, geospatial, and time series applications. This focus area is also cataloging, and in some cases building, datasets with clear license for use, backed by unambiguous provenance and governance controls, which are needed for model training, tuning, and other purposes.

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
      <!--
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/pdf-parsing-for-science/">Parsing PDFs to Build AI Datasets for Science</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/pdf-parsing-for-science">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/39">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/pdf-parsing-for-science/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/pdf-parsing-for-science/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          There is a need for domain-specific datasets for tuning special-purpose models and use in data-heavy application patterns like RAG. In many technical domains, much of the expertise is published in the open, but difficult to exploit as AI training data. For example, while text extraction from PDFs is already common, extracting information from the tables and images in technical PDFs, and associating that information with the surrounding text, is not yet widespread. This project aims to solve this problem by applying the recently-developed <a href="https://docling-project.github.io/docling/">Docling</a> tool to parse PDF datasets and create new datasets in formats that preserve this rich content, yet are easier to exploit in model training, tuning, etc. The project will start with the <a href="https://huggingface.co/datasets/PleIAs/Math-PDF">Math-PDF</a> dataset of PDFs published recently by <a href="https://pleias.fr/">PleIAs</a>. See also <em>Docling</em>, discussed next.
        </td>
      </tr>
      -->
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


<!-- regional chapters: start -->
# AI Alliance Regional Chapters

The AI Alliance is a global organization. However, localization matters and is key to representation. To ensure effectiveness, relevance, and impact across diverse markets and communities, regional chapters of the AI Alliance exist and more are planned:

* [Japan](https://the-ai-alliance.github.io/japan/)
* India - coming soon!
* Paris - coming soon!


<!-- events: start -->
## Events
Come meet us and learn about AI! See our [full list](https://thealliance.ai/events) of Alliance-sponsored and third-party AI events.


## Additional Information
* The [AI Alliance GitHub Organization](https://github.com/The-AI-Alliance/)
    * [Contributing](https://github.com/The-AI-Alliance/community/CONTRIBUTING.md) to the AI Alliance [community](https://github.com/The-AI-Alliance/community).
    * The [microsite template](https://github.com/The-AI-Alliance/microsite-template): The template used for Alliance projects, including all the websites listed above. See the [README-template.md](https://github.com/The-AI-Alliance/microsite-template/blob/main/README-template.md) for instructions.
* The [AI Alliance website](https://thealliance.ai): About the AI Alliance, our goals and initiatives.
    * Learn more about [getting involved](https://thealliance.ai/community).

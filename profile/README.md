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

The [Open Agent Lab](https://open-agent-lab.lovable.app) is a collaborative community of open source AI projects and domain-specific work groups that seek to make AI Agents successful in the real world through fast experimentation and distillation of learning into usable reference architectures and implementations, and build out of new tools to enable development and deployment.

## Agent Reference Application Hub

(In progress - coming soon!) The agent reference application hub is a repository of continually updated domain-specific implementations and architectural components for developing and deploying agents based on the output of our work groups, which include AI researchers, engineers, and subject matter experts from industry leading organizations. Here is some of our initial work:

**Industrial AI / Semiconductors:** check out [SemiKong](https://github.com/aitomatic/semikong) a foundation model for semiconductor process agents.

**Expert knowledge / Legal:** try [Bartlebot](https://github.com/The-AI-Alliance/bartlebot) if you want to work with case law and other legal topics.

**Finance:** see [Deep Research Agent for Finance](https://the-ai-alliance.github.io/deep-research-agent-for-finance/), a new collaboration between finance and AI experts in the Alliance to explore the practical challenges of building and running trustworthy, production-quality AI-based finance applications.

**Geospatial:** check out projects like [GeoBench](https://github.com/ServiceNow/geo-bench) and [TerraTorch](https://github.com/IBM/terratorch).

<!--
**Chemistry and Materials:** take a look at new science foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted).
-->

**(Coming soon.)** Materials, Health, and Time Series work groups.

<a id="model-context-protocol-section"></a>
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
          <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP in the Enterprise: A User Guide</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/enterprise-MCP">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/34">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/enterprise-MCP/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/enterprise-MCP/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
           MCP has enormous potential to accelerate AI adoption in enterprises. This "living" user guide features chapters written by experts on various aspects of deploying, managing, and using MCP successfully in enterprise settings. It contains the first several chapters with many more coming soon. (<a href="https://the-ai-alliance.github.io/enterprise-MCP/contributing/">Contributions are welcome!</a>.)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://ibm.github.io/mcp-context-forge/">Context Forge</a>
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
           Context Forge is an MCP gateway, which also supports <a href="https://a2a-protocol.org/latest/" target="a2a">A2A</a> and REST. It serves as a central management point for tools, resources, and prompts. It can be accessed by MCP-compatible LLM applications. It converts REST API endpoints to MCP, composes virtual MCP servers with added security and observability, and converts between protocols (e.g., stdio, SSE, etc.). (Principal developer: <a href="https://ibm.com">IBM</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-finance/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/42/views/1">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-finance/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-finance/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a> project demonstrates MCP in action for a common design pattern, <em>Deep Research Agent</em>. This example shows how a financial analyst can use a deep research agent to find, aggregate, and analyze information about a public company (or other potential investment). There are many other applications possible. The app is built on <a href="https://github.com/lastmile-ai/mcp-agent">MCP Agent</a>, developed by <a href="https://www.lastmileai.dev/">LastMile AI</a>, discussed next.
        </td>
      </tr>      <tr>
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
          Build effective agents using Model Context Protocol and simple to sophisticated workflow patterns. See the <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a>, discussed in the previous row, which is built with this toolkit. See the <a href="https://thealliance.ai/blog/building-a-deep-research-agent-using-mcp-agent">recent Alliance blog post</a> on their lessons learned developing the <em>orchestration</em> feature for deep research and related use cases. Highly informative! (Principal developer: <a href="https://www.lastmileai.dev/">LastMile AI</a>)
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

The <a href="https://nlip-project.org/">NLIP project</a> is facilitating the development of an open-source protocol for intelligent agents to communicate with each other and with humans using natural language. The <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP in the Enterprise: A User Guide</a>, discussed <a href="#model-context-protocol-section">above</a> has a chapter on NLIP.

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
              <a href="https://ecma-international.org/technical-committees/tc56/">TC-56</a> (Technical Committee 56)
            </li>
            <li>
              <a href="https://github.com/nlip-project">GitHub org</a>
            </li>
            <li>
              <a href="https://github.com/nlip-project/ecma_draft1">NC-56 NLIP draft</a>
            </li>
            <li>
              <a href="https://github.com/orgs/nlip-project/projects/3">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/nlip-project/documents">other documents</a>
            </li>
          </ul>
        </td>
        <td>
          The <a href="https://nlip-project.org/">NLIP project</a> is facilitating the development of an open-source protocol for intelligent agents to communicate with each other and with humans using natural language. NLIP is designed to perform the role of a meta-protocol that allows agents from other ecosystems to communicate with one another including interfaces with other protocols such as A2A, ACP, AGNTCY, MCP, NANDA, etc.
          <br/><br/>
          One outcome will be a new <a href="https://ecma-international.org/">ECMA</a> standard, <a href="https://ecma-international.org/technical-committees/tc56/">TC-56 NLIP, Natural Language Interaction Protocol</a> (<a href="https://github.com/nlip-project/ecma_draft1">draft</a>). The organization is also developing reference implementations of the protocol and end-points. See the <a href="https://github.com/nlip-project">GitHub organization</a> for details on these implementations.
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
          <a href="https://aitomatic.github.io/dana/">Dana — The Agent-Native Evolution of AI Development</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/aitomatic/dana" target="_blank">repo</a>
            </li>
            <li>
              <a href="https://github.com/aitomatic/dana/issues" target="_blank">issues</a>
            </li>
            <li>
              <a href="https://thealliance.ai/blog/the-ai-alliance-releases-new-ai-powered-programmin" target="_blank">blog post</a>
            </li>
            <!--
            <li>
              <a href="https://www.linkedin.com/posts/ctnguyen_aialliance-danalanguage-opendxa-activity-7344578841706708992-_c3X)" target="_blank">announcement</a>
            </li>
            <li>
              <a href="https://docs.google.com/forms/d/e/1FAIpQLSewvrs-L1XEabZWxljO8ogB4236HMNxzieQt6E4eXON8sPC_g/viewform?pli=1">Interest form</a>
            </li>
            -->
          </ul>
        </td>
        <td>
          <em>Dana</em> is based on the question, &ldquo;What if your agents could learn, adapt, and improve itself in production—without you?&rdquo;
          <br/><br/>
          Dana bridges the gap between AI coding assistance and autonomous agents through agent-native programming: native <code>agent</code>primitives, context-aware <code>reason()</code> calls that adapt output types automatically, self-improving pipelines with compositional <code>|</code> (&ldquo;pipe&rdquo;) operators, and functions that evolve through POET feedback loops (an automated prompt improvement technique). (Principal developer: <a href="https://aitomatic.com/">Aitomatic</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Agent Knowledge and Tool Foundations

See also the <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a>, which is discussed in the <a href="#model-context-protocol-section">MCP Ecosystem</a> section above.

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
          <a href="https://the-ai-alliance.github.io/semiont/">Semiont</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/semiont/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/34/views/2?filterQuery=repo%3A%22The-AI-Alliance%2Fsemiont%22">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/semiont/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/semiont/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Wiki-like knowledge base supporting graph retrieval, where humans and agents co-create Knowledge.  Includes MCP server.
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
          Document enrichment and knowledge structure (e.g., knowledge graph) extraction and resolution.
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
    </tbody>
  </table>
</div>


## Llama Stack and Llama Stack Agents

The [Llama Stack](https://github.com/meta-llama/llama-stack) project standardizes the core building blocks that simplify AI application development. It codifies best practices across the Llama ecosystem, integrates with other open-source tools and managed services, and provides APIs for inference, evaluation, agents, [MCP](#model-context-protocol-section), and deployment requirements like observability. It is designed to support both on-premise and cloud deployments. The ecosystem provides many example applications to help developers build and deploy AI applications quickly and effectively.

AI Alliance members are [contributing directly](https://thealliance.ai/blog/ai-alliance-accelerating-open-source-ai-innovation) to Llama Stack development, as well as building example applications that illustrate its use in various enterprise scenarios. The `llama-stack-examples` project has two initial example applications, described in the table below. The first  app is a simple getting-started chatbot that shows you the basics of creating an app with Llama Stack and how to run it. The second app (in development) is a _deep research_ application, a popular class of AI applications, which will demonstrate Llama Stack support for technologies like agents and [MCP](#model-context-protocol-section). Other examples under consideration will be chosen to cover other common application patterns seen in several industries. [Please join us!](https://events.thealliance.ai/llamastack)

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
          <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://llama-stack.readthedocs.io/en/latest/">documentation</a>
            </li>
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
          The <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> project itself.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/llamastack/llama-stack-client-python">Llama Stack Python Client</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/llamastack/llama-stack-client-python">repo</a>
            </li>
            <li>
              <a href="https://github.com/llamastack/llama-stack-client-python/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/llamastack/llama-stack-client-python/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The Python library used by client applications to communicate with <a href="https://github.com/llamastack/llama-stack-client-python">Llama Stack</a> services. See the Llama Stack <a href="https://llama-stack.readthedocs.io/en/latest/">documentation</a> for usage examples. There are also client libraries for other programming languages in the <a href="https://github.com/llamastack"><code>llamastack</code> GitHub organization</a>.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/llamastack/llama-stack-apps">Llama Stack Example Apps</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/llamastack/llama-stack-apps">repo</a>
            </li>
            <li>
              <a href="https://github.com/llamastack/llama-stack-apps/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          A growing suite of example applications for <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> that demonstrate how to build applications that use the RAG pattern and agents.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/The-AI-Alliance/llama-stack-examples">AI Alliance Llama Stack Example Apps</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-examples">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-examples/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/llama-stack-examples/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          A growing suite of example applications for <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> that demonstrate various stack features and common application patterns:
          <ol>
            <li>
              A getting-started chatbot app, which shows how to build and deploy Llama Stack applications. It includes two different UI options and inference with an <a href="https://ollama.com">ollama</a>-hosted <a href="https://www.llama.com/models/llama-3/">Llama 3</a> model.
            </li>
            <li>
              Jupyter Notebooks that demonstrate several APIs, like the new Responses API (<a href="https://developers.redhat.com/articles/2025/08/20/your-agent-your-rules-deep-dive-responses-api-llama-stack">blog post</a>).
            </li>
            <li>
              A <em>deep research</em> app (under development), which illustrates an emerging, common application pattern for AI. The user asks for detailed information about a topic, for example the market performance and financials for a publicly-traded company, agents find relevant data from diverse sources, and finally an LLM digests the information retrieved and prepares a report. This example will demonstrate Llama Stack support for agent-based application development, including the use of protocols like <a href="#model-context-protocol-section">MCP</a>.
            </li>
          </ol>
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/opendatahub-io/llama-stack-demos">Llama Stack Demos for OpenShift and Kubernetes</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/opendatahub-io/llama-stack-demos">repo</a>
            </li>
            <li>
              <a href="https://github.com/opendatahub-io/llama-stack-demos/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          A suite of examples for deploying and managing Llama Stack-based applications on OpenShift and Kubernetes. (Principal developer: <a href="https://redhat.com">Red Hat</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

# Governance, Evaluation, and Safety

Safety, accuracy, red-teaming, security, compliance, and more are required for successful AI applications. How do we know that AI applications are _trustworthy_, that they are _safe_, meaning free of harmful outputs, that they correctly implement the required behaviors? The following projects address these concerns.

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
          An introduction to trust and safety concepts from diverse experts, followed by recommendations for how to meet your application's needs. Start here if you are new to trust and safety, then leverage the projects discussed next to implement what you need.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/ai-application-testing/">Testing Generative AI Applications</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
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
          Are you an enterprise developer? How should you test AI applications? You know how to write <em>deterministic</em> tests for your "pre-AI" applications. What should you do when you add generative AI models, which aren't deterministic? This project adapts existing evaluation techniques for the "last mile" of AI evaluation; verifying that an AI application correctly implements its requirements and use cases, going beyond the general concerns of evaluation for safety, security, etc. We are building nontrivial, reusable examples and instructional materials, so you can use these techniques effectively in combination with the traditional tools you already know. This project is part of the <a href="https://thealliance.ai/core-projects/trust-and-safety-evaluations" target="tsei">Trust and Safety Evaluation Initiative</a> (TSEI). (It was previously called <em>Achieving Confidence in Enterprise AI Applications</em>.)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://servicenow.github.io/DoomArena/">DoomArena</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://arxiv.org/abs/2504.14064">paper</a>
            </li>
            <li>
              <a href="https://www.servicenow.com/blogs/2025/doomarena-security-testing-ai-agents">blog post</a>
            </li>
            <li>
              <a href="https://colab.research.google.com/github/ServiceNow/DoomArena/blob/main/notebooks/doomarena_intro_notebook.ipynb">colab</a>
            </li>
            <li>
              <a href="https://github.com/ServiceNow/DoomArena">repo</a>
            </li>
            <li>
              <a href="https://github.com/ServiceNow/DoomArena/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          <p>
            AI agents are becoming increasingly powerful and ubiquitous. They now interact with users, tools, web pages, and databases—each of which introduces potential attack vectors for malicious actors. As a result, the security of AI agents has become a critical concern. <a href="https://servicenow.github.io/DoomArena/">DoomArena</a> provides a modular, configurable framework that enables the simulation of realistic and evolving security threats against AI agents. It helps researchers and developers explore vulnerabilities, test defenses, and improve the security of AI systems. The DoomArena architecture comprises several key components that work together to create a flexible, powerful security testing environment for AI agents:
          </p>
          <p>
            <ul>
              <li><b>Attack Gateway:</b> Functions as a wrapper around original agentic environments (TauBench, BrowserGym, OSWorld), injecting malicious content into the user-agent-environment loop as the AI agent interacts with it.</li>
              <li><b>Threat Model:</b> Defines which components of the agentic framework are attackable and specifies targets for the attacker, enabling fine-grained security testing.</li>
              <li><b>Attack Config:</b> Specifies the AttackableComponent, the AttackChoice (drawn from a library of implemented attacks), and the SuccessFilter which evaluates attack success.</li>
            </ul>
          </p>
          <p>
            DoomArena offers several advanced capabilities that make it a powerful and flexible framework for security testing of AI agents:
          </p>
          <p>
            <ul>
              <li><b>Plug-in:</b> Plug into to your favorite agentic framework and environments τ-Bench, BrowserGym, OSWorld without requiring any modifications to their code.</li>
              <li><b>Customizable threat models:</b> Test agents against various threat models including malicious users and compromised environments.</li>
              <li><b>Generic Attacker Agents:</b> Develop and reuse attacker agents across multiple environments.</li>
              <li><b>Defense Evaluation:</b> Compare effectiveness of guardrail-based, LLM-powered, and security-by-design defenses.</li>
              <li><b>Composable Attacks:</b> Reuse and combine previously published attacks for comprehensive and fine-grained security testing.</li>
              <li><b>Trade-off Analysis:</b> Analyze the utility/security trade-off under various threat models.</li>
            </ul>
          </p>
        </td>
      </tr>      
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/trust-safety-evals/">Evaluation Is for Everyone</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
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
          <em>Evaluation Is for Everyone</em> addresses two problems: 1) many AI application builders don't know what they should do to ensure trust and safety, and 2) it should be as easy as possible to add trust and safety capabilities to AI applications. Many trust and safety evaluation suites are available that can be executed on the <a href="https://the-ai-alliance.github.io/eval-ref-stack">Evaluation Reference Stack</a>. We are making it as easy as possible for AI application developers to find and deploy the evaluations they need. See also the companion <a href="https://the-ai-alliance.github.io/ai-application-testing/">Testing Generative AI Applications</a> project. This project is part of the <a href="https://thealliance.ai/core-projects/trust-and-safety-evaluations" target="tsei">Trust and Safety Evaluation Initiative</a> (TSEI).
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/eval-ref-stack/">Evaluation Reference Stack</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/eval-ref-stack/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/23">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/eval-ref-stack/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/eval-ref-stack/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The companion projects <a href="https://the-ai-alliance.github.io/ai-application-testing/">Testing Generative AI Applications</a> and <a href="https://the-ai-alliance.github.io/trust-safety-evals/">Evaluation Is for Everyone</a> require a runtime stack that is flexible and easy to deploy and manage. This project is collating popular tools for writing and running evaluations into easy-to-consume packages. This project is part of the <a href="https://thealliance.ai/core-projects/trust-and-safety-evaluations" target="tsei">Trust and Safety Evaluation Initiative</a> (TSEI).
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
          See also the SYNTH Initiative in the next row!
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/SYNTH-initiative/">SYNTH Initiative</a> <img src="https://the-ai-alliance.github.io/assets/images/aia_symbol_main_color_24x24.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/SYNTH-initiative">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/44">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/SYNTH-initiative/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/SYNTH-initiative/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The SYNTH Initiative aims to address the critical gap in open-source AI development by creating a cutting-edge, open-source data corpus for training sovereign AI models and advanced AI agents. This involves curating permissively licensed, high-quality multimodal and multilingual datasets, with a focus on underrepresented languages, and generating synthetic data specifically designed to enhance frontier-level reasoning capabilities in these languages. The ultimate mission is to enable global access to advanced AI reasoning by fostering an inclusive data ecosystem that supports the full training pipeline of sophisticated models and agents. 
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
* [Thailand](https://the-ai-alliance.github.io/thailand/)
* India - coming soon!
* Paris - coming soon!

## Events
Come meet us and learn about AI! See our [full list](https://thealliance.ai/events) of Alliance-sponsored and third-party AI events.


## Additional Information
* The [AI Alliance GitHub Organization](https://github.com/The-AI-Alliance/)
    * Learn more about getting involved in our [community](https://thealliance.ai/community). In particular, see our [Contributing](https://github.com/The-AI-Alliance/community/CONTRIBUTING.md) guide.
    * The [microsite template](https://github.com/The-AI-Alliance/microsite-template): The template used for Alliance projects, including all the websites listed above. See the [README-template.md](https://github.com/The-AI-Alliance/microsite-template/blob/main/README-template.md) for instructions.
* The [AI Alliance website](https://thealliance.ai): About the AI Alliance, our goals and initiatives.

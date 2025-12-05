# The Open Agent Hub

> Collaborate, experiment, and build production-ready, open-source agents.

The [Open Agent Hub](https://the-ai-alliance.github.io/open-agent-hub/) is a collaborative community of open-source AI projects and domain-specific work groups that seek to make AI Agents successful in the real world through fast experimentation and distillation of learning into reusable reference architectures and enterprise-quality implementations.

Our focus on domain-specific projects helps surface and address the challenges faced in those domains, which often surface for other domains. Our work groups include engineers, AI researchers, and subject matter experts from industry-leading organizations. Here is some of our initial work:

**Industrial AI / Semiconductors:** See [SemiKong](https://github.com/aitomatic/semikong) a foundation model for semiconductor process agents.

**Expert knowledge / Legal:** Try [Bartlebot](https://github.com/The-AI-Alliance/bartlebot) if you want to work with case law and other legal topics.

**Finance:** See [Deep Research Agent for Finance](https://the-ai-alliance.github.io/deep-research-agent-for-finance/), a new collaboration between finance and AI experts in the Alliance to explore the practical challenges of building and running trustworthy, production-quality AI-based finance applications.

**Geospatial:** See projects like [GeoBench](https://github.com/ServiceNow/geo-bench) and [TerraTorch](https://github.com/IBM/terratorch).

**Chemistry and Materials:** See the new science foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted).

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
          <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP in the Enterprise: A User Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/><a href="#footnote-1"><sup>1</sup></a>
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
          <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          Build effective agents using Model Context Protocol and simple to sophisticated workflow patterns. See the <a href="https://the-ai-alliance.github.io/deep-research-agent-for-finance/">Deep Research Agent for Finance</a>, discussed in the previous row, which is built with this toolkit. See the <a href="https://thealliance.ai/blog/building-a-deep-research-agent-using-mcp-agent">recent Alliance blog post</a> on their lessons learned developing the <em>orchestration</em> feature for deep research and related use cases. Highly informative! (Principal developer: <a href="https://www.lastmileai.dev/">LastMile AI</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

<a id="footnote-1"></a>
<sup>1</sup> Indicates an Alliance <em>managed</em> project.

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
          <a href="https://the-ai-alliance.github.io/gofannon/">Gofannon</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://the-ai-alliance.github.io/semiont/">Semiont</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://the-ai-alliance.github.io/proscenium/">Proscenium</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://the-ai-alliance.github.io/lapidarist/">Lapidarist</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://github.com/The-AI-Alliance/AllyCat/">AllyCat</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://the-ai-alliance.github.io/bartlebot/">Bartlebot</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/bartlebot/">repo</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/bartlebot/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/bartlebot/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          Bartlebot is a demonstration of an AI Agent for the legal domain with a Slack integration. It is in early development.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/applying-ai-guide/">The Living Guide to Applying AI</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          The <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> project itself.<br/>
          See also the <a href="https://github.com/llamastack/llama-stack-client-python">Llama Stack Python Client</a>. 
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
          A growing suite of example applications for <a href="https://github.com/meta-llama/llama-stack">Llama Stack</a> that demonstrate how to build applications that use the RAG pattern and agents.<br/>
          See also the <a href="https://github.com/opendatahub-io/llama-stack-demos">Llama Stack Demos for OpenShift and Kubernetes</a>.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://github.com/The-AI-Alliance/llama-stack-examples">AI Alliance Llama Stack Example Apps</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          <a href="https://github.com/raghotham/cc-vec">CCVec - Common Crawl to Vector Stores</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/raghotham/cc-vec">repo</a>
            </li>
            <li>
              <a href="https://github.com/raghotham/cc-vec/issues">issues</a>
            </li>
          </ul>
        </td>
        <td>
          Search, analyze, and index Common Crawl data into vector stores for RAG applications, with three interfaces: CLI, Python library, and an MCP server. (Principal developers: <a href="https://commoncrawl.org/">Common Crawl Foundation</a> and <a href="https://meta.com">Meta</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://www.redhat.com/en/lightspeed">Red Hat Lightspeed</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/rhel-lightspeed">repo</a>
            </li>
            <li>
              <a href="https://docs.redhat.com/en/documentation/red_hat_lightspeed/1-latest">docs</a>
            </li>
          </ul>
        </td>
        <td>
          An end-to-end system management tool that predicts risks across Red Hat platforms, recommends actions, and tracks costs. Red Hat Lightspeed uses AI-powered package recommendations and planning capabilities to provide targeted guidance on increasing your systems’ day-to-day efficiency. (Principal developer: <a href="https://redhat.com">Red Hat</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

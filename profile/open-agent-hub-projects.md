# The Open Agent Hub Projects

> Collaborate, experiment, and build production-ready, open-source agents.

The [**Open Agent Hub**](https://the-ai-alliance.github.io/open-agent-hub/) is a collaborative community of open-source AI projects and domain-specific work groups that seek to make AI Agents successful in the real world through fast experimentation and distillation of learning into reusable reference patterns and example implementations.

Focusing on domain-specific projects surfaces unique challenges that often generalize to other domains, too. 

Our work groups include engineers, AI researchers, and subject matter experts from industry-leading organizations. Here is some of our work so far:

* **Industrial AI:** E.g., domain-specific models for **Semiconductor process agents** ([SemiKong](https://github.com/aitomatic/semikong) - [paper](https://arxiv.org/abs/2411.13802)) and **Marine Navigation** ([Llamarine](https://maritimetechnologyreview.com/2026/01/11/llamarine-ais-new-wave-for-smarter-maritime-navigation/) - [paper](https://arxiv.org/abs/2503.00203v3)).
* **Deep Research in Finance, Medical, etc.:** [Deep Research Agent for Applications](https://the-ai-alliance.github.io/deep-research-agent-for-applications/) implements the widely-applicable agent pattern, _deep research_, with example applications for finance, medicine, and [ArXiv](https://arxiv.org) exploration.
* **Expert Knowledge Graphs:** [Semiont](https://the-ai-alliance.github.io/semiont/), a Wiki-like knowledge base supporting graph retrieval, where humans and agents co-create Knowledge, and [Bartlebot](https://the-ai-alliance.github.io/bartlebot/), a demonstration AI Agent for the legal domain integrated with Slack. 
* **Geospatial:** [GeoBench](https://github.com/ServiceNow/geo-bench), an Earth observation benchmark for evaluating LLM performance on geospatial data, and [TerraTorch](https://github.com/IBM/terratorch), a Python toolkit for fine-tuning Geospatial Foundation Models (GFMs).
* **Chemistry and Materials:** Foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted).

We welcome your [feedback and help](https://github.com/The-AI-Alliance/community/blob/main/CONTRIBUTING.md), including suggestions for [new projects](https://events.thealliance.ai/aia-project) and [domain-specific use cases](https://qmmqo.share.hsforms.com/2qlmffVx9R8iVNad39JmDPg) of importance to you.

<a id="model-context-protocol-section"></a>
## Agent Ecosystems with MCP, A2A, and Related Projects

The [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) from [Anthropic](https://www.anthropic.com/) is quickly becoming an industry standard for communications between models, tool, and data repositories. A competing project with more emphasis on the unique requirements for agents is the [Agent2Agent](https://a2a-protocol.org/latest/) (A2A) protocol. The AI Alliance seeks to advance the application of these protocols and related tools to foster the development of robust distributed AI systems.

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
          <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP (and Beyond) in the Enterprise: A User Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/><a href="#footnote-1"><sup>1</sup></a>
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
           Model Context Protocol (MCP) has enormous potential to accelerate AI adoption in enterprises. Alternative protocols and complementary tools are also emerging rapidly. This "living" user guide features chapters written by experts on various aspects of deploying, managing, and using these tools successfully in enterprise settings. It contains the first several chapters with many more coming soon. (<a href="https://the-ai-alliance.github.io/enterprise-MCP/contributing/">Contributions are welcome!</a>)
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
           Context Forge is an AI application management suite, with support for protocols like MCP, A2A, REST, etc. It serves as a central management point for tools, resources, and prompts, as well as observability, security, and access control. (Principal developer: <a href="https://ibm.com">IBM</a>)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/deep-research-agent-for-applications/">Deep Research Agent for Applications</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-applications/">repo</a>
            </li>
            <li>
              <a href="https://github.com/orgs/The-AI-Alliance/projects/42/views/2?filterQuery=repo%3AThe-AI-Alliance%2Fdeep-research-agent-for-applications">dashboard</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-applications/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/deep-research-agent-for-applications/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          The <a href="https://the-ai-alliance.github.io/deep-research-agent-for-applications/">Deep Research Agent for Applications</a> demonstrates MCP in action for an important, common design pattern, <em>Deep Research Agents</em>. The first example application shows how a financial analyst can use a deep research agent to find, aggregate, and analyze information about a public company (or other potential investment). The second example explores recent medical research on diseases and pharmaceuticals. The third example supports finding and summarizing recent research papers posted to <a href="https://arxiv.org">ArXiv</a>. There are many other applications possible. The project is a collaboration of <a href="https://www.lastmileai.dev/">LastMile AI</a> and <a href="https://ibm.com">IBM</a>. It is based on LastMile's <a href="https://github.com/lastmile-ai/mcp-agent">MCP Agent</a>. See the <a href="https://www.aialliance.org/blog/building-a-deep-research-agent-using-mcp-agent">recent Alliance blog post</a> on LastMile's lessons learned developing the <em>orchestration</em> feature in MCP Agent for deep research and related use cases. Highly informative!
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://nlip-project.org/">NLIP Project</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://ecma-international.org/technical-committees/tc56/">ECMA TC-56</a>
            </li>
            <li>
              <a href="https://github.com/nlip-project">GitHub org</a>
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
          The <a href="https://nlip-project.org/">NLIP project</a> developed an open-source protocol for intelligent agents to communicate with each other and with humans using natural language. NLIP is designed to perform the role of a meta-protocol that allows agents from other ecosystems to communicate with one another including interfaces with other protocols such as A2A, ACP, AGNTCY, MCP, NANDA, etc. It is now an <a href="https://ecma-international.org/">ECMA</a> standard, <a href="https://ecma-international.org/technical-committees/tc56/">TC-56 NLIP, Natural Language Interaction Protocol</a>. The project is developing reference implementations of the protocol and end-points. The <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP (and Beyond) in the Enterprise: A User Guide</a>, discussed <a href="#model-context-protocol-section">above</a> has a chapter on NLIP.
        </td>
      </tr>
    </tbody>
  </table>
</div>

<a id="footnote-1"></a>
<sup>1</sup> The icon indicates an Alliance <em>core</em> project.

## Agent Development Tools

See also <a href="https://the-ai-alliance.github.io/deep-research-agent-for-applications/">Deep Research Agent for Applications</a>, discussed <a href="#model-context-protocol-section">above</a>.

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
          <a href="https://the-ai-alliance.github.io/ai-application-testing/">Testing Generative AI Agent Applications</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          Are you an enterprise developer? How should you test AI applications? You know how to write <em>deterministic</em> tests for your "pre-AI" applications. What should you do when you add generative AI models, which aren't deterministic? This project adapts existing evaluation techniques for the "last mile" of AI evaluation; verifying that an AI application correctly implements its requirements and use cases, going beyond the general concerns of evaluation for safety, security, etc. We are building nontrivial, reusable examples and instructional materials, so you can use these techniques effectively in combination with the traditional tools you already know. (This project is also discussed under the <a href="safety-governance-education-projects.md">AI Safety, Governance, and Education</a> projects.)
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          CUBE - Common Unified Benchmark Environment: <a href="https://github.com/The-AI-Alliance/cube-standard/"> Standard</a>, <a href="https://github.com/The-AI-Alliance/cube-harness/">Harness</a>, and <a href="https://github.com/The-AI-Alliance/cube-registry/">Registry</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li> Standard:
              <ul>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-standard/">repo</a>
                </li>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-standard/issues">issues</a>
                </li>
              </ul>
            </li>
            <li> Harness:
              <ul>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-harness/">repo</a>
                </li>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-harness/issues">issues</a>
                </li>
              </ul>
            </li>
            <li> Registry:
              <ul>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-registry/">repo</a>
                </li>
                <li>
                  <a href="https://github.com/The-AI-Alliance/cube-registry/issues">issues</a>
                </li>
              </ul>
            </li>
          </ul>
        </td>
        <td>
          <em>Common Unified Benchmark Environment</em> meets a common necessity, to standardize benchmark wrapping so the community can integrate otherwise-incompatible benchmarks uniformly and use them everywhere. The three projects include:
          <ul>
            <li>
              <a href="https://github.com/The-AI-Alliance/cube-standard/"> Standard</a>: The standards.
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/cube-harness/">Harness</a>: An open-source framework and research initiative for building and evaluating UI agents.
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/cube-registry/">Registry</a>: A community-maintained index of benchmarks that implement the CUBE standard. Any CUBE-compliant evaluation platform or training harness can discover and run registered benchmarks without custom integration.
            </li>
          </ul>
          (Principal developer: <a href="https://servicenow.com/">ServiceNow</a>)
        </td>
      </tr>
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
          <a href="https://aitomatic.github.io/dana/">Dana — The Agent-Native Evolution of AI Development</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/aitomatic/dana">repo</a>
            </li>
            <li>
              <a href="https://github.com/aitomatic/dana/issues">issues</a>
            </li>
            <li>
              <a href="https://www.aialliance.org/blog/the-ai-alliance-releases-new-ai-powered-programmin">blog post</a>
            </li>
          </ul>
        </td>
        <td>
          <em>Dana</em> is based on the question, &ldquo;What if your agents could learn, adapt, and improve itself in production—without you?&rdquo;
          <br/><br/>
          Dana bridges the gap between AI coding assistance and autonomous agents through agent-native programming: native <code>agent</code>primitives, context-aware <code>reason()</code> calls that adapt output types automatically, self-improving pipelines with compositional <code>|</code> (&ldquo;pipe&rdquo;) operators, and functions that evolve through POET feedback loops (an automated prompt improvement technique). (Principal developer: <a href="https://aitomatic.com/">Aitomatic</a>)
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
          <a href="https://cuga.dev">CUGA - Configurable Generalist Agent</a>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>
              <a href="https://github.com/cuga-project/cuga-agent/">repo</a>
            </li>
            <li>
              <a href="https://github.com/cuga-project/cuga-agent/issues">issues</a>
            </li>
            <li>
              <a href="https://github.com/cuga-project/cuga-agent/discussions">discussions</a>
            </li>
          </ul>
        </td>
        <td>
          CUGA is an open-source generalist agent framework from IBM Research, purpose-built for enterprise automation. Designed for developers, CUGA combines and improves the best of foundational agentic patterns such as ReAct, CodeAct, and Planner-Executor into a modular architecture enabling trustworthy, policy-aware, and composable automation across web interfaces, APIs, and custom enterprise systems.
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
          Tips from experts on using AI for various applications, including popular <i>design patterns</i>. (<a href="https://the-ai-alliance.github.io/applying-ai-guide/contributing/">Contributions are welcome!</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Knowledge Graphs for Agent Knowledge Bases

A set of projects for building _knowledge bases_ using _knowledge graphs_.

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
          Wiki-like knowledge base supporting graph retrieval, where humans and agents co-create Knowledge. Includes MCP an server. See also the companion projects, <a href="https://the-ai-alliance.github.io/proscenium/">Proscenium</a>, <a href="https://the-ai-alliance.github.io/lapidarist/">Lapidarist</a>, and <a href="https://the-ai-alliance.github.io/bartlebot/">Bartlebot</a>, next.
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
           Collaborative, asynchronous human/agent interactions.
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
    </tbody>
  </table>
</div>


## Llama Stack and Llama Stack Agents

The [Llama Stack](https://github.com/meta-llama/llama-stack) project standardizes the core building blocks that simplify AI application development. It codifies best practices across the Llama ecosystem, integrates with other open-source tools and managed services, and provides APIs for inference, evaluation, agents, [MCP](#model-context-protocol-section), and deployment requirements like observability. It is designed to support both on-premise and cloud deployments. The ecosystem provides many example applications to help developers build and deploy AI applications quickly and effectively.

AI Alliance members are contributing directly to Llama Stack development, as well as building example applications that illustrate its use in various enterprise scenarios. The `llama-stack-examples` project has two initial example applications, described in the table below. The first  app is a simple getting-started chatbot that shows you the basics of creating an app with Llama Stack and how to run it. The second app (in development) is a _deep research_ application, a popular class of AI applications, which will demonstrate Llama Stack support for technologies like agents and [MCP](#model-context-protocol-section). Other examples under consideration will be chosen to cover other common application patterns seen in several industries. [Please join us!](https://www.aialliance.org/join).

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

## Deployment and Scaling

Deploying and scaling AI systems is critical for cost-effective use of AI. There is the growing diversity of hardware accelerators for AI, not only for servers, but for edge devices, too. Developers want the ability to write AI applications that efficiently and transparently scale across different deployment scenarios, from PoCs and single-node deployments on development laptops and edge devices, up to large-scale clustered deployments supporting many users.

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
          <a href="https://the-ai-alliance.github.io/ai-accelerator-software-ecosystem-guide/">The AI Accelerator Software Ecosystem Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          A guide to the most common AI accelerators and the software stacks they use to integrate with tools you know, like PyTorch. (<a href="https://the-ai-alliance.github.io/ai-accelerator-software-ecosystem-guide/contributing/">Contributions are welcome!</a>)
        </td>
      </tr>
    </tbody>
  </table>
</div>

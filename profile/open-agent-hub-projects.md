# Projects for AI Agents and Applications

> Collaborate, experiment, and build production-ready, open-source agentic applications.

This page lists projects that provide core tools for building AI applications, including agentic applications. Some of these projects focus on specific domains. Going deep often surfaces challenges that apply more generally, too. See also the companion [Agents and Applications](https://the-ai-alliance.github.io/open-agent-hub/) website.

* **Industrial AI:** E.g., domain-specific models for **Semiconductor process agents** ([SemiKong](https://github.com/aitomatic/semikong) - [paper](https://arxiv.org/abs/2411.13802)) and **Marine Navigation** ([Llamarine](https://maritimetechnologyreview.com/2026/01/11/llamarine-ais-new-wave-for-smarter-maritime-navigation/) - [paper](https://arxiv.org/abs/2503.00203v3)).
* **Expert Knowledge Graphs:** [Semiont](https://the-ai-alliance.github.io/semiont/), a Wiki-like knowledge base supporting graph retrieval, where humans and agents co-create Knowledge.
* **Deep Research Agents for Finance, Medical, etc.:** [Deep Research Agent for Applications](https://the-ai-alliance.github.io/deep-research-agent-for-applications/) implements the widely-applicable agent pattern, _deep research_, with example applications for finance, medicine, and [ArXiv](https://arxiv.org) exploration.
* **Geospatial:** [GeoBench](https://github.com/ServiceNow/geo-bench), an Earth observation benchmark for evaluating LLM performance on geospatial data, and [TerraTorch](https://github.com/IBM/terratorch), a Python toolkit for fine-tuning Geospatial Foundation Models (GFMs).
* **Chemistry and Materials:** Foundation models for [molecular analysis](https://huggingface.co/ibm-research/materials.smi-ted).


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
          <a href="https://the-ai-alliance.github.io/semiont/">Semiont</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/><sup>1</sup>
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
          Wiki-like knowledge base supporting graph retrieval, where humans and agents co-create Knowledge. Includes MCP an server. See also the <a href="https://github.com/orgs/The-AI-Alliance/repositories?q=semiont">companion projects</a>, including support tools and synthetic, domain-specific, knowledge bases.
        </td>
      </tr>
    </tbody>
  </table>
</div>

<a id="footnote-1"></a>
<sup>1</sup> The icon indicates an Alliance <em>core</em> project.

## Agent Development Tools and Example Applications

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
          <a href="https://the-ai-alliance.github.io/ai-application-testing/">Testing Generative AI Applications</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
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
          Are you an enterprise developer? How should you test AI applications? You know how to write <em>deterministic</em> tests for your "pre-AI" applications. What should you do when you add generative AI models, which aren't deterministic? This project adapts existing evaluation techniques for the "last mile" of AI evaluation; verifying that an AI application correctly implements its requirements and use cases, going beyond the general concerns of evaluation for safety, security, etc. We are building nontrivial, reusable examples and instructional materials, so you can use these techniques effectively in combination with the traditional tools you already know. This project is also discussed under the <a href="safety-governance-education-projects.md">AI Safety, Governance, and Education</a> projects, where many of the same techniques apply.
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
    </tbody>
  </table>
</div>

### Notable AI Alliance Member Projects

The following notable, recommended projects are developed by Alliance members and affiliated organizations.

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
          CUGA is an open-source generalist agent framework, purpose-built for enterprise automation. Designed for developers, CUGA combines and improves the best of foundational agentic patterns such as ReAct, CodeAct, and Planner-Executor into a modular architecture enabling trustworthy, policy-aware, and composable automation across web interfaces, APIs, and custom enterprise systems. (Principal developer: <a href="https://research.ibm.com">IBM Research</a>)
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
              <a href="https://www.thealliance.ai/blog/the-ai-alliance-releases-new-ai-powered-programmin">blog post</a>
            </li>
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

### Legacy AI Alliance Projects

The following projects were created by the Alliance, but are not currently active. Most still welcome contributions in the form of pull requests. If you find them valuable, please help us restart work on them!

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
          The <a href="https://the-ai-alliance.github.io/deep-research-agent-for-applications/">Deep Research Agent for Applications</a> demonstrates MCP in action for an important, common design pattern, <em>Deep Research Agents</em>. The first example application shows how a financial analyst can use a deep research agent to find, aggregate, and analyze information about a public company (or other potential investment). The second example explores recent medical research on diseases and pharmaceuticals. The third example supports finding and summarizing recent research papers posted to <a href="https://arxiv.org">ArXiv</a>. There are many other applications possible. The project is a collaboration of <a href="https://www.lastmileai.dev/">LastMile AI</a> and <a href="https://ibm.com">IBM</a>. It is based on LastMile's <a href="https://github.com/lastmile-ai/mcp-agent">MCP Agent</a>. See the <a href="https://www.thealliance.ai/blog/building-a-deep-research-agent-using-mcp-agent">recent Alliance blog post</a> on LastMile's lessons learned developing the <em>orchestration</em> feature in MCP Agent for deep research and related use cases. Highly informative!
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          <a href="https://the-ai-alliance.github.io/enterprise-MCP/">MCP (and Beyond) in the Enterprise: A User Guide</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/><a href="#footnote-1"></a>
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
           Model Context Protocol (MCP) has enormous potential to accelerate AI adoption in enterprises. Alternative protocols and complementary tools are also emerging rapidly. This "living" user guide features chapters written by experts on various aspects of deploying, managing, and using these tools successfully in enterprise settings. It contains the first several chapters with many more coming soon. (<a href="https://the-ai-alliance.github.io/enterprise-MCP/contributing/">Contributions are welcome!</a>) The _Deep Research Agent for Applications_, discussed below, relies heavily on MCP for gathering information.
        </td>
      </tr>
      <tr>
        <td class="project-title" colspan="2">
          CUBE - Common Unified Benchmark Environment: <a href="https://github.com/The-AI-Alliance/cube-standard/">Standard</a>, <a href="https://github.com/The-AI-Alliance/cube-harness/">Harness</a>, and <a href="https://github.com/The-AI-Alliance/cube-registry/">Registry</a> <img src="https://the-ai-alliance.github.io/assets/images/favicon-16x16.png" alt="AI Alliance icon"/>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <li>Standard:
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
              <a href="https://github.com/The-AI-Alliance/cube-standard/">Standard</a>: The standards.
            </li>
            <li>
              <a href="https://github.com/The-AI-Alliance/cube-harness/">Harness</a>: An open-source framework and research initiative for building and evaluating AI agents.
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


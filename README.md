<div align="center">
  <a name="readme-top"></a>
  <!-- Using the horizontal logo -->
  <br/>
  <a href="https://axwise.de/" target="_blank"><h1>AxWise Flow 🚀</h1>

  <h2>Your AI Co-Pilot from Raw Idea to Actionable Plan</h2>
  <p>
    <strong>An API-first, open-core platform leveraging AI to transform raw ideas, user interviews, and feedback into validated, strategic product plans.</strong>
  </p>

  <p>
    <!-- Badges -->
    <a href="https://github.com/AxWise-GmbH/Flow/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache_2.0-blue.svg?style=flat-square" alt="License"></a>
    <a href="https://github.com/AxWise-GmbH/Flow"><img src="https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=flat-square" alt="Status: Active Development"></a>
    <a href="https://github.com/AxWise-GmbH/Flow/stargazers"><img src="https://img.shields.io/github/stars/AxWise-GmbH/Flow.svg?style=social&label=Star&maxAge=2592000" alt="GitHub stars"></a>
    <a href="https://github.com/AxWise-GmbH/Flow/issues"><img src="https://img.shields.io/github/issues/AxWise-GmbH/Flow?style=flat-square" alt="GitHub issues"></a>
    <!-- Add links to Docs/Release later -->
    <a href="[Link to API Docs - TODO]"><img src="https://img.shields.io/badge/API_Docs-Coming_Soon-orange?style=flat-square" alt="API Documentation"></a> 
  </p>
  <p>
    <strong>✨ Star this repo to follow our progress and support the open-source product development revolution! ✨</strong>
  </p>
  <p>
    <a href="https://axwise.de/join-waitlist?source=github" target="_blank" style="background-color: #4CAF50; color: white; padding: 12px 24px; text-align: center; text-decoration: none; display: inline-block; border-radius: 8px; font-size: 16px; font-weight: bold; margin-top: 10px;">
      ➡️ Join the Waitlist for SaaS & Updates! ⬅️
    </a>
  </p>
</div>
<br/>

## 🤔 What is AxWise Flow?

AxWise Flow is an **AI-powered, open-core platform** built with an **API-first design**. It guides innovators, startups, Product Managers, UX Researchers, and Product Designers through the entire product development lifecycle – **from a raw idea or user interview to a validated, actionable plan**. We help you mitigate the risk of building the wrong thing by integrating validation and strategic planning directly into your workflow.

Leveraging 14+ years of product development experience, AxWise Flow provides an **E2E workflow** with semi-automated guardrails to help you:

*   **Ingest & Process Data:** Handle various inputs, including interview transcripts (structured or raw text), user feedback, and initial ideas. Integration with partners like [Vexa.ai](https://github.com/Vexa-ai/vexa) enhances interview processing capabilities.
*   **Analyze & Synthesize:** Automatically extract rich, structured insights including themes (with definitions, keywords, codes, reliability), behavioral patterns (with evidence, impact), sentiment analysis (overall, statements), and pain points.
*   **Generate Personas:** Create detailed, data-driven user personas with evidence-backed traits and confidence scores.
*   **Prioritize & Plan:** Identify key insights ranked by potential impact and generate actionable outputs like user stories and strategic recommendations.
*   **Validate & Iterate:** Structure your validation process and refine your plans based on evidence.

The **core engine, LLM processing logic, prompts, and API** are functional and will be **open-source** (Apache 2.0). This allows enterprises, startups, and individuals to self-host, integrate via API, customize, and benefit from transparency, addressing common concerns with proprietary "black box" analysis tools. A premium SaaS offering will provide a seamless UI, managed infrastructure, and advanced features.

<div align="center">
  <h3>The AxWise Flow Process</h3>
  <img src="https://axwise.de/assets/updatedflow-CwaTTRJ3.svg" alt="AxWise Flow Process Diagram - Idea to Actionable Plan" width="90%">
  <p><em>A streamlined flow from input definition to actionable outputs.</em></p>
</div>

## ✨ Key Features (Implemented & Functional via API)

AxWise Flow already includes a powerful set of API-driven features:

*   ✅ **Rich Interview Analysis Engine:** Processes various interview formats (transcripts, Q&A, raw text) to extract deep, structured information.
*   ✅ **Enhanced Theme Extraction:** Identifies themes with definitions, keywords, codes, reliability scores, and sentiment distribution (See example schema below).
*   ✅ **Behavioral Pattern Recognition:** Detects workflows, coping strategies, habits, etc., complete with evidence, impact analysis, and suggested actions.
*   ✅ **Nuanced Sentiment Analysis:** Provides overall sentiment, category breakdown (positive/neutral/negative), and supporting statements.
*   ✅ **Evidence-Based Persona Generation:** Creates detailed personas with traits, confidence scores, and direct evidence links.
*   ✅ **Prioritized Insights Engine:** Ranks themes and patterns based on calculated impact scores (sentiment, frequency).
*   ✅ **Multi-LLM Support:** Easily switch between different Large Language Models (e.g., Gemini, OpenAI) via configuration.
*   ✅ **Analysis History:** Persists and retrieves past analysis results.
*   ✅ **User Management:** Integrated authentication via Clerk.
*   ✅ **API-First Design:** Core functionalities are accessible via a robust API for seamless integration.
*   ✅ **Interview Processing Partnership:** Integration with [Vexa.ai](https://github.com/Vexa-ai/vexa) for enhanced audio/video interview processing capabilities.

<!-- 2x2 Grid of Screenshots -->
<table align="center">
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="https://axwise.de/onepager-presentation/img/Screenshot%202025-04-28%20191354.png" alt="AxWise Flow - Identified Themes Screenshot" width="95%">
      <br/><em>Identified Themes with Definitions & Evidence</em>
    </td>
    <td align="center" valign="top" width="50%">
      <img src="https://axwise.de/onepager-presentation/img/Screenshot%202025-04-28%20194706.png" alt="AxWise Flow - Prioritized Insights Screenshot" width="95%">
      <br/><em>Prioritized Insights Ranked by Impact</em>
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <img src="https://axwise.de/onepager-presentation/img/Screenshot%202025-04-28%20193211.png" alt="AxWise Flow - User Personas Screenshot" width="95%">
      <br/><em>Generated User Personas with Traits</em>
    </td>
    <td align="center" valign="top" width="50%">
      <img src="https://axwise.de/onepager-presentation/img/Screenshot%202025-04-11%20121717.png" alt="AxWise Flow - Sentiment Analysis Screenshot" width="95%">
      <br/><em>Sentiment Analysis with Supporting Statements</em>
    </td>
  </tr>
</table>

### Example Output Snippet (Theme Schema)
```json
{
  "themes": [
    {
      "name": "Challenges in User Research Execution",
      "frequency": 0.25, // Prevalence score (0-1)
      "sentiment": -0.8, // Sentiment score (-1 to 1)
      "statements": [ // Direct supporting quotes
        "So there are many problems with research.",
        "I guess big problem is to convince stakeholder that we even need it.",
        // ... more statements
      ],
      "definition": "Practical difficulties encountered when planning and conducting user research...",
      "keywords": ["stakeholder buy-in", "finding users", "budget", ...],
      "codes": ["RESEARCH_CHALLENGES", "STAKEHOLDER_RESISTANCE", ...], // Categorization codes
      "reliability": 0.9, // Confidence in theme identification (0-1)
      "process": "enhanced", // Analysis process used
      "sentiment_distribution": { // Sentiment breakdown within this theme
        "positive": 0.1, "neutral": 0.2, "negative": 0.7
      }
    },
    // ... more themes
  ]
  // ... patterns, sentiment, personas, insights etc.
}
```

## 🚀 Getting Started

AxWise Flow's core functionalities are operational and accessible via its API. The full open-source core release and the SaaS UI are under active development.

**1. Explore the API (Coming Soon):**
*   We are preparing comprehensive API documentation. `[Link to API Docs - TODO]`
*   Interested in early API access or partnership? Contact us at [vitalijs@axwise.de](mailto:vitalijs@axwise.de)

**2. Prepare for Self-Hosting (Open Source Core - Coming Soon):**
The open-source core is designed for straightforward self-hosting. The setup will likely involve:
```shell
# 1. Clone the Repository (Link will be active upon release)
# git clone https://github.com/AxWise-GmbH/Flow.git
# cd Flow

# 2. Configure Environment (.env file: API keys, DB settings, LLM choice)
cp .env.example .env
# ... edit .env ...

# 3. Run using Docker (Example)
docker-compose up -d

# 4. Interact via API or integrate with your tools
```
*(**Note:** Detailed self-hosting instructions will accompany the open-source release.)*

**3. Stay Updated & Get Involved:**
*   **🌟 Star this Repository**: Follow our development progress!
*   **🔔 Join the Waitlist**: Be the first to know about the SaaS launch, open-source release, and major updates! 👉 **[https://axwise.de/join-waitlist?source=github](https://axwise.de/join-waitlist?source=github)**
*   **🐞 Report Issues:** Found a bug or have a suggestion for the API or core engine? Open an [Issue](https://github.com/AxWise-GmbH/Flow/issues).
*   **💬 Discuss:** Join the conversation in our [Discussions](https://github.com/AxWise-GmbH/Flow/discussions) tab (once enabled).

## ⚙️ Usage Example (Conceptual API Interaction)

```python
import requests
import json

# Replace with your self-hosted or future SaaS endpoint
API_BASE_URL = "http://localhost:8000" 
# Replace with your actual token or API key mechanism
AUTH_TOKEN = "YOUR_CLERK_JWT_OR_API_KEY" 

headers = {
    "Authorization": f"Bearer {AUTH_TOKEN}",
    "Content-Type": "application/json"
}

# 1. Upload Interview Data (Example: Raw Text)
# (Alternatively, use the /api/data endpoint for file uploads)
interview_text = """
User A: The new dashboard is great, much clearer than before.
User A: However, I still can't find the export settings easily. It took me 5 minutes yesterday.
User B: I agree, the main view is better, but finding specific options is a pain point.
"""

# 2. Trigger Analysis
analysis_payload = {
    # Provide data_id if previously uploaded, or potentially raw text directly (API design TBD)
    # "data_id": 123, 
    "text_data": interview_text, # Example: Sending raw text (Actual API might differ)
    "analysis_config": {
        "llm_provider": "gemini", # Or "openai"
        "tasks": ["themes", "patterns", "sentiment", "personas", "insights", "priority"] 
    }
}

# Assuming an endpoint like /api/analyze/text (Actual endpoint TBD)
analysis_response = requests.post(f"{API_BASE_URL}/api/analyze/text", headers=headers, json=analysis_payload)

if analysis_response.status_code == 200: # Or 202 if async
    analysis_result_id = analysis_response.json().get("result_id")
    print(f"Analysis started with Result ID: {analysis_result_id}")

    # 3. Poll for Results (Conceptual - actual endpoint TBD)
    # status_url = f"{API_BASE_URL}/api/results/{analysis_result_id}/status"
    # results_url = f"{API_BASE_URL}/api/results/{analysis_result_id}"
    # ... polling logic ...

    # 4. Fetch & Process Results (Conceptual)
    # results_response = requests.get(results_url, headers=headers)
    # if results_response.status_code == 200:
    #     final_results = results_response.json()
    #     print("Analysis Complete:")
    #     # Access themes, patterns, personas, insights...
    #     print(f"- Themes Found: {len(final_results.get('results', {}).get('themes', []))}")
    #     print(f"- Personas Generated: {len(final_results.get('results', {}).get('personas', []))}")
else:
    print(f"Error starting analysis: {analysis_response.status_code} - {analysis_response.text}")

```
*Note: This is a conceptual example. The final API structure and endpoints will be detailed in the official documentation.*

## 🌐 Open Source Core & SaaS Model

AxWise Flow operates on an **open-core model**:

*   **Open Source Core (Apache 2.0):** The fundamental analysis engine, workflow logic, LLM interactions, and API are functional and will be fully open-sourced. This allows for:
    *   **Self-Hosting:** Run the core on your own infrastructure for maximum data control and privacy.
    *   **Transparency:** Understand exactly how your data is processed. No black boxes.
    *   **Customization:** Adapt the core to your specific needs, integrate deeply with internal tools, and use any LLM you prefer.
    *   **Community:** Contribute to and benefit from community improvements and integrations.
*   **Premium SaaS:** A managed cloud offering providing:
    *   A user-friendly web interface for the E2E workflow (Coming Soon).
    *   Simplified setup, maintenance, and scaling.
    *   Advanced collaboration features.
    *   Potentially enhanced AI models or specialized features.

This hybrid approach provides flexibility for enterprises needing control and transparency, while offering convenience and advanced features through the SaaS platform.

## 🗺️ Roadmap

With the core API and analysis features implemented, our focus is on:

*   ⏳ **Full Open-Source Core Release:** Packaging, documenting, and releasing the core components for easy self-hosting and community contribution.
*   🎨 **SaaS UI Development:** Building the intuitive web interface for the E2E workflow.
*   🚀 **SaaS Platform Launch:** Making AxWise Flow accessible as a managed service via [axwise.de](https://axwise.de/).
*   🧩 **Integrations:** Connecting with popular tools (Jira, Figma, Miro, etc.).
*   🔌 **Plugin Architecture:** Enabling community extensions and custom workflow steps.
*   📈 **Enhanced AI:** Continuously improving analysis quality (e.g., user story generation, strategic recommendations) and adding more AI-driven guidance.
*   👥 **Community Building:** Fostering an active developer and user community around the open-source project.

## 🤝 Contributing

We welcome contributions! Whether it's improving the core engine, adding LLM support, enhancing documentation, reporting bugs, or suggesting features, your input is valuable.

Once the core repository structure is finalized for open-source release, we will provide a detailed `CONTRIBUTING.md` guide. We plan to use a **Contributor License Agreement (CLA)**.

## 📝 License

The open-source core of AxWise Flow is licensed under the **Apache License 2.0**.

This permissive license allows broad use, modification, and distribution, making it suitable for both individual and enterprise use, including building commercial applications on top of the open-source core.

See the [LICENSE](LICENSE) file for the full text.

---

<div align="center">
  <img src="https://axwise.de/logo-horizontal.svg" alt="AxWise Logo" height="40" style="vertical-align: middle; margin-right: 10px;"/>
  <br/>
  📬 **AxWise Flow – Building the Future of Validated Innovation, Together.**
  <br/><br/>
  **Get Involved!** <br/>
  <a href="https://github.com/AxWise-GmbH/Flow/stargazers">⭐ Star this repo!</a> | 
  <a href="https://axwise.de/join-waitlist?source=github">🔔 Join the Waitlist</a> |
  <a href="https://axwise.de/">🌐 Visit AxWise.de</a> |
  <a href="https://github.com/AxWise-GmbH/Flow/issues">🐞 Report an Issue</a>
</div>

<!-- Link Definitions -->
[axwise-website-link]: https://axwise.de/
[axwise-waitlist-link]: https://axwise.de/join-waitlist?source=github-bottom
[github-repo-link]: https://github.com/AxWise-GmbH/Flow
[license-link]: https://github.com/AxWise-GmbH/Flow/blob/main/LICENSE
[github-stars-link]: https://github.com/AxWise-GmbH/Flow/stargazers
[github-issues-link]: https://github.com/AxWise-GmbH/Flow/issues

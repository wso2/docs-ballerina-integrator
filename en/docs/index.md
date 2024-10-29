# WSO2 Kola Documentation

WSO2 Kola is a comprehensive integration solution that simplifies your digital transformation journey.

The Kola extension for Visual Studio Code (Kola for VS Code) enables developers to utilize the popular Visual Studio Code editor for integration development, enhancing the overall experience. This AI-assisted development environment offers a faster, customizable, and more intuitive experience, boosting productivity in integration development.
Kola provides a range of features that streamline coding tasks, enhance code quality, and reduce time spent on error-prone processes. By leveraging AI capabilities, Kola empowers developers to focus on high-value tasks, accelerating digital transformation efforts.

### AI-assisted development  
Kola empowers developers by using AI to streamline coding tasks, enhance code quality, and reduce time spent on error-prone processes. Here’s how Kola’s AI capabilities make a difference:

- Code Suggestions and Autocompletion: The AI in Kola for VS Code provides context-aware suggestions, helping developers complete lines of code or entire blocks accurately. These real-time prompts assist in selecting the best methods, properties, or configurations, which can significantly speed up the coding process.
- Error Detection and Fix Recommendations: AI continuously analyzes the code as it's written, flagging potential errors or inconsistencies and suggesting fixes. This proactive error handling helps prevent bugs and enhances code quality, enabling developers to correct issues early, reducing the need for extensive debugging.
- Pattern Recognition and Code Optimization: By recognizing patterns in the code, Kola’s AI suggests optimizations, streamlining performance or even recommending best practices. This can be particularly useful for new developers or teams looking to standardize code across projects.
- Natural Language Code Search and Commands: Kola’s AI allows developers to use natural language to search for code snippets, methods, or libraries, reducing the time spent manually browsing documentation or previous code. This also enables quicker onboarding, as developers can intuitively ask questions or search within the IDE.
- Smart Refactoring and Code Restructuring: As applications evolve, restructuring code becomes critical. Kola’s AI offers intelligent refactoring options, enabling developers to restructure code confidently without breaking functionality. This minimizes technical debt and makes the codebase cleaner and more maintainable.

Together, these AI-driven features in Kola for VS Code create a more efficient, accurate, and productive development experience, reducing the learning curve and enabling developers to focus on high-value tasks rather than repetitive or error-prone coding tasks.

### Low-code integration development
Kola provides a streamlined, user-friendly environment for building integrations with minimal coding, opening up integration tasks to both experienced developers and those new to coding. Here’s how Kola’s low-code capabilities simplify the integration development process:

- Visual Designer Interface: Kola includes visual tools that let developers create integration workflows by simply dragging and dropping pre-built components. This visual builder reduces the need for manual coding, allowing users to connect systems and data sources without extensive syntax knowledge.
- Pre-Built Connectors and Templates: With an extensive library of connectors and templates, Kola enables users to quickly incorporate common integration patterns and connect to popular systems like databases, cloud services, and enterprise applications. This eliminates repetitive setup work and accelerates development.
- Parameterized Configurations: Kola’s low-code environment supports easy configuration of workflows using parameters, making it possible to adjust integrations without coding. This flexibility simplifies the process of tailoring integrations to specific use cases while maintaining consistency.
- AI-Powered Recommendations for Components: Kola leverages AI to suggest components, mappings, and configurations based on the current workflow context. This feature helps guide developers through building integrations efficiently, even if they’re not deeply familiar with the underlying code.
- Testing and Deployment Automation: The low-code environment integrates testing and deployment tools that enable users to validate integrations quickly and push them to production with minimal manual intervention. Automated testing helps ensure that workflows function as intended, while deployment tools streamline the release process.
- Collaboration-Friendly Design: Low-code tools in Kola for VS Code promote collaboration between developers and business teams by allowing users with different technical backgrounds to contribute to integration projects. This inclusive approach helps bridge the gap between technical and non-technical team members.
By offering these low-code features, Kola for VS Code makes integration development accessible, faster, and more flexible. It enables teams to focus on delivering value through integration rather than getting bogged down in complex coding tasks, ultimately accelerating digital transformation efforts.

- Visual design: Kola for VS Code provides a visual design experience that simplifies integration development.

### Leverage the Power of Ballerina
Kola to take advantage of a language purpose-built for integration development, allowing developers to handle cloud-native, API-driven integrations with simplicity and efficiency. [Ballerina](https://ballerina.io), the foundation of Kola, empowers developers with:

- Integration-Centric Syntax: Ballerina’s syntax is intuitive for integration, reducing the need for boilerplate code and allowing developers to write integration logic clearly and concisely. Its language constructs, like workers, channels, and error handling, are specifically designed for scenarios like API orchestration and data transformation.
- Cloud-Native and API-First Design: Ballerina is cloud-native by design, meaning that it includes built-in support for modern protocols like HTTP, WebSocket, gRPC, and Kafka, essential for microservices and cloud-based architectures. This enables developers to connect and interact with various APIs, making it ideal for the API-first strategies prevalent in modern enterprises.
- Visual Flow Representation: Ballerina’s unique graphical representation allows developers to visualize integrations as they code, bridging the gap between code and design. This approach provides a flow-based overview of data movement and logic, which is invaluable for understanding complex workflows.
- In-Built Observability and Resilience: Ballerina includes observability features, enabling developers to monitor integrations out of the box. This includes support for distributed tracing, metrics, and logging, essential for maintaining and debugging integrations in a distributed environment.
- Unified Data Handling and Transformations: Ballerina simplifies data handling with straightforward syntax for defining data transformations and mappings, essential in integration workflows where data is frequently transformed between systems. This reduces complexity when integrating heterogeneous data sources.
- Built-in Testing and Deployment Tools: Ballerina supports testing and deployment automation, making it easy to validate and deploy integrations in cloud environments. By leveraging these tools, developers can ensure reliability and scalability for integrations, even as they deploy them across diverse infrastructures.
Integrating Kola with Ballerina brings the best of both worlds: a developer-friendly environment with powerful language features designed to make integration projects easier, faster, and more robust.

{% raw %}
<style>
.md-sidebar.md-sidebar--primary {
    display: none;
}
.md-sidebar.md-sidebar--secondary{
    display: none;
}
.section02 {
    display: flex;
    justify-content: space-between;
}

[//]: # (header.md-header .md-header__button:not([hidden]) {)
[//]: # (    display: none;)
[//]: # (})

.about-home {
    display: flex;
}
.about-home div:first-child {
    width: 50%;
    padding-top: 20px;
}
.about-home div:nth-child(2) {
    width: 50%;
}
@media screen and (max-width: 76.1875em) {
    .md-sidebar.md-sidebar--primary {
        display: block;
    }
}
@media screen and (max-width: 945px) {
    .about-home div:first-child {
        width: 100%;
    }
    .about-home div:nth-child(2) {
        width: 100%;
    }
    .about-home {
        flex-direction: column;
    }
    .md-typeset a {
        background-position-x: left;
    }
    .download-btn-wrapper {
        display: block;
        text-align: center;
    }
}
.md-typeset h1{
    visibility: hidden;
    margin-bottom: 0;
}
.md-search-result__article.md-typeset h1{
    visibility: visible;
}
</style>
{% endraw %}
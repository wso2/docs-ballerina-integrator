<div class="homePage">
    <div class="section01">
        <div class="leftContent">
            <div class="about-home">
                <div>
                    <b>Kola</b> is a comprehensive integration solution that simplifies your digital transformation journey. The Kola extension for Visual Studio Code (Kola for VS Code) enables developers to utilize the popular Visual Studio Code editor for integration development, enhancing the overall experience. This AI-assisted development environment offers a faster, customizable, and more intuitive experience, boosting productivity in integration development.
                    Kola provides a range of features that streamline coding tasks, enhance code quality, and reduce time spent on error-prone processes. By leveraging AI capabilities, Kola empowers developers to focus on high-value tasks, accelerating digital transformation efforts.
                    <div class="linkSet2" onclick="location.href='{{base_path}}/get-started/quick-start-guide';">
                        <a href="get-started/quick-start-guide"><h3>Quick Start Guide</h3></a>
                        <p>
                            Get started with Kola by running a simple integration use case in your local environment.
                        </p>
                    </div>
                </div>
                <div  style="text-align:right">
                    <a href="{{base_path}}/assets/img/introduction/kola.png"><img src="{{base_path}}/assets/img/introduction/kola.png" alt="Kola" width="95%"></a>
                </div>
            </div>
        </div>
    </div>
    <div class="section02">
        <div class="leftContent">
                <div class="about-home">
                    <div>
                        <h3>Low-code integration development</h3>
                        <p>
                            Kola provides a streamlined, user-friendly environment for building integrations with minimal coding, opening up integration tasks to both experienced developers and those new to coding. Here’s how Kola’s low-code capabilities simplify the integration development process:
                        </p>
                        <ul>
                            <li><b>Design Visually:</b> Kola’s interface allows users to visually design integrations, making it easy to create and manage integration flows.</li>
                            <li><b>Pre-built connectors:</b> Kola offers a range of pre-built connectors that simplify the process of connecting to various systems and services.</li>
                            <li><b>Reuse components:</b> Kola enables users to create reusable components that can be shared across multiple integrations, reducing development time and effort.</li>
                            <li><b>Automate testing:</b> Kola provides automated testing capabilities that help users identify and resolve issues early in the development process.</li>
                            <li><b>AI-assisted development:</b> Kola’s AI capabilities provide intelligent suggestions and recommendations that help users write code more efficiently and accurately.</li>
                        </ul>
                    </div>
                    <div  style="text-align:right">
                        <a href="{{base_path}}/assets/img/introduction/low-code.gif"><img src="{{base_path}}/assets/img/introduction/low-code.gif" alt="low-code" width="90%" style="padding-top: 60px" ></a>
                    </div>
                </div>
        </div>
    </div>
     <div class="section02">
        <div class="rightContent">
                <div class="about-home">
                    <div  style="text-align:left">
                        <a href="{{base_path}}/assets/img/introduction/ai.gif"><img src="{{base_path}}/assets/img/introduction/ai.gif" alt="AI" width="90%" style="padding-top: 60px; padding-right: 50px" ></a>
                    </div>
                    <div>
                        <h3>AI-assisted development</h3>
                        <p>
                            Kola empowers developers by using AI to streamline coding tasks, enhance code quality, and reduce time spent on error-prone processes. Here’s how Kola’s AI capabilities make a difference:
                        </p>
                        <ul>
                            <li><b>Code Suggestions and Autocompletion:</b> Kola’s AI offers context-aware suggestions, helping developers complete code faster and accurately with real-time prompts for methods, properties, or configurations.</li>
                            <li><b>Error Detection and Fix Recommendations:</b> AI actively detects errors and suggests fixes, preventing bugs early and improving code quality, reducing extensive debugging needs.</li>
                            <li><b>Pattern Recognition and Code Optimization:</b> Kola’s AI identifies code patterns and suggests optimizations, improving performance and helping standardize code across teams.</li>
                            <li><b>Natural Language Code Search and Commands:</b> Developers can use natural language to search for code snippets or methods, reducing time spent on documentation and speeding up onboarding.</li>
                            <li><b>Smart Refactoring and Code Restructuring:</b> Kola’s AI offers refactoring options, enabling confident code restructuring for a cleaner, maintainable codebase.</li>
                        </ul>
                    </div>
                </div>
        </div>
    </div>
    <div class="section02">
        <div class="leftContent">
                <div class="about-home">
                    <div>
                        <h3>Leverage the Power of Ballerina</h3>
                        <p>
                            Kola to take advantage of a language purpose-built for integration development, allowing developers to handle cloud-native, API-driven integrations with simplicity and efficiency. <a href="https://ballerina.io">Ballerina</a>, the foundation of Kola, empowers developers with:
                        </p>
                        <ul>
                            <li><b>Integration-Centric Syntax:</b> Ballerina’s syntax is designed for integration, minimizing boilerplate and enabling clear, concise logic with constructs like workers, channels, and error handling for API orchestration and data transformation.</li>
                            <li><b>Cloud-Native and API-First Design:</b> Ballerina supports cloud protocols like HTTP, WebSocket, gRPC, and Kafka, enabling seamless API interactions for microservices and API-first strategies.</li>
                            <li><b>Visual Flow Representation:</b> Ballerina’s graphical view lets developers visualize integrations, offering an overview of data flow and logic essential for complex workflows.</li>
                            <li><b>In-Built Observability and Resilience:</b> Ballerina includes observability features, with distributed tracing, metrics, and logging for effective monitoring and debugging.</li>
                            <li><b>Unified Data Handling and Transformations:</b> Ballerina simplifies data handling with easy syntax for data transformations, reducing complexity in diverse data integrations.</li>
                            <li><b>Built-In Testing and Deployment Tools:</b> Ballerina includes tools for testing and deployment, ensuring scalable, reliable integrations in cloud environments.</li>
                        </ul>
                    </div>
                    <div  style="text-align:right">
                        <a href="{{base_path}}/assets/img/introduction/ballerina.png"><img src="{{base_path}}/assets/img/introduction/ballerina.png" alt="ballerina" width="80%" style="padding-top: 250px" ></a>
                    </div>
                </div>
        </div>
    </div>
</div>
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
header.md-header .md-header__button:not([hidden]) {
    /* display: none; */
}
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
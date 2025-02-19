# License
- The license for IBM watsonx Code Assistant can be found in the [product-licenses](./product-licenses/) folder in this repository.

- You can use this repository to add issues for watsonx Code Assistant. The license for issues, discussion, and any files or samples shared in issues can be found in the [LICENSE](./LICENSE) file.

# IBM® watsonx™ Code Assistant

IBM® watsonx™ Code Assistant is an innovative, generative AI coding companion that offers robust, contextually aware assistance for popular programming languages including Go, C, C++, Java, JavaScript, Python, TypeScript, and more. Seamlessly integrated into your IDE, you can accelerate your productivity and simplify coding tasks, all with trust, security, and compliance.

## Features

### Get code suggestions

**Use chat conversations**: Use natural language prompts to generate code suggestions. Use a chat conversation to enter a prompt that explains the code you need, and watsonx Code Assistant generates something you can choose to use. 

<img src="https://github.com/ibm/watsonx-code-assistant/raw/HEAD/images/code-interaction.png" alt="Use a chat conversation in IBM watsonx Code Assistant">

**Reference code**: To ask questions or refine a specific file, class, function, or method in your workspace, you can use a code reference. These references provide important context and can help to increase the accuracy of the answer. As part of your chat message, type the @ symbol to see a list of files, classes, and methods from your workspace. Click to select the reference, and watsonx Code Assistant sends the contents of the reference as part of your message.

<img src="https://github.com/ibm/watsonx-code-assistant/raw/HEAD/images/reference.gif" alt="Reference code in IBM watsonx Code Assistant">

**Code completion**: Or, complete code in the editor. Start typing a line of code, then pause. IBM watsonx Code Assistant adds a code suggestion to complete the line that you typed. 

<img src="https://github.com/ibm/watsonx-code-assistant/raw/HEAD/images/Single-line.gif" height=200 alt="Single-line completion in IBM watsonx Code Assistant">

You can also get a multiline code suggestion. Start typing a line of code, then use a keyboard shortcut, and watsonx Code Assistant adds a multiline code suggestion.

<img src="https://github.com/ibm/watsonx-code-assistant/raw/HEAD/images/Multi-line.gif" height=350 alt="Multi-line completion in IBM watsonx Code Assistant">

Or, enter a comment that describes the code you want. 

<img src="https://github.com/ibm/watsonx-code-assistant/raw/HEAD/images/comment-to-code.gif" height=200 alt="Comment to code generation in IBM watsonx Code Assistant">

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-generate-code" target="_blank">Getting code suggestions</a>.

### Explain code

Use generative AI to analyze and summarize your code to understand what the code does. Click the **Explain** option that precedes a code block or enter `/explain` in a chat conversation. IBM watsonx Code Assistant analyzes the code and provides a detailed explanation of what the code does.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-explain" target="_blank">Explaining code</a>.

### Document code

Generate comment lines that document what your code does. Click the **Document** option that precedes a code block or enter `/document` in a chat conversation. IBM watsonx Code Assistant analyzes the code and adds comments that document what the code does.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-generate-doc" target="_blank">Documenting code</a>. 

### Generate unit tests

Create unit tests to evaluate your code functions. Click the **Unit Test** option that precedes a code block or enter `/unit-test` in a chat conversation. IBM watsonx Code Assistant analyzes the code and creates a unit test.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-generate-test" target="_blank">Generating unit tests</a>. 

### Translate code from one language to another

Use watsonx Code Assistant to translate code. In a chat conversation, use the syntax `translate [from <source language >] to <target_language> <code reference>`

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-translate-code" target="_blank">Translating code from one language to another</a>. 


# IBM® watsonx™ Code Assistant for Enterprise Java Applications

For use with the Standard plan, IBM® watsonx™ Code Assistant for Enterprise Java Applications adds features for Java application upgrades and modernization, and enhanced code explanation and unit test generation.

## Features

### **Java runtime modernization**

Analyze your Java application runtime and modernize it to a more lightweight, flexible, and efficient runtime. Receive a prescriptive plan that describes the changes that are needed to modernize your application, with a detailed assessment of complexity and required development effort. Use automation to quickly implement code and configuration changes. Transform code with generative Al assistance to resolve more complex issues.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-modernize-java" target="_blank">Modernizing Java applications</a>.

### **Java version upgrade**

Identify changes required to upgrade Java code, automatically apply fixes, and use generative AI to transform Java code. Receive a prescriptive plan that describes the changes that are needed to upgrade your application, with a detailed assessment of complexity and required development effort. Use automation to quickly implement code and configuration changes. Transform code with generative Al assistance to resolve more complex issues.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-upgrade-java" target="_blank">Upgrading the Java version for your application</a>.

### **Explain code and applications**

Understand complex code structures by using generative AI to summarize your application's key functions, services, and dependencies.

With the Standard plan, get enhanced code explanations. Use generative AI to analyze and summarize your code to understand what the code does. Click the **Explain** option that precedes a code block or enter `/explain` in a chat conversation. IBM watsonx Code Assistant analyzes the code and provides a detailed explanation of what the code does.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-explain" target="_blank">Explaining code</a>.

### **Generate unit tests**

Use generative AI to create tests that help maintain critical application functions.

With the Standard plan, create enhanced unit tests to evaluate your code functions. Click the **Unit Test** option that precedes a code block or enter `/unit-test` in a chat conversation. IBM watsonx Code Assistant analyzes the code and creates a unit test.

For more information, see the documentation for <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-wca-generate-test" target="_blank">Generating unit tests</a>. 

# Setup

Provision a watsonx Code Assistant service instance on IBM Cloud for your organization to get the best performance and the full set of features. Or for individuals, you can use watsonx Code Assistant Individual to access a local IBM Granite model. 

## Use a watsonx Code Assistant service instance on IBM Cloud

To set up on IBM Cloud:

1. Explore the <a href="https://www.ibm.com/products/watsonx-code-assistant/pricing" target="_blank">pricing plans</a>.
1. Use the <a href="https://cloud.ibm.com/catalog/services/ibm-watsonx-code-assistant" target="_blank">IBM Cloud catalog</a> to provision a service instance of watsonx Code Assistant.
1. When you finish provisioning your instance, click **Setup** to open an onboarding checklist page to help you with configuration.
1. Have your developers create an IBM Cloud API Key.
1. Have your developers install the Visual Studio Code extension or Eclipse IDE plug-in for watsonx Code Assistant.
   
For more information, see the documentation for: 
- <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-cloud-setup-wca" target="_blank">Setting up your watsonx Code Assistant service in IBM Cloud</a>
- <a href="https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-cloud-setup-wca-extensions" target="_blank">Installing the IDE extension or plug-in</a>

## Use watsonx Code Assistant Individual with a local IBM Granite model

Free for individual use on a personal laptop, use IBM watsonx Code Assistant Individual to access a local model through <a href="https://ollama.com" target="_blank">Ollama</a>, which is a widely-used local inferencing engine for LLMs. Ollama wraps the underlying model-serving project <a href="https://github.com/ggml-org/llama.cpp" target="_blank">llama.cpp</a>.

### Install the IBM watsonx Code Assistant Visual Studio Code extension

This setup is not available for the Eclipse IDE plug-in. It is only available with the Visual Studio Code extension.

1. Open the <a href="https://marketplace.visualstudio.com/items?itemName=IBM.wca-core&ssr=false#overview" target="_blank">watsonx Code Assistant</a> extension page in the Visual Studio Marketplace.
1. Click Install on the Marketplace page.
1. In Visual Studio Code, click Install on the extension.
1. In the extension settings, set **Wca: Backend Provider** to **ollama**.

### Install Ollama

- MacOS, Linux, Windows: Download and run the <a href="https://ollama.com/download" target="_blank">ollama installer</a>
- On MacOS, you can also use <a href="https://brew.sh/" target="_blank">homebrew</a> to install Ollama:

  ```shell
  brew install ollama
  ```

### Start the Ollama inference server

In a console window, run:

```shell
ollama serve
```

Leave that window open while you use Ollama.

If you receive the message `Error: listen tcp 127.0.0.1:11434: bind: address already in use`, the Ollama server is already started.

### Install the IBM Granite code model

Get started with IBM watsonx Code Assistant by installing the `granite-code:8b` model available in the <a href="https://ollama.com/library/granite-code" target="_blank">Ollama library</a>.

1. Open a new console window.
2. On the command line, type `ollama run granite-code:8b` to download and deploy the model. You see output similar to the following example:

   ```shell
   pulling manifest 
   pulling 8718ec280572... 100% ▕███████████████████████ 4.6 GB
   pulling e50df8490144... 100% ▕███████████████████████ ▏  123 B
   pulling 58d1e17ffe51... 100% ▕███████████████████████▏  11 KB
   pulling 9893bb2c2917... 100% ▕███████████████████████▏  108 B
   pulling 0e851433eda0... 100% ▕███████████████████████▏  485 B
   verifying sha256 digest 
   writing manifest 
   removing any unused layers 
   success 
   >>> 
   ```

3. Type `/bye` after the `>>>`to exit the Ollama command shell.
4. Try out the model by typing:

   ```shell
   ollama run granite-code:8b "How do I create a python class?"
   ```

5. You should see a response similar to:

   ```shell
   To create a Python class, you can define a new class using the "class" keyword followed by the name of the class and a colon. Inside the class definition, you can specify the methods and attributes that the class will have. Here is an example: ...
   ```

### Configure the Ollama host

By default, the Ollama server runs on IP address `127.0.0.1`, port `11434`, and http as a protocol. If you change the IP address or the port where Ollama is available:

1. In Visual Studio Code, open the extension settings for watsonx Code Assistant.
1. In **Wca > Local: API Host**, add the host IP and port.

### Configure the Granite model to use

By default, watsonx Code Assistant uses the `granite-code:8b` model for both chat and code completion. If your environment has enough capacity, install the `granite-code:8b-base` model.

To use a different model:
1. Install the `granite-code:8b-base` model. See [Install the IBM Granite code model](#install-the-ibm-granite-code-model).
1. In Visual Studio Code, open the extension settings for watsonx Code Assistant.
1. In **Wca > Local: Code Gen Model**, enter `granite-code:8b-base`.

## Securing your setup

### Your IDE environment

IBM watsonx Code Assistant does not provide any additional security controls. It's recommended the following steps be taken to properly secure your setup:

- Apply all updates for your IDE to help ensure you have the latest security and bug fixes.
- The IBM watsonx Code Assistant logs are stored in *.log files under `<your home directory>/.wca`. These files are not encrypted, other than the encryption that your file system provides. Safeguard the logs against improper access.

### Chat conversation storage

IBM watsonx Code Assistant stores all your chat conversations locally in your file system under `<your home directory>/.wca/chat.db`, in a database format defined by <a href="https://www.sqlite.org/index.html" target="_blank">SQLite</a>. IBM watsonx Code Assistant does _not_ share these conversations with anyone. This file is not encrypted, other than the encryption that your file system provides. Safeguard this file against improper access.

### Telemetry data

IBM watsonx Code Assistant does _not_ collect any telemetry data. In general, IBM watsonx Code Assistant does not send any data that it processes to a third party, IBM included.

### Connecting IBM watsonx Code Assistant and Ollama

By default, the Ollama server runs on IP address 127.0.0.1, port 11434, using http as a protocol, on your local device. To use https instead, or go through a proxy server, see the <a href="https://github.com/ollama/ollama/blob/main/docs/faq.md#how-can-i-use-ollama-with-a-proxy-server" target="_blank">Ollama documentation</a>.


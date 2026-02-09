![logo](https://github.com/user-attachments/assets/3af4e228-79b2-4fa0-a45c-c38276c6db91)

# Python-Use: A New AI Agent Paradigm (Agent 2.0)

**AI-Powered Python & Python-Powered AI**

Python-Use is a task-driven, result-oriented intelligent execution paradigm. It tightly integrates LLMs with a Python interpreter to establish a complete loop:

> **Task → Plan → Code → Execute → Feedback**

## Background: The Outdated "Prosthetic" AI Agent Model

Traditional AI (Agent 1.0) relies on Function Calling, Tools, MCP-Servers, Workflows, and plugin-based clients. These external "prosthetics" lead to:
- High entry barriers
- Heavy reliance on developers
- Poor coordination between tools
- Most AI-generated code locked in cloud sandboxes, unable to interact with the real environment

We urgently need a new paradigm that reconnects AI with the real world and fully activates its native execution power—ushering in the **AI Think Do** era.

## What is Python-Use?

Python-Use provides the entire Python execution environment to LLM. Imagine LLM sitting in front of a computer, typing various commands into the Python command-line interpreter, pressing Enter to execute, observing the results, and then typing and executing more code.

This gives models two core capabilities:
- **API Calling**: Automatically generate and execute Python code to invoke APIs
- **Packages Calling**: Flexibly leverage Python's ecosystem to orchestrate workflows

Users only need to provide a task description or API key. The model handles the rest—no plugin registration, no toolchain setup, no workflow editing.

> **Important**: Python-Use is _not_ a code generator or smart IDE.
> It's a task-first, outcome-driven AI Agent.

To the user, Python-Use is simple:
> Describe a task → AI executes it → Result returned.

The model autonomously understands, plans, writes, debugs, and executes code—and fixes bugs along the way. Code is just an internal implementation—not the deliverable. The real deliverable is the **result**.

## Why Python?

While this paradigm theoretically supports any language, we choose Python because:
- It has a powerful ecosystem spanning data, automation, system control, and AI
- Its syntax is simple and readable, ideal for model generation and debugging
- Models are naturally more proficient in Python for accurate and efficient coding

## Core Principle: No Agents, Code is Agent

Python-Use introduces a radically simplified execution architecture:

**No Agents, No MCP, No Workflow, No Clients…**

It discards legacy layers and lets models use code to directly act on the environment. In short: **Code is Agent**.

With Python, the model can:
- **Python use Data**: Load, transform, analyze
- **Python use Browser**: Automate the web
- **Python use Computer**: Access file systems and local resources
- **Python use IoT**: Control devices and embedded systems
- **…**
- **Python use Anything**: Code becomes a universal interface

This means:
- **No MCP**: No standardized protocol needed—code is the protocol
- **No Workflow**: Model plans and executes on the fly
- **No Tools**: No plugin registrations needed—just use existing ecosystems
- **No Agents**: Code replaces orchestration—execution becomes native

This is the bridge that reconnects LLMs to the real digital world, unlocking their latent power.

## Execution Mode: AI Think Do

**AI Think Do = True Integration of Knowing & Doing**

- **Task**: User describes intent
- **Plan**: Model decomposes and plans a path
- **Code**: Optimal Python strategy is generated
- **Execute**: Direct interaction with the environment
- **Feedback**: Output is evaluated and looped back into planning

No external agent needed. The AI completes the full loop independently, unleashing true cognitive-action capability.

## Single Entry Point: AiPy

You don't need multiple AI apps or UI wrappers anymore.

Just run one thing: **AiPy**, a Python-powered AI Client.

- **Unified interface**: All interaction via Python
- **Zero clutter**: No plugin mess, no bloated clients
- **AiPy**: https://www.aipy.app/

## Usage
AiPy has two running modes:

### Task Mode (Default)
Very simple and easy to use—just input your task. Suitable for users unfamiliar with Python.

### Python Mode (`--python`)
Suitable for users familiar with Python, allowing both task input and Python commands. Ideal for advanced users.

## Basic Config

Create `~/.aipyapp/aipyapp.toml`:

```toml
[llm.deepseek]
type = "deepseek"
api_key = "Your DeepSeek API Key"
```

## Task Mode Examples

### Installation
```bash
pip install aipyapp
```

### Usage
```bash
aipy
```

```
🚀 Python use - AIPython (0.1.22) [https://aipy.app]
>>> Get the latest posts from Reddit r/LocalLLaMA
......
>>> /done
```

## Python Mode Examples

### Start Python Mode
```bash
aipy --python
```

### Basic Usage
Automatic task processing:

```
Python use - AIPython (Quit with 'exit()')
>>> ai("Get the title of Google's homepage")
```

### Automatically Request to Install Third-Party Libraries
```
>>> ai("Use psutil to list all processes on MacOS")

📦 LLM requests to install third-party packages: ['psutil']
If you agree and have installed, please enter 'y [y/n] (n): y
```

### Basic Config
~/.aipyapp/aipyapp.toml:
```toml
[llm.deepseek]
type = "deepseek"
api_key = "Your DeepSeek API Key"
```

### Task Mode
`uv run aipy`
```
>>> Get the latest posts from Reddit r/LocalLLaMA
......
......
>>> /done
```

`pip install aipyapp` and run with `aipy`

```
-> % aipy
🚀 Python use - AIPython (0.1.22) [https://aipy.app]
>> Get the latest posts from Reddit r/LocalLLaMA
......
>>
```

### Python Mode

#### Basic Usage
Automatic task processing:

```
>>> ai("Get the title of Google's homepage")
```

#### Automatically Request to Install Third-Party Libraries
```
Python use - AIPython (Quit with 'exit()')
>>> ai("Use psutil to list all processes on MacOS")

📦 LLM requests to install third-party packages: ['psutil']
If you agree and have installed, please enter 'y [y/n] (n): y

```

## Vision: Free the AI, Reach AGI

Python-Use is more than a tool—it's a future-facing AI philosophy:

> **The Model is the Product → The Model is the Agent → No Agents, Code is Agent → Just Python-use → Freedom AI (AGI)**

It transforms AI from "just speaking" to "taking action," from plugin-bound to autonomous execution. It unlocks full production power—and lights the path to general intelligence.

Join us. Let AI break free, act freely, and build the future.

**The real general AI Agent is NO Agents!**

**No Agents, Just Python-use!**

## Self-Evolution: Multi-Model Fusion

AI evolution is not just language modeling—it's multi-modal intelligence.

- Integrates vision models for image/video understanding
- Adds speech models for listening and speaking
- Embeds expert models for domain reasoning
- All fused and coordinated under a unified AI control loop

This moves us from "chatbots" to fully embodied AI agents—on the path to true AGI.

## Thanks

- **Hei Ge**: Product manager/senior user/chief tester
- **Sonnet 3.7**: Generated the first version of the code, which was almost ready to use without modification
- **ChatGPT**: Provided many suggestions and code snippets, especially for the command-line interface
- **Codeium**: Intelligent code completion
- **Copilot**: Code improvement suggestions

---

**Python-Use: The Future of AI Agents**




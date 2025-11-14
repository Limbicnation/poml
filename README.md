# poml
A markup language for defining, orchestrating, and managing AI prompt templates with advanced composition and templating capabilities.

## Overview

POML (Prompt Markup Language) is a powerful framework for creating and managing AI prompt templates with advanced composition and templating capabilities. For more information about POML, see the [official POML repository](https://github.com/microsoft/poml).

This repository contains various POML configurations for agentic AI systems, including social media content generation, sophisticated 3D modeling with Blender, code engineering and QA, job applications, and specialized development workflows.

## Project Structure

- `/prompts/` - Contains all POML template configurations
- `CLAUDE.md` - Project instructions and Blender Agent documentation
- `GEMINI.md` - Gemini-specific configuration documentation
- `QWEN.md` - QWEN model documentation

## Available Configurations

### Social Media Post Generator (`social-media-post.poml`)
Generate engaging social media content with the right tone, hashtags, and calls to action for various platforms.

Key features:
- **Tone Control:** Maintains a concise, engaging, and humble tone
- **Platform Awareness:** Adapts content for different platforms (Twitter X, Instagram, Facebook, LinkedIn)
- **Structured Output:** Follows a consistent format with post content and relevant hashtags
- **Built-in Call to Action:** Automatically incorporates clear calls to action

### Blender Agent (`blender_agent.poml`)
Enhanced agentic 3D modeling assistant configuration that provides sophisticated AI-assisted 3D modeling workflows through structured prompt templates.

Key features:
- **Advanced Reasoning Structure:** Systematic requirement analysis and clarification
- **Multi-Phase Workflow:** 5-step process from planning to implementation
- **Error Handling:** Comprehensive debugging and quality assurance
- **Multi-modal Support:** Integration with external resources and existing scenes
- **Technical Planning:** API analysis and performance optimization

#### Workflow Phases:
1. **Requirement Analysis & Clarification** - Understanding user objectives and constraints
2. **Technical Planning & Resource Assessment** - Analyzing complexity and required Blender modules
3. **Iterative Script Development** - Creating robust Python scripts using bpy, bmesh, etc.
4. **Quality Assurance & Debugging** - Testing and optimization recommendations
5. **Documentation & Usage Instructions** - Clear implementation and customization guidance

### Other Configurations
- `ai-engineer.poml` - Senior AI engineer for code editing and refactoring
- `code-qa.poml` - Specialized Code-QA assistant
- `comfyui-node-developer.poml` - Developer for ComfyUI custom nodes
- `job_application.poml` - Assistant for creating job applications
- `job-interview.poml` - Comprehensive job interview process guide
- `job_search.poml` - Specialized job search assistant
- `job-preparation.poml` - Job preparation and evaluation guide for candidates
- `stable-audio.poml` - Audio generation with Stable Audio
- `unreal-cpp-senior.poml` - Senior Unreal Engine C++ developer
- `wordpress_agent.poml` - WordPress development assistant

## Agent Template System

This repository includes a comprehensive **agent configuration template** (`subagent-structure.md`) for creating production-ready AI agents using POML and YAML frontmatter.

### What is the Agent Template?

The template provides a structured framework for designing AI agents with:
- **YAML frontmatter metadata** for agent routing and discovery
- **4 architecture patterns** (Simple Role-Based, Procedural Workflow, Multi-Phase Project, Agentic System)
- **POML syntax reference** with all markup elements and examples
- **Best practices and anti-patterns** guide for quality assurance
- **Complete working examples** demonstrating real-world usage

### Quick Start: Create Your First Agent

**5-Step Process:**

1. **Open the template:** See `subagent-structure.md`
2. **Copy the Basic Template Structure** section
3. **Fill in YAML frontmatter:**
   ```yaml
   name: your-agent-name          # kebab-case (e.g., python-code-reviewer)
   description: When to invoke     # Specific trigger description
   tools: Read, Write, Edit        # Minimum necessary tools
   version: 1.0                    # Semantic versioning
   domain: Your, Expertise, Areas  # High-level domains
   ```
4. **Choose an architecture pattern:**
   - **Simple Role-Based** → Straightforward input/output tasks
   - **Procedural Workflow** → Step-by-step processes with validation
   - **Multi-Phase Project** → Complex projects with prerequisites
   - **Agentic System** → Multi-turn interactions with context management
5. **Customize and test** with real-world scenarios

### Architecture Pattern Selection

| **If your agent needs...** | **Use this pattern** |
|----------------------------|---------------------|
| Single focused task with clear I/O | Simple Role-Based |
| 5+ sequential steps with checkpoints | Procedural Workflow |
| Complex workflow with prerequisites | Multi-Phase Project |
| State tracking across multiple turns | Agentic System |

### Example Agents in This Repository

Explore these production-ready examples to learn agent design patterns:

- **Social Media Post Generator** (`prompts/social-media-post.poml`)
  - Pattern: Procedural Workflow
  - Features: 5-phase systematic process, engagement psychology, platform intelligence

- **Git DevOps Engineer** (`prompts/git-devops.poml`)
  - Pattern: Agentic System
  - Features: Context management, multi-turn interactions, validation framework

- **Blender Agent** (`prompts/blender_agent.poml`)
  - Pattern: Multi-Phase Project
  - Features: Prerequisites, error handling, comprehensive documentation

### Key Components

Every well-designed agent includes:

✅ **YAML Frontmatter** - Metadata for routing and discovery
✅ **Role Description** - Specific expertise and capabilities
✅ **Systematic Procedure** - Step-by-step workflow with validation
✅ **Input Variables** - Documented parameters with examples and defaults
✅ **Validation Framework** - Quality criteria and success metrics
✅ **Output Format** - Structured response specification

### Best Practices

**DO:**
- ✅ Be specific in role descriptions ("Python security specialist" not "coding assistant")
- ✅ Include validation checkpoints in every phase
- ✅ Provide concrete examples for inputs and outputs
- ✅ Request minimum necessary tool permissions
- ✅ Document variables with format, examples, and validation

**DON'T:**
- ❌ Use vague descriptions or generic capabilities
- ❌ Skip validation or error handling sections
- ❌ Request unnecessary tool permissions
- ❌ Leave variables undocumented
- ❌ Forget context management for multi-turn agents

### Additional Resources

- **Template Guide:** `subagent-structure.md`
- **POML Official Repository:** https://github.com/microsoft/poml
- **Example Agents:** See `/prompts/` directory

---

## Getting Started

1. Install a POML-compatible AI assistant
2. Load any of the provided `.poml` configuration files into the assistant
3. Provide the required inputs as defined in each configuration
4. The assistant will generate content based on the template

## Syntax

<poml>
  <p>Hello, world!</p>
</poml>

## Documentation

For detailed information about each configuration, refer to the specific documentation files:
- `QWEN.md` - Social Media Post Generator
- `CLAUDE.md` - Blender Agent (Claude version)
- `GEMINI.md` - Blender Agent (Gemini version)

## Contributing

We welcome contributions from the community! If you have an idea for a new feature or have found a bug, please open an issue on our GitHub repository.
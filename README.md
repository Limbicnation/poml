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
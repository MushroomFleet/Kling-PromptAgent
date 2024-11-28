# Kling1.5 PromptAgent

A specialized prompt generation system for text-to-image, text-to-video, and image-to-video AI models, powered by Claude. This agent utilizes the ACE-HOLOFS (Holographic Filesystem) and ACE methodology (Adaptive Capacity Elicitation) for optimized prompt generation. This can be used with other good LLM's with some modification, it can also be extended, by providing new Prompt examples to the relevant .txt files.

## Overview

Kling1.5 PromptAgent is designed to generate high-quality, structured prompts for various AI generation tasks. It maintains consistent quality through its modular architecture and example-based learning system.

## Features

- Text-to-Image prompt generation with 5W1H framework
- Text-to-Video prompt generation with temporal awareness
- Image-to-Video prompt generation with physics-compliant movement suggestions
- Virtual filesystem for organized prompt management
- Comprehensive example database for each generation type

## Installation

1. Create a new Claude Project
2. Add the following files as Artifacts in your project:
   ```
   ACEHOLOFS-V3.txt
   kling15-image-to-video-examples.txt
   kling15-image-to-video-prompt-module.md
   kling15-project-manifest-normal.md
   kling15-text-to-image-examples.txt
   kling15-text-to-image-prompt-module.md
   kling15-text-to-video-examples.txt
   kling15-text-to-video-prompt-module.md
   ```

3. Navigate to Custom Instructions in your Claude Project settings
4. Locate the `kling15-agent-custom-instructions.md` file in the `/custom-instructions/` folder of this repository
5. Copy the contents into your Claude Project's Custom Instructions dialog

## Verification

To verify successful installation, start a new conversation and ask Claude to perform a system check. The agent should initialize its holographic filesystem and confirm all modules are available.

## Usage

For detailed usage instructions, please refer to our tutorial guides:

- [Main Tutorial](/tutorial/README.md) - Complete system overview and general usage
- [Text-to-Image Prompt Guide](/tutorial/text-to-image-prompt-guide.md) - Detailed T2I prompt generation guide
- [Text-to-Video Prompt Guide](/tutorial/text-to-video-prompt-guide.md) - Comprehensive T2V prompt creation
- [Image-to-Video Prompt Guide](/tutorial/image-to-video-prompt-guide.md) - I2V animation prompt guidelines

## System Architecture

The system uses a holographic filesystem (HOLOFS) and Adaptive Capacity Elicitation (ACE) methodology to maintain consistent prompt generation quality. The project manifest ensures proper initialization of all components in each new conversation.

## Contributing

We welcome contributions! Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built for use with Anthropic's Claude
- Inspired by modern prompt engineering practices
- Developed to maintain consistent quality in AI content generation

## Support

If you encounter any issues or have questions:
1. Check the tutorial guides
2. Review the example files
3. Create an issue in this repository

## Project Status

Active development - Regular updates and improvements based on user feedback

---

*Note: This agent is designed specifically for Claude Projects and requires proper setup of all listed components for full functionality.*

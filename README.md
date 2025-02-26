![saplings](https://github.com/kanopi/saplings/assets/5177009/a6377e32-deb2-49d8-873a-f3dd5a36fa7c)

# Saplings - AI Image Generator

Installs and configures AI-powered image generation tools.

## Features
- Generates images using an AI provider.
- Configures AI media image generation.
- Uses OpenAI's DALL-E 3 model for image creation.

## Installation

```sh
composer require kanopi/saplings-ai-image-generator
cd web && php core/scripts/drupal recipe ../recipes/saplings-ai-image-generator
```

### Configure OpenAI

To enable AI-powered image generation, configure the OpenAI provider:

1. Create an API key at [OpenAI](https://platform.openai.com).
2. Store the API key securely in `private://keys/openai_provider.key`.
3. Ensure the key is deployed in your hosting environment to be accessible.

## Usage

To use AI-generated images, navigate to the media library and select the AI
image generation option. OpenAI’s DALL-E model will generate images based on
input prompts.

For bulk image creation and media automation, additional configurations can be
applied via the AI module settings under **Admin > Configuration > Media**.

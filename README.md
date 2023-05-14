# Hugging Face Agent Tools
A curated list of Hugging Face agent tools. PRs welcome.


## Text-to-Image

- [TextToImageTool](https://huggingface.co/spaces/huggingface-tools/text-to-image): This is a tool that creates an image according to a prompt, which is a text description. It takes an input named `prompt` which contains the image description and outputs an image.

## Text-to-Video

- [TextToVideoTool](https://huggingface.co/spaces/huggingface-tools/text-to-video): This is a tool that creates a video according to a text description. It takes an input named `prompt` which contains the image description, as well as an optional input `seconds` which will be the duration of the video. The default is of two seconds. The tool outputs a video object.

## Image-to-Image

- [ImageTransformationTool](https://huggingface.co/spaces/huggingface-tools/image-transformation): This is a tool that transforms an image according to a prompt. It takes two inputs: `image`, which should be the image to transform, and `prompt`, which should be the prompt to use to change it. It returns the modified image.

## Data/Information Retrieval

- [TextDownloadTool](https://huggingface.co/spaces/huggingface-tools/text-download): This is a tool that downloads a file from a `url`. It takes the `url` as input, and returns the text contained in the file.
- 

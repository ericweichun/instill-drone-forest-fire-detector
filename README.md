# instill-drone-forest-fire-detector
Using LLaVA1.6-13B to analyze the photos taken by drones hovering above the forest, determine if there is a wildfire risk, and respond accordingly.

# Challange
Using drones to patrol and photograph forests for fire detection automatically poses a challenge: it is typically difficult for humans to thoroughly review each photo for fire risks. Therefore, AI is employed to conduct drone-based forest fire inspections efficiently.

# Drone forest fire risk detector

The Drone Forest Fire Risk Detector can quickly determine if there is a risk of forest fires, by uploading real-time images taken by drones during automated patrols. LLaVa1.6-13B is an open-source Visual-Language Model (VLM) created through fine-tuning LLaMA/Vicuna on GPT-generated multimodal instruction-following data. This model operates as an auto-regressive language model, built on the transformer architecture.

# LLaVA1.6-13B on Instill Model

This model is accessible through the Instill Model platform and can be conveniently used to build pipelines via Instill Model connector. To utilize it, simply set the Model task to "TASK_VISUAL_QUESTION_ANSWERING" and set the Model to "llava1.6-13b" in the Instill Model connector.

For in-depth information about LLaVA1.6-13B, its capabilities, and the research behind it, please refer to the official paper and additional resources available at [LLaVa GitHub](https://llava-vl.github.io/).

# Example

Simply upload the picture captured from a drone during automated patrols. Click the "Run" button to initiate the pipeline. The drone forest fire risk detector will process your image and reply to you with the action suggestion in bilingual with traditional chinese and english.

# Instill Cloud pipeline link

https://instill.tech/ericw/pipelines/drone-forest-fire-detector

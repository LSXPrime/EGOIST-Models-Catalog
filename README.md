<h1 align="center">EGOIST - AI Hub</h1>

---

<h3 align="center"> Overview </h1>

**Standardized JSON Descriptors:**
A structured collection of JSON files for Image, Text, Voice Generation models, and Roleplay characters. 

> Each model JSON file offers comprehensive information, including name, backend, weights, path, links, additional resources, and provider.

> Each character JSON file provides detailed character information, encompassing name, personality summary, scenario, description, first message, example dialogue, additional resources, and provider.

### Character Installation
- To install a character, download its folder from `Characters`, copy it into `EGOIST (Application Directory)/Resources/Characters`, and find it in Roleplay & Characters tabs upon EGOIST startup.
- Import `TaverAI` character cards by downloading the `.webp` character, pressing the `Import` button at the bottom of the `Management/Character Creator` tab, selecting the `.webp` file, and revising its data before pressing `Save`.

### Model Installation
- Models can be downloaded directly from EGOIST, but only supports models with configs from this repo. You can parse the model data into a config file and submit a pull request to this repo.
- Support for direct downloads from HuggingFace may be provided later, pending prompt template availability for most models.
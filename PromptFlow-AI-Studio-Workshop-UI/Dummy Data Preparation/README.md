# Dummy Data Preparation
You can skip this section if you have data ready, i.e. the documents that you want to index.

We will use [Bing Chat](https://www.bing.com/search?q=Bing+AI&showconv=1) as the main LLM tools to generate dummy document. You are free to use other model to generate document too.

## Prompts
### Setting context for Bing Chat
```text
You are a corporate security officer. can you tell me what is the typical outline for a standard of procedure document?
```

### Generate dummy docs
```text
based on this outline, can you generate a standard operating procedure for compromised office entrance?
```

```text
use the same outline, can you generate a standard operating procedure for lost item in office?
```

```text
use the same outline, can you generate a standard operating procedure for fire order in office?
```

## Alternatives
You can get the sample document from the **Sample** folder directly, which is generated by Bing Chat.
# AI response images (placeholder)

1,800 images of simulated AI chatbot responses: 100 products x 6 platforms x their prompts
(wave 2 design from "An Empirical Audit of LLM Product Recommendations").

**Placeholder content:** every image currently uses the same sample text with the product name swapped in.

## Layout

```
ai_responses/<category>/<product>/<platform>__<prompt_type>.jpg
```

- platform: chatgpt, gemini, claude, deepseek, grok, mistral
- prompt_type: options ("Recommend some options for a ..."), best ("What's the best ...?"),
  and, for 50 products, two of features / use_case / max_price

`manifest.csv` lists every image with its category, product, ownership (O = affiliated with Google or an Elon Musk company, I = independent),
platform, prompt type, prompt text, path and raw GitHub URL.

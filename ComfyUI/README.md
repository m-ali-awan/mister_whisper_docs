

<details>
<summary>Calling LLMStudio models from ComfyUI nodes</summary>

- Keep in mind to not have any typo in ipv4 address
    - If you don't know ip address, it can be found by going in terminal and powershell `ipconfig`
- Also `OpenAINode` in Comfyui use `openai==0.28.0`. **So, you have to use this specific version of openai.**
    - If in **StabilityMatrix**, you can downgrade the package in a very handy UI. By looking for the correct version in the dropdown. You have to relauch ComfyUI after downgrading the openai package.
- 
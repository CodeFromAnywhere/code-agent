Consider the OpenAPI:

![](openapi.yaml)

Implement it as a set of Vercel Edge Functions:

- First make a plan before you execute
- First come up and write the individual helper functions needed. Be thorough.
- Use `export default POST` (or other methods)
- Use regular Request/Response
- Don't use any libraries
- Create stumps for any api dependencies you need in a client object
- For the LLM, use the llmServerBaseUrl and the Authorization header, and do a fetch to POST /chat/completion
- Write typescript types but for OpenAPI and JSONSchema you can use `{[key:string]:any}`

Respond with a codeblock with a nested yaml object of the file/folder structure, with in each leaf property the contents of that file.

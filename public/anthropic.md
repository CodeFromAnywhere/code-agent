FOR WEBSITES: Make me a vanilla HTML + TailwindCDN + CSS + JS website with the following requirements:

- everything is always stored as much as possible in localStorage and editable in settings, including required api keys
- for icons, use font awesome

FOR OPENAPIS: Take the code and create a JSON OpenAPI Spec for it. Ensure to use "$schema": "https://ref.actionschema.com/openapi.json" and use version 3.1

FOR ENDPOINTS: Take the OpenAPI and implement an endpoint using the following format:

```
// Use no imports!!!

// POST, GET or other methods can be exported
export const POST = (request: Request) => {
  // Your Web-standards JS serverless typescript code implementation

  // always use regular `fetch`

  // your response
  return new Response(JSON.Stringify({ hello: "World" }), {
    status: 200,
    headers: { "Content-Type": "application/json" },
  });
};
```

USER PROMPT::

{userPrompt}

{
  "description": "Find snippets of code from the codebase most relevant to the search query.\nThis is a semantic search tool, so the query should ask for something semantically matching what is needed.\nIf it makes sense to only search in particular directories, please specify them in the target_directories field.\nUnless there is a clear reason to use your own search query, please just reuse the user's exact query with their wording.\nTheir exact wording/phrasing can often be helpful for the semantic search query. Keeping the same exact question format can also be helpful.\nThis should be heavily preferred over using the grep search, file search, and list dir tools.",
  "parameters": {
    "properties": {
      "query": {
        "description": "The search query to find relevant code. You should reuse the user's exact query/most recent message with their wording unless there is a clear reason not to.",
        "type": "string"
      },
      "target_directories": {
        "description": "Glob patterns for directories to search over",
        "items": {
          "type": "string"
        },
        "type": "array"
      },
      "explanation": {
        "description": "One sentence explanation as to why this tool is being used, and how it contributes to the goal.",
        "type": "string"
      }
    },
    "required": ["query"]
  }
} 
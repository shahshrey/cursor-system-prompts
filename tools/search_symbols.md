{
  "description": "Search for symbols (functions, classes, variables, etc.) in the workspace that match the query. This is a semantic search that uses VSCode's symbol search functionality.\n\nThis tool is useful when you want to:\n1. Find all occurrences of a specific function, class, or variable\n2. Locate where a symbol is defined or used\n3. Get an overview of available symbols in the workspace\n\nThe search is semantic, meaning it understands the structure of the code and can find symbols even if they're not exact text matches.",
  "parameters": {
    "properties": {
      "query": {
        "description": "The search query to find symbols. This can be a partial name, and the search will find all matching symbols.",
        "type": "string"
      }
    },
    "required": ["query"]
  }
} 
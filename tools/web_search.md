{
  "description": "Search the web for real-time information about any topic. Use this tool when you need up-to-date information that might not be available in your training data, or when you need to verify current facts. The search results will include relevant snippets and URLs from web pages. This is particularly useful for questions about current events, technology updates, or any topic that requires recent information.",
  "parameters": {
    "properties": {
      "search_term": {
        "description": "The search term to look up on the web. Be specific and include relevant keywords for better results. For technical queries, include version numbers or dates if relevant.",
        "type": "string"
      },
      "explanation": {
        "description": "One sentence explanation as to why this tool is being used, and how it contributes to the goal.",
        "type": "string"
      }
    },
    "required": ["search_term"]
  }
} 
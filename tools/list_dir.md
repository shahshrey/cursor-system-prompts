{
  "description": "List the contents of a directory. The quick tool to use for discovery, before using more targeted tools like semantic search or file reading. Useful to try to understand the file structure before diving deeper into specific files. Can be used to explore the codebase.",
  "parameters": {
    "properties": {
      "relative_workspace_path": {
        "description": "Path to list contents of, relative to the workspace root.",
        "type": "string"
      },
      "explanation": {
        "description": "One sentence explanation as to why this tool is being used, and how it contributes to the goal.",
        "type": "string"
      }
    },
    "required": ["relative_workspace_path"]
  }
} 
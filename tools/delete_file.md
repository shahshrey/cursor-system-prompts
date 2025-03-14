{
  "description": "Deletes a file at the specified path. The operation will fail gracefully if:\n    - The file doesn't exist\n    - The operation is rejected for security reasons\n    - The file cannot be deleted",
  "parameters": {
    "properties": {
      "target_file": {
        "description": "The path of the file to delete, relative to the workspace root.",
        "type": "string"
      },
      "explanation": {
        "description": "One sentence explanation as to why this tool is being used, and how it contributes to the goal.",
        "type": "string"
      }
    },
    "required": ["target_file"]
  }
} 
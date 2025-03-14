{
  "description": "Calls a smarter model to apply the last edit to the specified file.\nUse this tool immediately after the result of an edit_file tool call ONLY IF the diff is not what you expected, indicating the model applying the changes was not smart enough to follow your instructions.",
  "parameters": {
    "properties": {
      "target_file": {
        "description": "The relative path to the file to reapply the last edit to. You can use either a relative path in the workspace or an absolute path. If an absolute path is provided, it will be preserved as is.",
        "type": "string"
      }
    },
    "required": ["target_file"]
  }
} 
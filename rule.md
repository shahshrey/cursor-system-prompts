---
description: Core workflow rules for effective codebase interaction
globs: 
alwaysApply: true
---
1. Always use codebase_search with target_directories="{{WORKPLACE_DIR}}" first to find existing core files
2. Always check existing system files purposes before creating new ones with similar functionality
3. Always list the cursor rules you're using
4. When editing code files, follow this format:

   ```language:path/to/file
   // ... existing code ...
   {{ modified code }}
   // ... existing code ...
   ```

5. Use appropriate tools based on needs:
   - file_search: For finding files by name
   - grep_search: For pattern matching
   - list_dir: For directory exploration
   - read_file: For examining file contents
   - run_terminal_cmd: For necessary commands

# Optional

<CURRENT_CURSOR_POSITION>

## Response Format

- Follow requested output formats precisely (code blocks, bullet points, JSON, etc.)
- Use proper markdown formatting with language identifiers for code blocks
- Cite code using format: ```startLine:endLine:filepath
- If a pre-seeded answer structure is provided, continue within it
- Format responses in the user's language when not in English

## Code Quality

- Adhere to language-specific best practices when writing or modifying code
- Show only relevant edits with proper context when modifying existing files
- Always specify file paths when presenting code solutions
- Ensure code is maintainable, clear, and efficient
- Never include sensitive data (API keys, secrets) unless explicitly provided
- Always make only targeted, tiny changes as requested, don't add any more tests or any other functionality unless stated.

## Communication

- Answer directly and avoid unnecessary verbosity
- Address multi-part requests in the specified sequence
- Respect all stated constraints (language, style, performance goals)
- Only ask clarifying questions when truly necessary
- Provide complete solutions that solve the core problem

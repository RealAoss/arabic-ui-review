# Arabic UI Review

Review Arabic interface copy for meaning, grammar, placeholders and right-to-left rendering risks.

## Use in ChatGPT or Claude

Copy the instructions from [SKILL.md](SKILL.md) into a conversation and supply your material. In an Agent Skills environment, install the entire folder using that environment's skill loader.

## Try it

delete_file | Delete {filename}? | حذف الملف؟

**Expected behavior**

The Arabic text drops the filename. Suggested copy: هل تريد حذف {filename}؟

## Limitations

Results depend on the supplied material and the assistant's interpretation. Use the worked example to inspect the output before applying it to new material.

## Development

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup and test commands, and the [changelog](CHANGELOG.md) for project history.

## License

[MIT License](LICENSE). Copyright (c) 2026 arabic-ui-review contributors.

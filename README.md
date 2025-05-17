# rtfm-red-team-dataset
"Red team meets large language models — building datasets and tools for AI-powered cybersecurity."
# RTFM Manual Commands Dataset

A structured and machine-readable dataset extracted from the **Red Team Field Manual (RTFM)**. This collection of categorized terminal commands is designed for use in cybersecurity tooling, AI fine-tuning, command recommendation engines, and red team automation systems.

## 📁 Dataset Format

The dataset is provided in **`.jsonl` (JSON Lines)** format, where each line represents a command entry with the following fields:

- `category` — The logical section from the manual (e.g., `"LINUX NETWORK COMMANDS"`)
- `command` — The exact command-line syntax
- `description` — A brief explanation of the command’s function

### 🔍 Example

```json
{
  "category": "LINUX NETWORK COMMANDS",
  "command": "netstat -tulpn",
  "description": "Show all TCP/UDP connections"
}
This dataset is suitable for:

    Training/fine-tuning AI assistants or LLMs (e.g., GPT-style models)

    Building context-aware command suggestion engines

    Integrating into red team or blue team automation pipelines

    Creating cheat sheet generators or CLI reference bots

📊 Statistics

    Total entries: 696

    Categories included:

        Linux Networking

        Windows System Information

        Powershell

        TCPDump

        Covering Tracks

        Firewall Bypass

        and many more

⚖️ License

This dataset is shared under the CC0 1.0 Universal License (Public Domain Dedication). You are free to use, modify, and redistribute it for any purpose, including commercial.

    Portions of this dataset are derived from the public content of the RTFM manual and restructured for machine learning research and educational use.

🤝 Contributions

Pull requests are welcome! If you'd like to expand this dataset, clean entries, or add new sections (e.g., Active Directory, web enumeration, etc.), feel free to fork or open an issue.

# 12DA

**Find out what's inside a `.12da` or `.12daz` file.**

This open-source reader helps you see which models, strings and surfaces are in
a 12d Model export. You can ask an AI assistant to run it on your computer and
explain the results in plain English.

## Try it with an AI assistant

1. Open the folder containing your export in [Claude Code](https://code.claude.com/docs/en/overview),
   [Microsoft Copilot Code in Local mode](https://learn.microsoft.com/en-us/copilot/code/use-code),
   or [Codex in the ChatGPT desktop app](https://learn.chatgpt.com/docs/environments/modes).
2. Copy the prompt below and replace `your-file.12da` with your filename.

> Use the reader at https://github.com/willsmith443/12da to inspect
> `your-file.12da` in this folder. Follow the installation instructions in the
> technical reference and run the reader locally. In plain English, tell me which
> models, strings and surfaces are in the file. Flag anything the reader only
> understood in part. If you can't access the file or run the reader, tell me
> what you need.

The assistant needs access to the file and permission to run Python 3.12 or
later. The GitHub link gives it the setup instructions.

For a test run, [download the sample file](tests/fixtures/synthetic/complete.12da),
put it in the folder you open, and use `complete.12da` in the prompt.

## What it can do today

The reader is experimental and read-only. It reports partial results when it
can't fully interpret an export. Writing selected linework back to 12DA is
planned.

[Install it yourself or read the technical reference](docs/technical-reference.md)
· [Report a problem](SECURITY.md) · [MIT licence](LICENSE)

An independent project for 12d Model exports.

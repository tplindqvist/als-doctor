# Als-doctor

A tool that scan ableton project files (.als) and prepare them for migration to another computer. Specifically made for smooth collaborative work.

## Why

Collaborating on Ableton Live projects across different computers is notoriously frustrating. Producers constantly run into broken workflows due to missing plugins, uncollected samples, and untracked file paths. Managing this manually is a time-consuming chore.

## Purpose

Built as a learning project for my .NET developer studies, to get hands-on
with C#, .NET and version control with Git.

## Status

In development — stage 0 of 10.
Development log (in Swedish): [docs/loggbok.md](docs/loggbok.md)

## Planned features

- List every sample a Live set references
- Report which of them are missing from disk
- List plugin dependencies, so a collaborator knows what they need installed
- Collect used samples into a folder, ready to transfer
- Find unused files left over in the project folder

The tool reads and copies. It never writes to an '.als' file and never
deletes anything.

## Tech

C# / .NET 10. No third-party dependencies — 'GZipStream' for decompression, 'System.Xml.Lindq' for parsing, xUnit for tests.

## Sources and tools

Ableton's Live Set file format is undocumented. The structure described in
[docs/als-format.md](docs/als-format.md) is based on my own notes from
examining the files.

Claude Code to reverse engineer and understand the structure of the Ableton Live Set (The .als file is just a gzip-compressed XML).

## License

MIT.

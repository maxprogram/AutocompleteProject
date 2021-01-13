# CLI autocomplete project

- GOAL: Create a command-line application that autocompletes, giving a short list of the top possibilities when you start typing in it (or with tab completion).
- There should be a server script that serves the words requested.
- "Front end" is the CLI that connects to the server.
- The dictionary of 61,000 words is in the repo (`words.json`).
- Can be in any language you choose.
- You're welcome to use whatever library you need for the display.
- The assumption here is that there could be 10,000,000 words and therefore you can't just return them all. Just however many you need at a time.
# Voter Guide Commons

This repository holds the exact instructions the [Voter Guide Commons](https://voterguidecommons.org) server sends to Claude, ChatGPT and other AI assistants, with a dated history of every change. The server code itself isn't public.

Voter Guide Commons lets those assistants answer voters' questions by quoting local newsrooms' voter guides, with the newsroom's name and a link on every answer.

The text is in [`instructions.txt`](instructions.txt). It's the same text shown at [voterguidecommons.org/how-answers-work](https://voterguidecommons.org/how-answers-work).

The list of guides and states at the top of the text comes from the newsrooms taking part, so it grows as more join.

A scheduled job checks the live server once a day and commits here whenever the instructions change, so the commit history is a record of every change to what we tell the AI. Some changes come from the newsrooms' data rather than from us, such as a new guide joining or a candidate count changing.

Voter Guide Commons is a project of [Hacks/Hackers](https://www.hackshackers.com).

## License

The instructions are licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). You're welcome to adapt them for your own project; credit Voter Guide Commons and Hacks/Hackers.

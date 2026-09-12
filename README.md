### Barbaros Karagül

Small, honest open-source tools. Every claim in them points at its evidence: a quoted policy sentence, a recorded run, a test that fails when reality disagrees.

| Project | What it is | |
|---|---|---|
| **[Why didn't my job run?](https://github.com/barbarkaragul-oss/why-didnt-my-job-run)** | Paste a GitHub Actions workflow, pick the event, see which jobs run and why. GitHub's own workflow parser and expression engine, running in your browser; checked against 65 recorded real runs. | [open](https://barbarkaragul-oss.github.io/why-didnt-my-job-run/) |
| **[PrivacyMatrix](https://github.com/barbarkaragul-oss/privacymatrix)** | Does this AI app train on your chats? 28 assistants × 14 privacy questions; every cell quotes the vendor's own policy and is re-checked against its source weekly. | [open](https://barbarkaragul-oss.github.io/privacymatrix/) |
| **[AgentMatrix](https://github.com/barbarkaragul-oss/agentmatrix)** | A cited feature matrix of AI coding agent CLIs; every cell quotes the vendor's documentation and is re-checked weekly. | [open](https://barbarkaragul-oss.github.io/agentmatrix/) |

[wdmjr-fixtures](https://github.com/barbarkaragul-oss/wdmjr-fixtures) holds the real GitHub Actions runs the simulator is tested against; every run is visible under its Actions tab.

**How these are built.** I direct, decide what to verify and what to ship; Claude writes most of the code. What makes that acceptable is the harness around it: quotes that must be found at their URL, runs that must replay, weekly checks that demote a cell when its source changes. When the tool and reality disagree, reality wins and becomes a test.

Nothing here has a server, a key or a bill. Fork it, run it with your own credentials, open an issue when a result is wrong.

[barbaros.dev](https://barbaros.dev) · [@barbarosdev](https://x.com/barbarosdev)

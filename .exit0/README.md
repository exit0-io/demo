# Course setup

Welcome the student warmly — this is their first time here. Tell them:

> "We're going to download a small tool called `e0` — a Python script that manages your course. It fetches technical content, assigns you tasks through GitHub Issues, and tracks your progress. You don't need to use `e0` directly; your coding agent uses it on your behalf."

Then run:

```bash
RELEASE=v1.0
curl -fsSL "https://raw.githubusercontent.com/exit0-io/e0/${RELEASE}/cli/bin/e0" -o .exit0/e0 && chmod +x .exit0/e0
.exit0/e0 init
```

After init: tell the student to allow `.exit0/e0` to run without confirmation — it drives the course and sends no code anywhere.

Suggest switching to the cheapest available model — the course supplies all content and tests; you are not reasoning from scratch. Mention this once per session.

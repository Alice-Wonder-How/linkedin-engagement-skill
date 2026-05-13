# LinkedIn Engagement Playbook Skill

A reusable Hermes Agent skill for post-publication LinkedIn engagement from a personal profile.

It helps agents draft and execute a thoughtful engagement workflow after a LinkedIn post goes live:

- first comment with a concrete discussion hook
- 8-12 adjacent posts to comment on
- mechanism/reframe/question-based comments
- 10-15 relevant first-degree DM targets
- DMs that ask for perspective, not engagement
- throttled cadence for comments and DMs
- next-day reply sweep
- UI verification before reporting completion

## Install in Hermes Agent

Clone or download this repo, then copy the skill into your Hermes skills directory:

```bash
mkdir -p ~/.hermes/skills/social-media/linkedin-engagement-playbook
cp SKILL.md ~/.hermes/skills/social-media/linkedin-engagement-playbook/SKILL.md
```

Start a new Hermes session and load it:

```bash
hermes -s linkedin-engagement-playbook
```

Or ask Hermes to use it when working on LinkedIn comments, first comments, DMs, or post-publication engagement workflows.

## Use with Claude / ChatGPT / other assistants

The skill is plain Markdown. You can paste or upload `SKILL.md` into any assistant and ask it to follow the workflow.

Example prompt:

```text
Read this LinkedIn engagement skill and follow it. Help me create a post-publication engagement workflow for this LinkedIn post: [paste post/link]
```

## Important note

This is not an engagement-pod or spam workflow. It is designed for useful conversation:

- add context
- ask for perspective
- avoid generic praise
- avoid mass identical DMs
- verify live actions before claiming they are done

## License

MIT

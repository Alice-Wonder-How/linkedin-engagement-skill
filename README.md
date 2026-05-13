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

## How to use it

There are three easy ways to use this skill.

### 1. Use it in Hermes Agent

Clone or download this repo, then copy the skill into your Hermes skills directory:

```bash
git clone https://github.com/Alice-Wonder-How/linkedin-engagement-skill.git
mkdir -p ~/.hermes/skills/social-media/linkedin-engagement-playbook
cp linkedin-engagement-skill/SKILL.md ~/.hermes/skills/social-media/linkedin-engagement-playbook/SKILL.md
```

Start a new Hermes session and load it:

```bash
hermes -s linkedin-engagement-playbook
```

Example prompt:

```text
Use the linkedin-engagement-playbook skill. My LinkedIn post just went live: [paste link or post text].
Help me draft:
1. a first comment
2. adjacent LinkedIn comment angles
3. DMs to relevant first-degree connections asking for perspective
4. a next-day reply sweep plan
```

### 2. Use it with Claude, ChatGPT, or another assistant

The skill is plain Markdown. You can open `SKILL.md`, copy/paste it into any assistant, or upload the file.

Example prompt:

```text
Read this LinkedIn engagement skill and follow it.
Here is my LinkedIn post: [paste post/link].
Create a post-publication engagement plan with:
- one first comment
- 8 adjacent comment drafts
- 10 DM drafts that ask for perspective, not engagement
- a safe posting/DM cadence
- a next-day reply sweep checklist
```

### 3. Fork and customize it

Fork this repo and adapt the skill for your own voice, industry, and boundaries:

- preferred tone and comment length
- banned phrases
- industry examples
- DM style
- who to contact or avoid
- posting cadence
- verification rules


## Important note

This is not an engagement-pod or spam workflow. It is designed for useful conversation:

- add context
- ask for perspective
- avoid generic praise
- avoid mass identical DMs
- verify live actions before claiming they are done

## License

MIT

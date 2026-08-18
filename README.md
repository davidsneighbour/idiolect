<!-- markdownlint-disable-next-line MD026 -->
# Idiolect

## AI skills for a person's own writing voice

Idiolect is a collection of reusable AI skills for capturing, checking, and applying a person's idiolect - their own distinctive vocabulary, rhythm, and habits in writing. The goal is to keep AI-assisted writing sounding like the person who owns the voice, not like a generic assistant.

* [AI skills for a person's own writing voice](#ai-skills-for-a-persons-own-writing-voice)
* [Install](#install)
* [Update](#update)
* [Skills](#skills)

## Install

Install the current Idiolect skill set with:

```bash
npx skills add davidsneighbour/idiolect --yes
```

## Update

Re-run the install command to refresh an existing install:

```bash
npx skills add davidsneighbour/idiolect --yes
```

Use `--global` when the skills should be available outside the current project.

## Skills

* `idiolect` builds a voice profile from writing samples, checks a draft against that profile, and rewrites drafts so they read in the author's own voice.

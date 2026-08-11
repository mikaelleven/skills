# Agent Skills

A curated collection of reusable agent skills for common workflows, tools and development tasks.

The skills in this repository are intended for public use: copy them into your own agent setup, adapt them to your environment, or contribute improvements back to the project.

## What is included

Each skill is self-contained and documented in its own directory. A skill normally includes a `SKILL.md` file with the instructions an agent needs, plus optional scripts, examples and reference material.

## Getting started

1. Browse the available skill directories.
2. Copy the skill you want into the skills location used by your agent platform.
3. Read the skill's `SKILL.md` for any prerequisites and configuration.

The exact installation method depends on the agent platform you use.

## Repository structure

```text
skills/
  skill-name/
    SKILL.md
    scripts/        # Optional helper scripts
    references/     # Optional background material
```

## Contributing

Contributions are welcome. Please keep skills focused, reusable and clear about assumptions, prerequisites and supported environments. Add examples or validation steps whenever they improve practical usability.

Before submitting a change, ensure that the skill:

- solves a broadly useful problem;
- has a concise, descriptive `SKILL.md`;
- avoids personal paths, credentials and environment-specific assumptions; and
- documents required tools, dependencies and setup.

## License

This repository is intended to be released under the [MIT License](LICENSE). Add the included license file before publishing, or replace this section with the license you choose.

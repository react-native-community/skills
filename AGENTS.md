# AGENTS.md

## Skills

A skill is a set of local instructions stored in a `SKILL.md` file.

### Available skills

- migrate-to-strict-api: Migrate a React Native project (>= 0.80) to the strict TypeScript API. Handles the tsconfig.json opt-in, replaces deep imports, and fixes breaking type changes. (file: `migrate-to-strict-api/SKILL.md`)
- upgrade-react-native: Upgrade React Native versions in Community CLI projects using the Upgrade Helper diff. (file: `upgrade-react-native/SKILL.md`)

### How to use skills

- Trigger rule: Use `migrate-to-strict-api` when the user asks to migrate to the strict TypeScript API, enable the strict API, or fix deep imports for the strict API.
- Invocation: `/migrate-to-strict-api`
- Trigger rule: Use `upgrade-react-native` when the user asks to upgrade React Native to a newer version.
- Invocation: `/upgrade-react-native <targetVersion>`

# renovate-config

🔧 Shared Renovate presets for my repositories.

## Usage

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>canoypa/renovate-config"]
}
```

`default.json` holds only what every repository should do. Automerge, grouping and the managers to run depend on each repository, so write them in its own `renovate.json`.

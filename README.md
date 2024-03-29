# Venster Registry
A registry for verification of on-chain projects on
[venster.io](https://venster.io).

## Contributing
If you're not familiar with creating pull requests here on Github, head over to
[our Discord](https://discord.gg/64ct9tQzgn) and post your project's details in
the `✅️-registry` channel. Otherwise, proceed with the following steps.

### 1. Fork this repo

This can be done by clicking on the "Fork" button in the upper right corner.

### 2. Add your project

Edit the `registry.json` file by adding your project at the bottom of the array.
Your project should have the following structure:

```
{
  "name": <string>,
  "description": <string>,
  "artist": <string>,
  "website": <string>,
  "policy_ids": <array>,
  "storage_type": <integer | null>
}
```

- `name`: the project's name
- `description`: a description of a maximum of 300 characters (markdown enabled)
- `artist`: name(s) of the artist(s)
- `website`: a page with more info about the project
- `policy_ids`: an array with the policy id(s)
- `storage_type`: (optional)
  - `1` for monolithic on-chain
  - `2` for modular on-chain

### 3. Create a pull request

Before creating a PR, make sure the indentation is respected (2 spaces) and that
the JSON is still valid.


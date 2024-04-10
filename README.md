# My renovate configuration

This is my personal [Renovate](https://renovatebot.com/) configuration. It is used to keep dependencies up-to-date in my personal projects.

## Usage

To use this configuration in your own projects, add a `.github/renovate.json` file extending this configuration `marcolongol/renovate-config`:

```json
{
    "extends": ["github>marcolongol/renovate-config:default.json5"]
    [...]
}
```

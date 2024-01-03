# prettier-config

This is my personal Prettier config.  
To use it, follow the steps below:

## Installation

1. Use your favorite package manager (e.g. ```npm```) to install it as a dev dependency:

```bash
npm i -D @nathalyaricci/prettier-config
```

2. Create a ```.prettierrc``` file and extend the config using strings:

```json
"@nathalyaricci/prettier-config"
```

If you want to override some options, you can extend the package using ```"extends"```:

```json
{
  "extends": "@nathalyaricci/prettier-config",
  "overrides": [
    {
      // ...your configs
    }
  ]
}
```

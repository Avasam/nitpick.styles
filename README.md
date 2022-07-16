# nitpick.styles
My collection of nitpick styles

## How to use

Start by [installing nitpick](https://github.com/andreoliwa/nitpick#install).

Then add the shared configuration(s) you want to use in your `pyproject.toml`:  
https://nitpick.readthedocs.io/en/latest/configuration.html#multiple-styles
```toml
[tool.nitpick]
style = [
    "nitpick-override.toml",
    "https://raw.githubusercontent.com/Avasam/nitpick.styles/main/python.toml",
]
```

You can use nitpick directly as a [cli tool](https://nitpick.readthedocs.io/en/latest/cli.html), or as a [Flake8 plugin](https://nitpick.readthedocs.io/en/latest/flake8_plugin.html)  
Run `nitpick fix` to update all of your configurations

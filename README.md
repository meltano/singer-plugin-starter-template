# `singer-plugin-starter-template`

A starter template for building custom Singer taps and targets.

[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/meltano/meltano-cicd-lab-template)

## Testing

To test, first use the `Open in VS Code` link above to open the project in VS Code using Docker containers.

_Note: The only prerequisites to get started is to install **VS Code** and **Docker**. As needed, VS Code will prompt 
you to install any additional extensions needed to open the project._

### Docs for this lab

The docks for this lab are pulled from the SDK documentation [Building an New Tap or Target](https://sdk.meltano.com/en/latest/dev_guide.html#building-a-new-tap-or-target).

## Pre-Lab Instructions and Prep

1. ["Build Your Own Tap" Slide Deck](https://docs.google.com/presentation/d/1Z9O5ndQUQewC3gq8A_FP8jnfv0OSBKOpU3Fmcjrrv6c/edit?usp=sharing)
2. [Tap Developer's Worksheet](https://gitlab.com/meltano/academy/-/blob/main/labs/build_your_own_tap.md#choose-an-api) - new or existing

## Cookiecutter quick start

```bash
cookiecutter https://gitlab.com/meltano/sdk --directory="cookiecutter/tap-template"
```

Once you’ve answered the cookiecutter prompts, follow the instructions in the generated README.md file to complete your new tap or target. You can also reference the Meltano Tutorial for a more detailed guide.

# Web Design Directions

Before building a webpage, the agent proposes three layout and style directions in concise text. Each explains what visitors see first, what they can do next, and how color, typography, imagery, and controls support the design. Choose an entire direction or combine the layout from one option with the style from another. Implementation begins after you choose.

Works for desktop, mobile, and responsive websites. Each direction starts with the device that matters most for the task.

You can also keep an existing layout and compare palettes on their own. Proposals explain which colors to use, where to use them, and when each palette fits. [Palette reference](references/color-palettes.md)

To give different projects distinct identities, compare organizing ideas such as framed control panels, expressive interfaces, and modernist grids. Each option explains how typography, group boundaries, and controls work together. The selected direction carries through the entire page. [Design languages reference](references/design-languages.md)

## Install in Codex

Run this command from the project where you want to use the skill.

```sh
npx skills add oldSheep017/web-design-directions -a codex
```

To install from a downloaded copy, replace the example path with the directory containing `SKILL.md`.

```sh
npx skills add /path/to/web-design-directions -a codex
```

The command installs the skill in the current project by default. Add `-g` to make it available across your projects. [Installer documentation and requirements](https://github.com/vercel-labs/skills#install-a-skill)

## Try it

In Codex, try either of these prompts.

> Use $web-design-directions to design my blog homepage. I write project retrospectives and personal essays. Many of my readers visit on mobile.

> Use $web-design-directions to design a desktop parcel intake tool. Staff mainly use computers to log incoming packages and often enter several records in a row during busy periods.

You can choose a direction as presented or adjust it in your own words. For example, ask to keep the design that opens directly into an article while making the article index easy to find from the first screen. [Read the full skill instructions](SKILL.md)

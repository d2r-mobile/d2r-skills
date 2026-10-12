# D2R Skills

Agent skills for [D2R Mobile](https://github.com/d2r-mobile/d2r-mobile), design exploration, and interface redesign.

## Available skills

- [d2r-mobile](skills/d2r-mobile/SKILL.md): Build and install D2R Mobile from your own Nintendo Switch game files, with instructions for the Mac/Xcode and shell packaging routes.

- [design-reference](skills/design-reference/README.md): 制作精美专业的高保真设计参考图，用于需求脑洞、现有界面二开、改版对照及关键交互状态展示。

## Use

Clone this repository over SSH:

```sh
git clone git@github.com:d2r-mobile/d2r-skills.git
```

Each skill has its own directory under `skills/`. Copy the desired skill directory into your agent's skills directory, or open its `SKILL.md` and ask your agent to follow it. Build commands and application documentation paths in the `d2r-mobile` skill refer to a checkout of the D2R Mobile application repository.

The D2R Mobile build skill requires you to own the game and provide your own game files. The design-reference skill works with the references supplied for each task; original input screenshots are not bundled. A generated [visual example](skills/design-reference/README.md#效果示例符文之语新交互) is included to illustrate the output.

## License

[MIT](LICENSE).

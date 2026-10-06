# AwakePlay Skills

Publish and update static HTML mini-games from your AI coding assistant with [AwakePlay](https://awakeplay.com/).

## Publish a game made with AI

Ask your assistant to share a local web game, prepare a playable preview, or update the existing game while keeping its formal public link. The publish-awakeplay Skill uses AwakePlay's official CLI and browser-approved author authorization.

- Share an independent public web link with friends or a community.
- Prepare fixed-version previews and publish the reviewed version.
- Update the same project while preserving the formal link.
- Integrate leaderboards, cloud saves or gameplay analytics when requested.
- Keep ownership of your work. Platform data/export capabilities are described by the current official documentation; this package does not promise unshipped exports.

## Install

Install the official distribution repository with the Skills CLI:

```sh
npx skills add AirDia/awakeplay-skills --skill publish-awakeplay
```

Alternatively, install directly from https://awakeplay.com/skill, or copy SKILL.md into a publish-awakeplay folder in the skills directory supported by your coding assistant. Read the Skill and use your assistant's supported installation flow. Installing a Skill does not authorize a publish operation.

## Requirements and authorization

Your assistant needs access to the local project, the ability to run commands, network access and Node.js 22.15 or newer. AwakePlay publishes supported static output; it does not automatically host server backends. The author signs in and explicitly approves the Agent connection in the browser. Previews are public to anyone with the link. Confirmed releases use the selected version; update conflicts require a new author decision.

## Release integrity

This is the current distribution copy of the official Skill **0.14.0**. The file is 35,628 bytes and its SHA-256 is:

`802c49ac1b56485cbb6fedfbf014d6328fb47bd0ae91a21f78ae08bd55ac7a58`

Official sources: [Skill](https://awakeplay.com/skill), [version and hashes](https://awakeplay.com/skill-version.json), [release notes](https://awakeplay.com/release-notes), [optional game SDK](https://awakeplay.com/sdk). The recorded manifest is in [source-manifest.json](source-manifest.json). Follow the Skill's fresh-version checks before using the CLI.

This repository distributes the existing public publishing guide. It does not declare an open-source license for the AwakePlay platform or change ownership or usage rights for uploaded games.

## 中文

在熟悉的 AI 编程助手中，把现有 HTML 小游戏上传为公开试玩，或更新原作品并保持正式链接。作者仍需注册/登录并批准 Agent 连接；安装 Skill 不等于授权发布。只需提供能运行的静态产物，排行榜、云存档和游玩分析按作者需要接入。预览持链接公开，当前未交付的导出能力不包含在本包承诺内。
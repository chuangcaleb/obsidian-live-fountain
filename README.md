# Fountain Editor - Obsidian Plugin

|**[Obsidian](https://obsidian.md) plugin for [Fountain](https://fountain.io) (screenplay) syntax highlighting in the editor.**|
|:-|

[![banner](docs/assets/banner.png)](https://youtu.be/GORryaw32sI "Obsidian Fountain - Live Editor (Plugin Showcase)")

> **Youtube Demo**: [Obsidian Fountain - Live Editor (Plugin Showcase)](https://youtu.be/GORryaw32sI)

---

<!--
## FAQ
- What is Obsidian?
- What is Markdown?
- What is Fountain?
- Why this plugin?
-->

## 🔨 Usage

### 🏁 Quickstart

Once the plugin is approved, you should be able to follow [these instructions to install through Obsidian's Community Plugins]((https://help.obsidian.md/Extending+Obsidian/Community+plugins)) in Obsidian's Settings tab! Otherwise,  you may install directly with [BRAT](https://github.com/TfTHacker/obsidian42-brat).

Create a new file and just add `cssclasses: fountain` to the frontmatter metadata Properties. You will get **automatic syntax highlighting/styling according to the [Fountain syntax rules](https://fountain.io/syntax/)**!

```yaml
---
cssclasses:
  - fountain
---
# Opening Hook

> THE STINK LINK <

FADE TO:

EXT. PUBLIC RESTROOM - DAY

A POLICE OFFICER steps into a dingy restroom.

POLICE OFFICER (O.S.)
I *smell* a rat...

= Use Fountain's Synopsis to escape into [[regular markdown]]! #so-cool
```

<!-- DOCS: Where to start -->

### 📢 Notice

1. We're past functional MVP `v1.0.0`! You may start using this plugin professionally and safely. Just keep in mind that there are still pending optimizations and incomplete features.
2. That said, this plugin should only extend your view & should never modify any local files! Worst case scenario if something breaks, just force restart your Obsidian or manually remove this plugin from your `community-plugins.json` list.

---

## 🎯 Goals

|I hope to make **Obsidian be your primary writing app for Fountain screenplays**.|
|-|

🔗 The main selling point is to be able to **connect/link/annotate your helper notes directly with your screenplay**, at the exact location where you referenced it.

🤞 The second selling point is to **integrate the Fountain screenwriting workflow with all of Obsidian's ecosystem** that fosters *idea-exploration* and *knowledge-management*.

🧩 In a similar vein, certain **Obsidian plugins will add sorely missing features in your Fountain screenplay writing workflow**. The chief missing jigsaw piece is that [Fountain requires your content to be in a single file](https://github.com/chuangcaleb/ffluent#purpose) — which can get tedious when you have 120+ pages. You'll likely find a [Obsidian plugin solution](https://github.com/kevboh/longform) for every problem.

---

## ✨ Features

- 🎨 **Get Fountain syntax highlighting** in Editing View (Source mode or Live Preview)!
- ✅ **Specify which individual notes get Fountain styling** with `cssclasses: fountain` in your frontmatter (opt-in basis, subject to change)
- 🛁 **Enjoy extended Obsidian syntax** where possible — bring your regular Obsidian markdown, tools, plugins, and workflow!
  - 🧰 **Leverage Obsidian!Markdown**: Use Links, Tags, Embedded Notes / Images / Audio, Graph...
  - 🛏️ **Feel at home**: Fountain's [Section](https://fountain.io/syntax/#sections-synopses) and [Emphasis](https://fountain.io/syntax/#emphasis) syntax don't add new styles — which means they'll look like familiar Obsidian [Headings](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Headings) and [inline text styles](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Styling+text)!
  - 🪓 **Opt-out** into regular Obsidian!Markdown syntax highlighting with Fountain's [Synopsis](https://fountain.io/syntax/#sections-synopses) token!
- 🤝 **Combine with your favorite Obsidian community plugins** like [Longform](https://github.com/kevboh/longform)!
- ⚙️ **Configure** your setup with `fountain-left` and `fountain-center` as additional `cssclasses` for alignment and width!
  - 🔧 **Fine-tune** the styling using CSS variables with the format `--fountain--*`

| Read about the [Design Guidelines](docs/basic/design-guidelines.md) to understand our implementation! |
|:-|

---

## 🤝 Synergistic Tools

- **[kevboh/longform](https://github.com/kevboh/longform): *A plugin for Obsidian that helps you write and edit novels, screenplays, and other long projects.***
- [Better Fountain - Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=piersdeseilligny.betterfountain): *Fountain autocomplete, syntax highlighting, and export to PDF*
- [MeepTech/obsidian-custom-file-extensions-plugin](https://github.com/MeepTech/obsidian-custom-file-extensions-plugin): *An obsidian plugin allowing you to register and view different file extensions in a modular manner.*
- [deathau/cm-typewriter-scroll-obsidian](https://github.com/deathau/cm-typewriter-scroll-obsidian): *Typewriter Scroll Obsidian Plugin*

|Read [Synergistic Tools](docs/basic/synergistic-tools.md) for how they work together with this plugin!|
|:-|

---

## 💝 Contributing

### 👀 Overview

#### 😎 Don't know how to code? You can contribute

- 🪲 **Report bugs** on [the Issue tab](https://github.com/chuangcaleb/obsidian-fountain-editor/issues/new?assignees=&labels=%F0%9F%AA%B2+a/bug&projects=chuangcaleb/2&template=bug_report.md)!
- 📣 **Share ([the link to](https://github.com/chuangcaleb/obsidian-fountain-editor)) this plugin** around on *forums* and *channels* and with your *friends*!
  - 🌟 **Star** this repo to receive updates & help raise awareness — if this project has been worth one button click to you!
- 🗣️ **Engage** with others in the [Discussions](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions) tab!
  - 💡 [Pitch an idea](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/ideas) / feature request!
  - 🙏 [Answer questions](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/q-a) from the community!
  - 🛠️ [Share tips & tricks](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/tips-tricks) that have helped you!
  - 🤩 [Send words of encouragement](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/general) — they actually make a difference to me! :D
  - 👥 All this proves that there's a community of people who are interested!
- ✍🏼 **Create a screenplay project** using this plugin!
  - 📸 **[Showcase your work](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/showcase)** of how you took advantage of mixing the best of Fountain + Obsidian. Then I can reuse your examples in promotions, and maybe get inspiration for new features too! hehe

#### 🤓 Know how to code? You can contribute too

- 🔀 **Open a Pull Request!** *Focus on critical bugs and priority features first.*
- 🪲 **Report a bug** — but with your *specialized technical diagnosis*!
- 🫱 **Send some advice!** Not just a first-time Obsidian plugin dev, but my first public community project.

→ See [Contributing](/docs/advanced/contributing.md) for proper details!

### 🤙 Contact

The [General - Discussions](https://github.com/chuangcaleb/obsidian-fountain-editor/discussions/categories/general) tab is a neat place you can just tag me in, because you also invite anyone from the community to join in the conversation! It's also better for keeping the context scoped within this project/repo.

If you want a more personal DM'ing (or just to send a private note of thanks!), you can reach me on Discord[#chuangcaleb](https://discordapp.com/users/199882835685801984)! You can also reach out by email to [balechuang@gmail.com](mailto:balechuang@gmail.com)!

---

## 🔃 Related Projects

- [Darakah/obsidian-fountain](https://github.com/Darakah/obsidian-fountain): *Obsidian plugin to edit, write and render Fountain Writing Syntax for screenplays and scripts*
  - Formats Fountain syntax, just like this plugin
  - But for preview mode only, and must be wrapped in a code block
  - 2.5 years+ old project
- [chuangcaleb/ffluent](https://github.com/chuangcaleb/ffluent): CLI to bundle atomic Fountain screenplay files
  - My attempt to replicate `longform` but for Fountain files, as a CLI.
  - Uses a json/yaml file at each folder directory to configure a custom sequence! So you can have complex folder organization structures
  - Marked as abandoned since this project, but it may be of interest to you!
- [Highland 2](https://www.highland2.app/)
  - Made by the creator of Fountain.
  - Features its own text editor app, WYSIWYG, "Revision Mode" and analysis tools.
  - Since everything is wrapped in a nice bow, it's probably the best Fountain-writing app if you're not technical.

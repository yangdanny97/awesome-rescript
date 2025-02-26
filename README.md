### **Awesome ReScript** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things about the ReScript programming language and toolchain. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. [Contributions](#contribute) are always welcome.

**NOTE**: This repository is mainly for ReScript materials where the source code is ReScript (`.res` and `.resi` files). For materials written in ReasonML, please use the [awesome-reasonml](https://github.com/vramana/awesome-reasonml) repository.

- [ReScript](#rescript)
  - [Official Resources](#official-resources)
  - [Blogposts](#blogposts)
  - [Tutorials](#tutorials)
  - [Talks, Videos, Livestreams](#talks-videos-livestreams)
  - [Libraries and Bindings](#libraries-and-bindings)
  - [Editor Support](#editor-support)
- [Example Apps](#example-apps)
- [Contribute](#contribute)

## ReScript

### Official Resources

- [Homepage](https://rescript-lang.org)
- [Documentation](https://rescript-lang.org/docs/latest)
- [API](https://rescript-lang.org/docs/manual/latest/api)
- [Playground](https://rescript-lang.org/try)
- [Blog](https://rescript-lang.org/blog)
- [Community Page](https://rescript-lang.org/community)
- [Roadmap](https://rescript-lang.org/community/roadmap)

- [ReScript Association Homepage](https://rescript-association.org/)
- [ReScript Github Organization](https://github.com/rescript-lang/)
- [ReScript Association Github Organization](https://github.com/rescript-association)

### Community

- [Official Forum](https://forum.rescript-lang.org)
  - Post your questions mainly here, the ReScript core team is there to answer them.
- [Official Twitter](https://twitter.com/rescriptlang)
- [ReScript Subreddit](https://www.reddit.com/r/rescript)
- [ReScript Telegram Channel](https://t.me/rescriptjs)

### Blogposts

A lot of posts can be found via the [#rescript tag on dev.to](https://dev.to/t/rescript). So please check first, if a post is also there to keep this list small.
Roughly sorted from newest to oldest. But some posts have no date, get updated sometimes or are collection links.

- [ReScript for React Development](https://scalac.io/blog/rescript-for-react-development/) by [@mishaszu](https://github.com/mishaszu)
- [A Journey from JavaScript and TypeScript, to Rescript/React, via Elm, OCaml & Haskell.](https://alex.kleydints.com/a-journey-from-javascript-and-typescript-to-rescript-react-via-elm-ocaml-haskell-c878867b6fe6)
- [Ongoing list of Rescript articles](https://dusty.phillips.codes/rescript/) by [@dusty-phillips](https://github.com/dusty-phillips)
- [Rewriting a Project in ReScript](https://yangdanny97.github.io/blog/2021/07/09/Migrating-to-Rescript) by [@yangdanny97](https://github.com/yangdanny97)
- [Responsive images and cumulative layout shift](https://alexfedoseev.com/blog/dev/2021/responsive-images-and-cumulative-layout-shift) by [@alexfedoseev](https://github.com/alexfedoseev)
- [Lazy Loading Images With ReScript](https://alexfedoseev.com/blog/dev/2021/lazy-loading-images-with-rescript) by [@alexfedoseev](https://github.com/alexfedoseev)
- [Type-safe bindings in ReScript](https://www.benadamstyles.com/blog/rescript-type-safe-bindings/) by [@benadamstyles](https://github.com/benadamstyles)
- [Cool Things You Can Do with First-Class Modules in ReScriptReact](https://alexfedoseev.com/blog/dev/2020/cool-things-you-can-do-with-first-class-modules-in-rescript-react) by [@alexfedoseev](https://github.com/alexfedoseev)
- [Safe Routing in ReScript](https://alexfedoseev.com/blog/dev/2020/safe-routing-in-rescript) by [@alexfedoseev](https://github.com/alexfedoseev)

### Tutorials

- [ReScript Tutorial by protoship.io](https://github.com/protoship/rescript-tutorial)
- [ReScript GraphQL Tutorial by hasura](https://hasura.io/learn/graphql/rescript-react-apollo/introduction/)

### Talks, Videos, Livestreams

- 2021/04 - [@tom-sherman](https://github.com/tom-sherman) - NorfolkDevelopers - [Should you consider ReScript over Typescript for your next project?](https://youtu.be/XWgL51JSbGI)
- 2020/10 - [@IwanKaramazow](https://github.com/IwanKaramazow) and [@serras](https://github.com/serras) - 47 Degrees - [Immutable Conversations - ReScript](https://youtu.be/IlykOL4Z0gw)

### Libraries and Bindings

[ReScript Package Index](https://rescript-lang.org/packages)
To discover libraries and bindings for ReScript, please use the [official package index tool](https://rescript-lang.org/packages). Libraries with the `rescript` keyword in their `package.json` will appear there, as well as manually added resources. If you happen to find no bindings for a library, please ask for it on the [forum](<(https://forum.rescript-lang.org)>). Chances are that somebody already wrote them, but kept them private, because maintaining a full set of bindings is always harder than tweaking them to one's specific needs.

### Editor Support

(also refer to the [official site](https://rescript-lang.org/docs/manual/latest/editor-plugins))

#### General ReScript language support

- [ReScript-VSCode](https://marketplace.visualstudio.com/items?itemName=chenglou92.rescript-vscode)
- [ReScript-Sublime](https://github.com/rescript-lang/rescript-sublime)
- [VIM-ReScript](https://github.com/rescript-lang/vim-rescript)
- [Atom](https://atom.io/packages/ide-rescript)
- [IDEA](https://github.com/giraud/reasonml-idea-plugin)
- [Emacs](https://github.com/reasonml-editor/reason-mode)

#### Other extensions

- [vscode-rescript-relay](https://marketplace.visualstudio.com/items?itemName=GabrielNordeborn.vscode-rescript-relay)

#### Snippets in VSCode

The official snippets included with the ReScript-VSCode extension are available [here](https://github.com/rescript-lang/rescript-vscode/blob/master/snippets.json). You don't need to do anything to activate them; the extension already installs them.

But you can also add your snippets if you want to. You can add them as user snippets or in a workspace through a `rescript.code-snippets` file in the `.vscode` folder in the root of your workspace / project. See an example of some user snippets [here](rescript.code-snippets). Read more about snippets in VSCode [here](https://code.visualstudio.com/docs/editor/userdefinedsnippets).

#### Keybindings in VSCode

If you're coming to ReScript React from other languages, you probably find yourself writing `React.string("")` quite a lot, but maybe sometimes forgetting to add the `React.string` call.

Luckily, VSCode has support for adding custom keybindings. If you open your `keybindings.json` and add the following, you can select any piece of code and press `cmd+k` followed by `s` to add the `React.string` call around the selection:

```
{
  {
    "key": "cmd+k s",
    "command": "editor.action.insertSnippet",
    "when": "editorTextFocus",
    "args": {
      "snippet": "{React.string(\"$TM_SELECTED_TEXT\")}"
    }
  }
  ...rest of your keybindings.json
}
```

Change the keybinding to your liking. Read more about keybindings in VSCode [here](https://code.visualstudio.com/docs/getstarted/keybindings).

---

### Example Apps

- [ReScript Game of Life](https://github.com/alanrsoares/rescript-game-of-life) - Conway's Game of Life written in ReScript using ReScript-React. [(demo)](https://alanrsoares.github.io/reason-game-of-life/)
- [ReScript RealWorld example app](https://github.com/jihchi/rescript-react-realworld-example-app) - Another Medium.com clone written using ReScript-React
- [ReTurbo](https://github.com/RawToast/ReTurbo) - Pseudo 3D racing game built with Reprocessing [(demo)](https://pale-potato.surge.sh/)
- [Coronate](https://github.com/johnridesabike/coronate) - A Swiss-style chess tournament manager for the web and desktop, written with ReScript-React. [(web demo)](https://johnridesa.bike/coronate/)
- [Pomodoro](https://github.com/tkovs/pomodoro) - Simple pomodoro application. Written in ReScript and ReactJS. [(demo)](https://pomodoro.tkovs.com)
- [rescript-intro](https://github.com/mellson/rescript-intro) - A calculator Using ReScript, React + Tailwind.
- [Fire Emblem Chess](https://github.com/yangdanny97/fire-emblem-chess) - A pass & play chess game using ReScript, D3, and Howler [(demo)](https://yangdanny97.github.io/fire-emblem-chess/)

---

## Contribute

Just fork this repository and add your resources in a pull-request. Please check for duplicates and dead links before you submit.

**NOTE**: This repository is mainly for ReScript materials where the source code is ReScript (`.res` and `.resi` files). For materials written in ReasonML, please use the [awesome-reasonml](https://github.com/vramana/awesome-reasonml) repository.

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

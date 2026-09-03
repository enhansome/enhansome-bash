# Awesome Bash with stars

> A curated list of delightful Bash scripts and resources.

In addition to this list, you should read the list [awesome-shell](https://github.com/alebcay/awesome-shell) ⭐ 37,554 | 🐛 184 | 📅 2025-08-28. It is a curated list of awesome command-line frameworks, toolkits, guides and gizmos. You may also want to check [awesome-zsh](https://github.com/unixorn/awesome-zsh-plugins) ⭐ 17,988 | 🐛 6 | 🌐 Shell | 📅 2026-08-29 or [awesome-fish](https://github.com/bucaran/awesome-fish) ⭐ 5,068 | 🐛 16 | 📅 2026-01-25. If you are looking for more lists, check [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ⭐ 502,524 | 🐛 105 | 📅 2026-09-02.

## Contents <!-- omit in toc -->

* [Books and Resources](#books-and-resources)
* [Command-Line Productivity](#command-line-productivity)
* [Customization](#customization)
* [For Developers](#for-developers)
* [Downloading and Serving](#downloading-and-serving)
* [Applications](#applications)
* [Games](#games)
* [Website](#website)
* [Shell Package Management](#shell-package-management)
* [Shell Script Development](#shell-script-development)
* [Just for fun](#just-for-fun)
* [Community](#community)
* [Other Awesome Lists](#other-awesome-lists)
* [Contribute](#contribute)
* [License](#license)

## Books and Resources

* [Pure Bash Bible](https://github.com/dylanaraps/pure-bash-bible) ⚠️ Archived - A collection of pure bash alternatives to external processes.
* [bash-handbook](https://github.com/denysdovhan/bash-handbook) ⭐ 6,079 | 🐛 30 | 🌐 JavaScript | 📅 2024-02-05 - A handbook for those who want to learn Bash without diving in too deeply.
* [Safe ways to do things in bash](https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md) ⭐ 4,802 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - How to do things safely in Bash.
* [The Bash-Hackers Wiki](https://web.archive.org/web/20230406205817/https://wiki.bash-hackers.org/) - Human-readable documentation of any kind about GNU Bash.
* [Bash beginner's mistakes](https://web.archive.org/web/20230330234404/https://wiki.bash-hackers.org/scripting/newbie_traps) - List of Bash beginner mistakes (by the Bash-Hackers Wiki).
* [Bash Guide](http://mywiki.wooledge.org/BashGuide) - A bash guide for beginners (by Lhunath).
* [Bash FAQ](http://mywiki.wooledge.org/BashFAQ) - Answers most of your questions (by Lhunath).
* [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - Lists the common pitfalls beginners fall into, and how to avoid them.
* [Bash manual](http://www.gnu.org/software/bash/manual/) - Bourne-Again Shell manual.
* [Bash FAQ](http://tiswww.case.edu/php/chet/bash/FAQ) (by [Chet Ramey](http://tiswww.case.edu/php/chet/))
* [Advanced Bash-Scripting Guide](http://tldp.org/LDP/abs/html/) - An in-depth exploration of the art of shell scripting.
* [Bash Guide for Beginners](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/) - Bash guide for beginners (by Machtelt Garrels).
* [Bash Programming - Intro/How-to](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shellguide.html) - Reasonable advice about code style.
* [Sobell's Book](http://www.sobell.com/CR3/index.html) - A practical guide to commands, editors, and shell programming.
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [Defensive BASH Programming](https://web.archive.org/web/20180917174959/http://www.kfirlavi.com/blog/2012/11/14/defensive-bash-programming) - Methods to defend your programs from breaking as well as keeping the code tidy and clean.
* [explainshell](https://explainshell.com) - A website that breaks down and explains shell (Bash) commands (including their flags and options).

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 39,135 | 🐛 141 | 🌐 Rust | 📅 2026-08-31 - A better way to navigate your filesystem. Written in Rust, cross-shell, and much faster than other autojumpers.
* [ble.sh](https://github.com/akinomyoga/ble.sh) ⭐ 4,670 | 🐛 84 | 🌐 Shell | 📅 2026-08-18 - User-friendly and feature rich readline replacement, with syntax highlighting, better command completion, and improved multi-line editing.
* [hstr](https://github.com/dvorka/hstr) ⭐ 4,454 | 🐛 185 | 🌐 C | 📅 2026-08-28 - Bash History Suggest Box.
* [bashmarks](https://github.com/huyng/bashmarks) ⭐ 1,968 | 🐛 31 | 🌐 Shell | 📅 2026-07-05 - Directory bookmarks for the shell.
* [bashhub](https://github.com/rcaloras/bashhub-client) ⭐ 1,306 | 🐛 24 | 🌐 Python | 📅 2026-08-30 - Bash history in the cloud. Indexed and searchable :cloud:.
* [has](https://github.com/kdabir/has) ⭐ 819 | 🐛 20 | 🌐 Shell | 📅 2026-02-26 - `has` helps you check presence of various command line tools and their versions on path.
* [aliases](https://github.com/sebglazebrook/aliases) ⭐ 624 | 🐛 16 | 🌐 Rust | 📅 2024-10-28 - Contextual, dynamic, organized aliases for the bash shell.
* [sshrc](https://github.com/cdown/sshrc) ⭐ 528 | 🐛 4 | 🌐 Shell | 📅 2023-01-27 - Bring your .bashrc, .vimrc, etc. with you when you SSH.
* [utility-bash-scripts](https://github.com/aviaryan/utility-bash-scripts) ⭐ 473 | 🐛 6 | 🌐 Shell | 📅 2020-09-30 - Useful bash scripts to do automatable tasks with a single command.
* [commacd](https://github.com/shyiko/commacd) ⭐ 365 | 🐛 4 | 🌐 Shell | 📅 2019-11-07 - A faster way to move around in Bash.
* [forkrun](https://github.com/jkool702/forkrun) ⭐ 361 | 🐛 0 | 🌐 Shell | 📅 2026-09-03 - A pure-bash tool for running code in parallel. Similar in syntax and speed to `xargs -P`, but with more features and native Bash function support.
* [bashhub-server](https://github.com/nicksherron/bashhub-server) ⭐ 322 | 🐛 13 | 🌐 Go | 📅 2023-03-30 - Privately hosted open source bashhub server.
* [bashmount](https://github.com/jamielinux/bashmount) ⭐ 290 | 🐛 11 | 🌐 Shell | 📅 2022-06-30 - Easily manage removable media.

## Customization

*Custom prompts, color themes, etc.*

* [oh-my-bash](https://github.com/ohmybash/oh-my-bash) ⭐ 7,678 | 🐛 160 | 🌐 Shell | 📅 2026-09-02 - A delightful community-driven framework for managing your bash configuration.
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) ⭐ 6,938 | 🐛 35 | 🌐 Shell | 📅 2026-04-10 - An informative and fancy Bash prompt for Git users.
* [liquidprompt](https://github.com/nojhan/liquidprompt) ⭐ 4,673 | 🐛 29 | 🌐 Shell | 📅 2026-09-01 - A full-featured & carefully designed adaptive prompt for Bash & Zsh.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) ⭐ 3,715 | 🐛 56 | 🌐 Shell | 📅 2022-06-30 - An opinionated git prompt for bash and zsh.
* [LS\_COLORS](https://github.com/trapd00r/LS_COLORS) ⭐ 2,277 | 🐛 8 | 🌐 Shell | 📅 2025-06-06 - A collection of LS\_COLORS definitions.
* [bash-sensible](https://github.com/mrzool/bash-sensible) ⭐ 2,124 | 🐛 10 | 🌐 Shell | 📅 2024-10-17 - An attempt at saner Bash defaults.
* [bashstrap](https://github.com/barryclark/bashstrap) ⭐ 1,556 | 🐛 3 | 🌐 Shell | 📅 2019-05-22 - A quick way to spruce up macOS terminal.
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) ⭐ 1,156 | 🐛 2 | 🌐 Shell | 📅 2025-11-21 - Bash prompt with colors, Git statuses, and Git branches.
* [bash-powerline](https://github.com/riobard/bash-powerline) ⭐ 911 | 🐛 16 | 🌐 Shell | 📅 2023-07-06 - Powerline-style Bash prompt in pure Bash script.
* [git-prompt](https://github.com/lvv/git-prompt) ⭐ 327 | 🐛 16 | 🌐 Shell | 📅 2024-05-05 - Bash prompt with Git, SVN and HG modules.
* [progress-bar.sh](https://github.com/edouard-lopez/progress-bar.sh) ⭐ 252 | 🐛 1 | 🌐 Shell | 📅 2025-10-24 - Simple & sexy progressbar for `bash`, give it a duration and it will do the rest.
* [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme) ⭐ 176 | 🐛 2 | 🌐 Shell | 📅 2025-08-04 - Minimalistic theme (prompt) for sexy terminals.
* [gittify](https://github.com/momeni/gittify) ⭐ 80 | 🐛 0 | 🌐 Shell | 📅 2022-04-02 - A colorful Bash prompt + customized Git aliases.

## For Developers

*Command-line development, version control, and deployment.*

* [bocker](https://github.com/p8952/bocker) ⭐ 12,672 | 🐛 15 | 🌐 Shell | 📅 2017-12-09 - Docker implemented in 100 lines of bash.
* [git-sh](https://github.com/rtomayko/git-sh) ⚠️ Archived - A customized Bash environment suitable for Git work.
* [mkdkr](https://github.com/rosineygp/mkdkr) ⭐ 382 | 🐛 0 | 🌐 Shell | 📅 2021-05-27 - Make + Docker + Shell = CI Pipeline.

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) ⭐ 6,601 | 🐛 161 | 🌐 Shell | 📅 2024-06-04 - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox.
* [bashttpd](https://github.com/avleen/bashttpd) ⭐ 1,553 | 🐛 15 | 🌐 Shell | 📅 2026-07-24 - A web server written in Bash.
* [xiringuito](https://github.com/ivanilves/xiringuito) ⭐ 1,160 | 🐛 8 | 🌐 Shell | 📅 2021-12-29 - SSH-based VPN for poors.
* [Bash-web-server](https://github.com/dzove855/Bash-web-server) ⭐ 998 | 🐛 5 | 🌐 Shell | 📅 2024-02-29 - A purely bash web server, no socat, netcat, etc.
* [bash-stack](https://github.com/cgsdev0/bash-stack) ⭐ 908 | 🐛 9 | 🌐 Shell | 📅 2025-09-06 - Modern web framework in bash.
* [balls](https://github.com/jneen/balls) ⭐ 869 | 🐛 5 | 🌐 Shell | 📅 2016-07-29 - Bash on Balls.
* [sherver](https://github.com/remileduc/sherver) ⭐ 353 | 🐛 2 | 🌐 Shell | 📅 2026-08-22 - Pure Bash lightweight web server.
* [bashbro](https://github.com/victrixsoft/bashbro/) ⭐ 223 | 🐛 1 | 🌐 Shell | 📅 2024-10-11 - A Bash-based web file browser - allowing you to remotely browse, stream, view documents and save files via your web browser.
* [ngincat](https://github.com/jaburns/ngincat) ⭐ 183 | 🐛 0 | 🌐 Shell | 📅 2014-07-18 - Tiny Bash HTTP server using netcat.
* [httpd.sh](https://github.com/cemeyer/httpd.sh) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2015-08-24 - A trivial web server in bash, using ctypes.sh.

## Applications

*Command line-based applications or command line access to existing services.*

* [todo.sh](https://github.com/todotxt/todo.txt-cli) ⭐ 6,170 | 🐛 42 | 🌐 Shell | 📅 2026-09-01 - A simple and extensible shell script for managing your todo.txt file.
* [bashblog](https://github.com/cfenollosa/bashblog) ⭐ 1,928 | 🐛 35 | 🌐 Shell | 📅 2026-07-09 - A Bash script that handles blog posting.
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) ⭐ 236 | 🐛 6 | 🌐 Shell | 📅 2023-10-04 - Bash interface to the PushBullet API.
* [cheapci](https://github.com/ianmiell/cheapci) ⭐ 190 | 🐛 0 | 🌐 Shell | 📅 2022-09-22 - A continuous integration framework implemented in bash.

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) ⭐ 910 | 🐛 0 | 🌐 Shell | 📅 2024-04-30 - Bash implementation of 2048 game.
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) ⭐ 66 | 🐛 4 | 🌐 Shell | 📅 2020-05-29 - Bash implementation of minesweeper.
* [wordle](https://gist.github.com/huytd/6a1a6a7b34a0d0abcac00b47e3d01513) - Wordle in less than 50 lines of Bash.

## Website

* [Bash One-Liners](http://www.bashoneliners.com/) -  A collection of practical or just pure awesome bash one-liners ([repos](https://github.com/janosgyerik/bashoneliners) ⭐ 224 | 🐛 3 | 🌐 Python | 📅 2025-02-01 by @[janosgyerik](https://github.com/janosgyerik)).
* [commandlinefu](http://www.commandlinefu.com/) -  A repository for the most elegant and useful UNIX commands.

## Shell Package Management

*Tools for managing multiple shell configurations.*

* [bash-it](https://github.com/Bash-it/bash-it) ⭐ 15,149 | 🐛 7 | 🌐 Shell | 📅 2026-08-30 - A community Bash framework.
* [homeshick](https://github.com/andsens/homeshick) ⭐ 2,193 | 🐛 17 | 🌐 Shell | 📅 2026-08-28 - Git dotfile synchronizer written in Bash.
* [bpkg](https://github.com/bpkg/bpkg) ⭐ 1,974 | 🐛 38 | 🌐 Shell | 📅 2025-07-07 - A lightweight bash package manager.
* [basher](https://github.com/basherpm/basher) ⭐ 1,301 | 🐛 15 | 🌐 Shell | 📅 2025-11-18 - A package manager for shell scripts.

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [shellcheck](https://github.com/koalaman/shellcheck) ⭐ 39,982 | 🐛 1,138 | 🌐 Haskell | 📅 2026-08-04 - A static analysis tool for shell scripts.
* [shfmt](https://github.com/mvdan/sh) ⭐ 9,035 | 🐛 92 | 🌐 Go | 📅 2026-09-02 - Format bash programs.
* [DevOps-Bash-tools](https://github.com/HariSekhon/DevOps-Bash-tools) ⭐ 8,393 | 🐛 8 | 🌐 Shell | 📅 2026-08-24 - 750+ DevOps Shell Scripts and Advanced Bash environment.
* [bats](https://github.com/bats-core/bats-core) ⭐ 6,244 | 🐛 127 | 🌐 Shell | 📅 2026-07-26 - Bash Automated Testing System.
* [Bash Infinity](https://github.com/niieani/bash-oo-framework) ⭐ 5,619 | 🐛 36 | 🌐 Shell | 📅 2023-12-15 - A modern boilerplate / framework / standard library for bash.
* [shellharden](https://github.com/anordal/shellharden) ⭐ 4,802 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter.
* [bashly](https://github.com/DannyBen/bashly) ⭐ 2,447 | 🐛 2 | 🌐 Ruby | 📅 2026-08-24 - Bash command line framework and CLI generator.
* [bash3boilerplate](https://github.com/kvz/bash3boilerplate) ⭐ 2,213 | 🐛 17 | 🌐 Shell | 📅 2026-07-20 - Templates to write better Bash scripts.
* [shunit2](https://github.com/kward/shunit2) ⭐ 1,737 | 🐛 46 | 🌐 Shell | 📅 2026-03-15 - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* [argbash](https://github.com/matejak/argbash) ⭐ 1,483 | 🐛 33 | 🌐 M4 | 📅 2025-07-17 - Bash argument parsing code generator.
* [modernish](https://github.com/modernish/modernish) ⭐ 938 | 🐛 8 | 🌐 Shell | 📅 2026-08-06 - Library with various features for shell scripting.
* [ansi](https://github.com/fidian/ansi) ⭐ 838 | 🐛 2 | 🌐 Shell | 📅 2021-11-28 - ANSI escape codes in pure bash - change text color, position the cursor, much more.
* [bash\_unit](https://github.com/pgrange/bash_unit) ⭐ 635 | 🐛 13 | 🌐 Shell | 📅 2026-02-11 -  Bash unit testing enterprise edition framework for professionals.
* [bashful](https://github.com/jmcantrell/bashful) ⚠️ Archived - A collection of libraries to simplify writing Bash scripts.
* [mo](https://github.com/tests-always-included/mo) ⭐ 607 | 🐛 11 | 🌐 Shell | 📅 2026-01-19 - Mustache templates in pure bash.
* [assert.sh](https://github.com/lehmannro/assert.sh) ⭐ 491 | 🐛 17 | 🌐 Shell | 📅 2022-01-21 - Bash unit testing framework.
* [json.bash](https://github.com/h4l/json.bash) ⭐ 462 | 🐛 1 | 🌐 Shell | 📅 2024-12-08 - Bash library and command-line tool that creates JSON.
* [bashunit](https://github.com/TypedDevs/bashunit) ⭐ 424 | 🐛 0 | 🌐 Shell | 📅 2026-09-03 - A simple testing library for bash scripts.
* [lobash](https://github.com/adoyle-h/lobash) ⭐ 399 | 🐛 0 | 🌐 Shell | 📅 2024-09-14 - A modern, safe, powerful utility/library for Bash script development.
* [semver\_bash](https://github.com/cloudflare/semver_bash) ⭐ 268 | 🐛 13 | 🌐 Shell | 📅 2026-04-24 - Semantic Versioning in Bash.
* [bunit](https://github.com/rafritts/bunit) ⭐ 202 | 🐛 1 | 🌐 Shell | 📅 2022-11-03 - A unit testing framework for Bash scripts.
* [timep](https://github.com/jkool702/timep) ⭐ 193 | 🐛 0 | 🌐 Shell | 📅 2026-06-27 - A next-gen profiler and FlameGraph generator for bash code.
* [Bashmatic](https://github.com/kigster/bashmatic) ⭐ 183 | 🐛 5 | 🌐 Shell | 📅 2026-06-23 - An easy to use DSL library for building BASH-based tooling & installers (900+ functions).
* [bash-modules](https://github.com/vlisivka/bash-modules) ⭐ 151 | 🐛 2 | 🌐 Shell | 📅 2025-08-27 - A collection of modules for unofficial strict mode.
* [async-bash](https://github.com/zombieleet/async-bash) ⭐ 146 | 🐛 0 | 🌐 Shell | 📅 2022-03-19 - Implementation of async functions in bash.
* [bashify](https://github.com/zombieleet/bashify) ⭐ 106 | 🐛 0 | 🌐 Shell | 📅 2016-12-19 - Few helper functions in bash (especially string manipulation functions).
* [bashmanager](https://github.com/lingtalfi/bashmanager) ⭐ 102 | 🐛 0 | 🌐 Shell | 📅 2016-02-27 - Mini bash framework for creating command line tools.
* [bashing](https://github.com/xsc/bashing) ⚠️ Archived - Smashing Bash into Pieces - Bash framework for creating command line tools.
* [alinex bashlib](https://gitlab.com/alinex/bash-lib) - Modular bash library for server administration, data processing, and remote scripting.

## Just for fun

* [Bash Screensavers](https://github.com/attogram/bash-screensavers?) ⭐ 949 | 🐛 11 | 🌐 Shell | 📅 2026-07-23 - A collection of screensavers written entirely in bash.
* [pokeget](https://github.com/talwat/pokeget) ⚠️ Archived - Displays sprites of pokemon in the terminal.

## Community

* [Stack Overflow](http://stackoverflow.com/questions/tagged/bash) - Bash tag on Stack Overflow.
* [/r/bash](https://www.reddit.com/r/bash) - A subreddit dedicated to bash scripting.
* [/r/commandline](https://www.reddit.com/r/commandline) - For anything regarding the command line, in any operating system.
* [#bash](https://web.libera.chat/?nick=Guest\&#bash) - IRC channel on Libera.​Chat. The main contributors of the BashGuide, BashFAQ, BashPitfalls and ShellCheck hang around there.

## Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) ⭐ 3,206 | 🐛 26 | 📅 2024-07-31 and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,644 | 🐛 62 | 🌐 Ruby | 📅 2024-06-02.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, aloisdg has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._

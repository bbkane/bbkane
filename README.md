# About Me

Hi, I'm Ben Kane! See my [personal website and blog](https://www.bbkane.com/) or browse through my projects (active and abandoned) here on GitHub :)

- [PRs to projects I don't own](https://github.com/search?q=author%3Abbkane+-owner%3Abbkane&type=pullrequests) (also see [Issues](https://github.com/search?q=author%3Abbkane+-owner%3Abbkane&type=issues))
- [Project star history](https://star-history.com/#bbkane/dotfiles&bbkane/grabbit&bbkane/fling&bbkane/starghaze&bbkane/gocolor&bbkane/warg&bbkane/shovel&bbkane/envelope&Date)
- [Repos containing my username](https://sourcegraph.com/search?q=context:global+-lang:svg+-repo:bbkane+bbkane&patternType=standard&sm=1&groupBy=repo)

# Selected Projects

## [dotfiles](https://github.com/bbkane/dotfiles)

Configs for apps I care about - see the [`zsh`](https://github.com/bbkane/dotfiles/tree/master/zsh) config especially :)

## [enventory](https://github.com/bbkane/enventory)

Store project environmental files in a central database.

![demo.gif](https://raw.githubusercontent.com/bbkane/enventory/master/demo.gif)

## [fling](https://github.com/bbkane/fling)

fling computes and creates/removes the minimal amount of symlinks needed in a directory to refer to files and directories in another directory,  similar to GNU Stow. I use fling to manage my dotfiles.

![demo.gif](https://raw.githubusercontent.com/bbkane/fling/master/demo.gif)

## [gocolor](https://github.com/bbkane/gocolor)

A tiny cross-platform cross-platform terminal color library that supports enabling and disabling colors.

![screenshot](https://github.com/bbkane/gocolor/raw/master/TestWithReflection.png)

## [grabbit](https://github.com/bbkane/grabbit)

A small single-binary CLI to grab images from Reddit - I've been  surprised how much I enjoy seeing beautiful wallpapers when I  lock/unlock my computer.

![example](https://github.com/bbkane/grabbit/raw/master/reddit_wallpapers.jpg)

## [logos](https://github.com/bbkane/logos)

Logging + Printing + Compromising

![demo](https://github.com/bbkane/logos/raw/master/demo/demo.gif)

## [observable.bbkane.com](https://github.com/bbkane/observable.bbkane.com)

Source code for https://observable.bbkane.com/git-data , which graphs commits over time in different ways.

## [shovel](https://github.com/bbkane/shovel)

Make a lot of DNS requests and count the results! Useful for testing complex dynamic DNS records.

![demo](https://github.com/bbkane/shovel/raw/master/demo.gif)

## [starghaze](https://github.com/bbkane/starghaze)

Save information about your GitHub starred repos into Google Sheets, Zinc, and SQLite!

```
$ sqlite3 starghaze.db '
SELECT
    l.Name ,
    COUNT(lr.Language_id) as Repo_Count
FROM
    Language_Repo lr JOIN Language l ON lr.Language_id = l.id
GROUP BY Language_id
ORDER BY Repo_Count DESC
LIMIT 10
'
-- Loading resources from /Users/bbkane/.sqliterc
┌────────────┬────────────┐
│    Name    │ Repo_Count │
├────────────┼────────────┤
│ Shell      │ 939        │
│ JavaScript │ 617        │
│ HTML       │ 598        │
│ Python     │ 540        │
│ Makefile   │ 519        │
│ CSS        │ 432        │
│ Dockerfile │ 403        │
│ Go         │ 367        │
│ C          │ 305        │
│ C++        │ 230        │
└────────────┴────────────┘
```

## [toddlerevents](https://github.com/bbkane/toddlerevents)

Find Bay Area toddler events (currently only from public libraries) to attend with my son that are outside of work hours. Updates https://github.com/bbkane/toddlerevents.bbkane.com each Friday and Monday.

## [warg](https://github.com/bbkane/warg)

Declarative and Intuitive Command Line Apps with Go

![demo](https://github.com/bbkane/warg/raw/master/img/image-20220114212104654.png)

<!--
**bbkane/bbkane** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

TODO:
- Add tablegraph if I ever care enough to spruce up the docs
-->

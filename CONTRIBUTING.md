# Contributing

Thanks for helping to grow this list! New links are very welcome.

## The easy way (no git needed)

1. Open the file you want to change: [cw.md](cw.md) or [tools.md](tools.md).
2. Click the pencil icon (**Edit this file**).
3. Add your link, then click **Propose changes**. GitHub makes the fork and the
   Pull Request for you.

If you do not want to edit files at all, just
[open an issue](https://github.com/cqham/awesome/issues/new/choose) and suggest the link.

## The git way

```sh
# fork the repo on GitHub first, then:
git clone ssh://git@github.com/<your-user>/awesome.git
cd awesome
git switch -c add-my-link
# edit the file, then:
git commit -am "Add <name> to <section>"
git push -u origin add-my-link
```

Then open a Pull Request against `main`.

## Link format

One line per link, in this shape:

```markdown
- [Name](https://example.com/) — short description
```

Rules:

- **Name** is the real name of the site or tool, not the bare URL.
- The description is short (a few words) and says what it is. It may be left
  out if the name already says everything.
- Use an em dash (`—`) between the name and the description.
- Add the link at the **end** of its section.

## Where does my link go?

| File | Content |
|---|---|
| [cw.md](cw.md) | Morse code: keys and devices, books and papers, online trainers |
| [tools.md](tools.md) | Calculators, maps and other online tools |

If nothing fits, open an issue and we will talk about a new file or section.

## Before you open the PR

- [ ] The link works and is free to open (no login wall, no paywall).
- [ ] The link is not already in the list.
- [ ] It is about ham radio.
- [ ] One link per Pull Request, if possible. It makes review faster.

A bot checks every Pull Request for dead links. If it fails, look at the log —
it is usually a typo in the URL.

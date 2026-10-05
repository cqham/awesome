# Contributing

Thanks for helping to grow this list! New links are very welcome.

## The easy way (no git needed)

1. Open the file you want to change: [cw.md](cw.md), [software.md](software.md)
   or [tools.md](tools.md).
2. Click the pencil icon (**Edit this file**).
3. Add your row, then click **Propose changes**. GitHub makes the fork and the
   Pull Request for you.

If you do not want to edit files at all, just
[open an issue](https://github.com/cqham/awesome/issues/new/choose) and suggest
the link.

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

## Row format

Every list is a Markdown table. Add one row at the **end** of the right table,
and fill every column that table has.

Most tables have three columns:

```markdown
| Name | What it is | Link |
|---|---|---|
| Morse Code Ninja | Huge set of practice audio, words and phrases | https://morsecode.ninja/ |
```

Software tables add **Platform** and **Price**, and logger tables also add
**LoTW**:

```markdown
| Name | What it is | Platform | Price | LoTW | Link |
|---|---|---|---|---|---|
| Log4OM 2 | Full station log with digital mode integration | Windows | Free | Yes | https://www.log4om.com/ |
```

Rules:

- **Name** is the real name of the site or tool, not the bare URL.
- **What it is** is one short line saying what it does. Not marketing text.
- **Link** is a bare URL, no `[...]()` around it. GitHub makes it clickable.
- **Platform**: `Windows`, `Linux`, `macOS`, `Web`, `Android`, `iOS`, or a few
  of them separated by commas.
- **Price**: `Free`, `Paid`, or `Free / Paid` when there is both.
- **LoTW**: `Yes`, `No`, or `Via integrations`.
- Do not break the row over several lines. One row, one line.

## Where does my link go?

| File | Content |
|---|---|
| [cw.md](cw.md) | Anything CW specific: keys, books, online trainers, games, training software, decoders |
| [software.md](software.md) | General ham software: logging, DX spotting, propagation, rig control |
| [tools.md](tools.md) | Calculators, maps and other small online tools |

If nothing fits, open an issue and we will talk about a new file or section.

## Before you open the PR

- [ ] The link works and is free to open (no login wall, no paywall).
- [ ] The link is not already in the list.
- [ ] It is about ham radio.
- [ ] One link per Pull Request, if possible. It makes review faster.

A bot checks every Pull Request for dead links. If it fails, look at the log —
it is usually a typo in the URL.

# Alex's notebook

Based on the Zettelkasten method by Luhmann inspired by [How to take smart notes](https://fortelabs.co/blog/how-to-take-smart-notes/?utm_source=hackernewsletter&utm_medium=email&utm_term=fav). Plain-text format inspired by The Pragmatic Programmer.

## Aims

The main aim of this repo is to be a safe place for me to collect and store notes for future use. One of the main take aways from _how to take smart notes_ is that writing isn't the result of thinking, it is **where it happens**.

Each piece of information has been written in my own words, another core principle of good note taking along with linking between _cards_ and thoughful categorisation.

## Flow

1. Write notes on paper while reading/learning/thinking (no highlighting or copying)
2. Go through the notes, thinking about links to previous notes and in what way this new information will fit into my current system.
3. Write down the keywords and links from this new information to your existing information.
4. Add the new information to my _box_.
5. Add clickable links to relevent _cards_.
6. Commit changes to repo.

## File system

There are top-level directories which present are _contexts_. They're coded by a simple numeric ID (`1-cooking/`).

A _context_ is **not** a _category_. This is important. Contexts are collections of notes, grouped by _where I might use them_, not a mearly taxonomic topic. These might sometimes be equivelent in practice, but the difference is important to know.

Files under that directory use their filenames as a reference system (`1a-five-flavours.md`). The `1` represents the category and the `a` shows that it's a related or sub-topic.

We simply nest files this way using an alphabetic system (`1aa-salt.md`, `1ab-bitter.md` and so on).

## Tree

```
├── 1-cooking
│   ├── 1a-five-flavours.md
│   ├── 1aa-salt.md
│   └── 1ab-bitter.md
├── 2-functional-prog
│   ├── 2a-fp-fundamentals.md
│   ├── 2aa-side-effects.md
│   ├── 2ab-seperation.md
│   ├── 2ac-composition.md
│   ├── 2aca-first-class-functions.md
│   ├── 2ad-immutability.md
│   ├── 2ada-thread-safety.md
│   ├── 2ae-memoization.md
│   ├── 2af-higher-order-functions.md
│   ├── 2ag-currying.md
│   ├── 2ah-partial-application.md
│   └── 2aha-arity.md
├── 3-terminal-cmds
│   └── 3a-add-line-to-file.md
└── README.md
```
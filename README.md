# 📝 Notes CLI Application

Notes CLI Application built during the [Workshop Introduction to Node.js, v3](https://frontendmasters.com/workshops/node-js-v3/) by [Scott Moss](https://twitter.com/scotups).

**Participation & Enjoyment By:** [Pieter Herman](https://twitter.com/bepieter), a passionate learner who dived into the Awesome Workshop Introduction to Node.js, v3.

**Led & Inspired By:** The one and only [Scott Moss](https://twitter.com/scotups). His wisdom, insights, and engaging teaching style made this journey an unforgettable learning experience.

## Contents

- [What's This?](#whats-this)
- [Why?](#why)
- [My Experience](#my-experience)
- [Want to Dive Deeper?](#want-to-dive-deeper)
- [How to use](#how-to-use)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Commands](#commands)
    - [Options](#options)

## What's This?

A command-line note-taking tool, created during the workshop. Simple, like the best ideas. Made with Node.js, because why not?

## Why?

Because jotting down ideas in the terminal is cool, and because learning through workshops like this one helps shape better developers.

## My Experience

Engaging and insightful. Thanks to Scott Moss's captivating workshop, I've gained valuable insights into Node.js.

## Want to Dive Deeper?

- [Check Here The Workshop Introduction To Node.js, v3 (Unedited Replay)](https://frontendmasters.com/workshops/node-js-v3/)
- [Learn More About the Man Behind the Magic: Scott Moss](https://github.com/Hendrixer)

## How to use

### Installation

1. Clone the repo

2. `bash npm install && npm link `

### Usage

```bash
node app.js --help
```

### Commands

```bash
  note new <note>     Create a new note
  note all            get all notes
  note find <filter>  get matching notes
  note remove <id>    remove a note by id
  note web [port]     lanch website to see notes
  note clean          remove all notes
```

#### Options

```bash
      --help     Show help                    [boolean]
      --version  Show version number          [boolean]
  -t, --tags     tags to add to the note      [string]
```

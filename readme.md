# General Standards

## Coding standard

I think that the best way to explain something is to show it (when phisically possible), so:

```javascript
    const banana = require('banana')
    const {foo} = require('foo')
    const veryLongNameUsingCammelCase = require('longName')

    let bananer = (name) => {
        console.log(`${name} turned into a banana`)
    }

    module.exports = {
        bananer
    }
```

This is a good example for NodeJS (take note on the lack of semicolons and es6 usage).
None of this crap is mandatory, but it would make me happy to see contributions written this way.

## Git commit message standards

Here are some guidelines for contributors (myself included)
---

Take the following in consideration:

- One **should** commit when something can be described
- One **may** commit when more than one thing can be described
- One **should not** commit when there's nothing important happening

## __Examples__

You made some changes to a file, fixing a typo and turning some tabs into spaces.
The commit message **may** describe what __the commit__ does, as in:

`Fix typo on foo.js | Convert tabs into spaces`

Note that it didn't say "Fixed typo", but "Fix" instead. The message describes the commit, not your actions.

In this particular case, we have two messages and separate then by using a pipe ("|"). It's better than using a coma or semicolon, because you may write a long message and need those.

## __Emojis__

The folowing emojis are welcome:

:hammer: - For refactoring

:pill: - For bug fixes

:neckbeard: - For license related stuff 


# 360 Labs Code Style Guide

## General Code Guidelines

- 4 space hard tabs (1 tab character = 4 spaces)
- All js/ts files use single quotes
- Callbacks are always ES6 fat arrow functions (`fs.readFile('myfile.txt', (err,buf) => console.log(buf));`)

## Angular
- One component, one purpose
- File names are kabob-case: `patient-detail-chart.ts`
- Private variables are not prefixed with an underscore (`privateVar` not `_privateVar`)
- Angular projects use scss (`ng new --style scss my-project`)
- Never use `document.getElementById()` in an Angular project
- Don't use `setTimeout()` in an Angular project unless absolutely necessary


## Node
- Node file names are camel-case: `patientDetailChart.ts`

## Git
- One commit, one purpose
- Commit messages should be short (<40 chars) and succinct
- Commit messages should start be a sentence (start with a capital and end with a period)
- Commit messages should be describe what you did in past-tense: `Fixed promise rejection in save().`
- If you need more room for the message, use multiple `-m` options:
`git ci -m "First message." -m "Second message."`

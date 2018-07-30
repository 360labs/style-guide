# 360 Labs Code Style Guide

- 4 space hard tabs (1 tab character = 4 spaces)
- All js/ts files use single quotes
- Angular file names are kabob-case ('patient-detail-chart.ts')
- Node file names are camel-case ('patientDetailChart.ts')
- Angular private variables are not prefixed with an underscore (`privateVar` not `_privateVar`)
- Angular projects use scss (`ng new --style scss my-project`)
- Callbacks are always ES6 fat arrow functions (`fs.readFile('myfile.txt', (err,buf) => console.log(buf));`)
- Never use `document.getElementById()` in an Angular project
- Don't use `setTimeout()` in an Angular project unless absolutely necessary
- Angular: One component, one purpose
- Git: One commit, one purpose
- Git commit messages should be short (<40 chars) and succinct


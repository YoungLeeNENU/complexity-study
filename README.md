## A complexity study on [react](https://github.com/facebook/react)

- Using code-maat, python and d3.js 
- *Data from 2017/09/27, since react version 16.0.0 released*

### Checkout react version
```bash
git checkout `git rev-list -n 1 --before="2017-09-27" master`
```

### Output git logs
```bash
git log --pretty=format:'[%h] %an %ad %s' --date=short --numstat --before=2017-09-27 > react_evo.log
```

### Count the lines by commit 9ce135f86
```bash
cloc 9ce135f86 --by-file --csv --quiet --report-file=maat_lines.csv
```

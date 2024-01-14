# [Logseq](https://logseq.com) task completion tracker plugin

Original extension by DimitryDushkin with description [here](https://github.com/DimitryDushkin/logseq-plugin-task-check-date).

In this fork, just the date format for the 'completed' property has been changed to a plain text 'yyyyMMdd', as Logseq currently does not handle properties with programmatically inserted links correctly.

You can use the date in plain text format 'yyyyMMdd' in queries, comparing it with :today and other built-in variables.

## How to release
1. `yarn build`
2. `git commit -am "up build" && git push`
3. Make release in Github.

This Contribution Policy is applied to all projects within the [Tsoding Github Organization][tsoding-github]

### 1. Neglected Pull Requests

If the Reviewer's requests are not addressed by the Submitter within 2 weeks the Pull Request may be deemed neglected and closed without any further discussion.

### 2. Pull Request Size Limitation

The Pull Request size is calculated using the following formula:

```
Size = Max(Added_Lines, Removed_Line)
```

If `Size > 300` the Pull Request may be closed as "Too big" without any further discussion. If the limitation is not enough see [Continuous Decomposition](#3-continuous-decomposition) section.

### 3. Continuous Decomposition

As a Contributor, when you prepare a PR:

- make as many changes as you can according to the [PR size limitation](#2-pull-request-size-limitation),
- make sure that the code is compilable and the application is usable,
- create TODOs right in the code for the unfinished work,
- format your TODOs according to the [Snitch TODO format][snitch-todo-format]
- submit PR with the unfinished work and TODOs,
- TODOs will be converted to separate issues by the Reviewer

### 4. Issue Detalization

Issues with vague descriptions like "Application does not work", "I don't understand anything", etc, will be closed as "To vague" without any further discussion. Provide as many details as possible.

### 5. Policy Changes

The Policy is not final and constantly changes based on the precedents during development. To stay updated on the Policy changes [Start Watching](https://help.github.com/en/articles/watching-and-unwatching-repositories#watching-a-single-repository) this repo.

[snitch-todo-format]: https://github.com/tsoding/snitch#unreported-todo
[tsoding-github]: https://github.com/tsoding

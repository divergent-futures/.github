# .github

This special repository does two jobs for the whole **Divergent Futures**organisation.

## 1. The organisation profile

`profile/README.md` is the page shown at[github.com/divergent-futures](https://github.com/divergent-futures).

> **This only works if the repository is named exactly `.github`.**A repo named anything else — `dotgithub`, `divergent-futures-dotgithub`,`github` — will not render, and the organisation page falls back to a barerepo list.

That page is where the hierarchy is drawn explicitly: parent at the top, thechannels beneath it, projects grouped under each. GitHub can't nest anything, sothis is the one place the structure is stated rather than implied. **When achannel or project is added, update it here.**

## 2. Default community health files

Every file below is **inherited by every repository in the organisation thatdoesn't have its own copy**. Write it once here, and all repos get it.

| File | What it does |
| --- | --- |
| `CONTRIBUTING.md` | Shown when someone opens an issue or PR |
| `CODE_OF_CONDUCT.md` | Linked from the community tab of every repo |
| `SECURITY.md` | Shown under the "Security" tab; tells people how to report privately |
| `ISSUE_TEMPLATE/` | The forms people see when opening an issue |
| `PULL_REQUEST_TEMPLATE.md` | Pre-fills the PR description box |

A repo that needs different rules just adds its own copy of that one file — itoverrides the default without affecting anything else.

**`LICENSE` is not inherited.** Licences have to live in each repository. That'sa GitHub rule, not a choice.

## The naming convention this org uses

Every repository is prefixed with **what it is**, because GitHub sorts reposalphabetically and the prefix decides how the list groups itself:

| Prefix | Division | Means |
| --- | --- | --- |
| `hw-` | Hardware | Physical things, built from documentation |
| `app-` | Applications | Software a stranger installs and runs |
| `lab-` | Research | Models, calculators, analyses — produces answers, not tools |
| `ops-` | Studio | The machinery that runs Divergent Futures, websites included |

**Placing a new project — first match wins:**

1. Does it exist physically, or is it a design for something that will? → `hw-`
2. Would a stranger download and run it? → `app-`
3. Does its output answer a question rather than perform a task? → `lab-`
4. Does it exist so the studio can operate? → `ops-`

If two apply, pick the one that describes *who uses it*.

**Channel is a topic, not a prefix** — `divergent-futures`,`humans-in-space`, `living-on-the-spectrum`, `cosmos`. A repo can carry several.That way the list groups by division when you scan it, and by channel when youfilter it, and a fifth channel costs one new topic string rather than a rename.

Full reasoning and the scaling rules live in `GITHUB-STRUCTURE.md` alongside thewebsites repo.

## Editing

These are plain markdown files. Change one, commit, and every repo in theorganisation picks it up immediately — there's nothing to deploy.

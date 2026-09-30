# Contributing

Thanks for taking an interest in Vectros. Before you open anything, two facts about how these
repositories work.

## The code repositories are release mirrors

The code repositories in this organization (every repository except `vectros-feedback` and
`.github`) are developed in a private repository and published here at each release. Every commit
is a snapshot of a release, so the history here is a list of releases, not the day-to-day
development history. At each release the published files are regenerated from the source, so a
change to a published file made only here is overwritten.

Two consequences:

- **Issues go to [vectros-feedback](https://github.com/vectros-ai/vectros-feedback).** Bug reports
  and feature requests for every Vectros repository are tracked there, not in the repository you are
  reading.
- **A pull request cannot be merged here as it stands,** because the next release would overwrite
  it. If you have a fix in mind, describe it in an issue on vectros-feedback and attach the patch
  or diff. That is the way to get it considered.

## Where to go

| You want to | Go to |
| --- | --- |
| Report a bug or ask for a feature | [Open an issue on vectros-feedback](https://github.com/vectros-ai/vectros-feedback/issues/new/choose) |
| Report a security vulnerability | Follow the [security policy](https://github.com/vectros-ai/.github/blob/main/SECURITY.md). Do not open a public issue. |
| Learn how to use Vectros, or find an answer to a question | [docs.vectros.ai](https://docs.vectros.ai) |

## Writing a useful issue

- Name the package or app and its version.
- Give a minimal reproduction.
- Use synthetic data only.
- Leave out API keys, tokens, and any real customer data.

## Forking

The code repositories are Apache-2.0 licensed, and the reference apps are built to be forked. Fork
one, change it, and ship it.

## Conduct

Everyone taking part in these repositories is expected to follow the
[code of conduct](https://github.com/vectros-ai/.github/blob/main/CODE_OF_CONDUCT.md).

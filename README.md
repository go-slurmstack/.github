# .github

Organisation profile of [go-slurmstack](https://github.com/go-slurmstack) and
its Renovate runner.

- `profile/README.md` is shown on the organisation page.
- `config.js`, `default.json` and `.github/workflows/renovate.yml` run Renovate
  for this organisation only. The runner needs a `RENOVATE_TOKEN` repository
  secret; without it the nightly run fails in seconds, by design (see the
  comment in `renovate.yml`).
- `.github/workflows/ci.yml` validates those files on every pull request.

# Contributing to VHT.ai

Thank you for your interest in VHT.ai. This page explains what we accept from external contributors and how to submit it.

## What we accept

| Contribution | How |
|---|---|
| **Bug reports** | Open an issue in [`community`](https://github.com/virtual-healthcare-technologies/community/issues/new/choose) using the *Bug report* template. |
| **Feature requests** | Same repo, *Feature request* template. |
| **Translation fixes** | Same repo, *Translation fix* template. The app ships in 7 UI languages; wrong, awkward or missing strings are always welcome. A broader translation program is coming soon. |
| **Questions and ideas** | [Community Discussions](https://github.com/virtual-healthcare-technologies/community/discussions). |
| **Security reports** | Email **security@vht.ai** only. See [SECURITY.md](./SECURITY.md). |
| **Documentation fixes to these public repos** | Pull requests are welcome for typos and clarity in the `.github` and `community` repositories. |

## Code contributions

The VHT.ai application is not open source. Code contributions to the product are **by invitation only**. If you would like to work with us, email contact@vht.ai with a short note about your background and interests.

## The PHI rule

**Never include personal health information (PHI)** — yours or anyone else's — in an issue, discussion, pull request, screenshot or log. This includes names together with health details, lab values, medications, diagnoses, dates of birth, device identifiers and similar data. Every issue template begins with a required checkbox confirming this.

If you need to share sensitive details to reproduce a problem, email contact@vht.ai and we will arrange a private channel. Maintainers will remove PHI from public posts and label the item `phi-removed`.

## Developer Certificate of Origin (DCO)

All pull requests must be signed off. By signing off you certify the [Developer Certificate of Origin 1.1](https://developercertificate.org/): that you wrote the contribution or otherwise have the right to submit it under the repository's license.

Add a `Signed-off-by` line to every commit, either with `git commit -s` or by writing it yourself:

```
Signed-off-by: Your Name <you@example.com>
```

Use the name and email on your GitHub account (a GitHub `noreply` address is fine). Unsigned commits will be asked to be amended before merge.

## Pull request guidelines

1. Keep changes small and focused.
2. Fill in the pull request template; the first checkbox is the PHI confirmation.
3. Follow the [Code of Conduct](./CODE_OF_CONDUCT.md).
4. Pull requests are merged by squash only; the title becomes the commit message, so make it descriptive.

## License

Content in the `.github` and `community` repositories is licensed under [CC BY 4.0](./LICENSE). By contributing you agree your contribution is licensed the same way.

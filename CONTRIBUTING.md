# Contributing Guidelines

- Create a new git branch specific to your change (as opposed to making your commits in the master branch).
- Don't put multiple fixes/features in the same branch / pull request.
- First line of your commit message should start with present-tense verb, be 50 characters or less, and include the
relevant issue number(s) if applicable. Example: Ensure proper PLUGIN_PATH behavior. Refs #428. If the commit completely
fixes an existing bug report, please use Fixes #585 or Fix #585 syntax (so the relevant issue is automatically closed
upon PR merge).
- Make sure that new features are configurable using a variable (eg. `DISPLAY_CHUCKNORRIS_ADVICE`). Should default to
`False`, so users will not get any surprises when upgrading.
- Somewhat related, make sure changes do not break backwards compatibility, especially with regards to settings.
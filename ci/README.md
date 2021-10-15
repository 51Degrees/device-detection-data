# API Specific CI/CD Approach
This API does not produce packages so use `tag-repository` approach as described in `common-ci` `README.md`.

Differences:
- There is no `create-packages` pipeline, but `tag-repository` pipeline.
- `deploy` pipeline only push tag and branch to GitHub.

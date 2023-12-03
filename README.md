name: Example
uses: m1orez/m1orez@latest
with:
  template: repository
  filename: m1orez.repository.svg
  token: ${{ secrets.METRICS_TOKEN_WITH_SCOPES }}
  user: m1orez
  repo: m1orez
  plugin_lines: yes
  plugin_followup: yes
  plugin_projects: yes
  plugin_projects_repositories: m1orez/m1orez/projects/1

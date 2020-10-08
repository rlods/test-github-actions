# GitHub Actions Tests

Trigger workflow from command line

curl \
  -X POST \
  -H "Accept: application/vnd.github.v3+json" \
  -H "Authorization: token ..." \
  -d '{"event_type":"generate"}' \
  https://api.github.com/repos/rlods/test-github-actions/dispatches
  

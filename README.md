# actions-webhook

```
curl -H "Authorization: token <YOUR_GITHUB_TOKEN>" \
    --request POST \
    --data '{"event_type": "<YOUR_EVENT_TYPE>"}' \
    https://api.github.com/repos/<YOUR_GITHUB_USER>/<YOUR_GITHUB_REPO>/dispatches
```

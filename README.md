# Tutorial-GitHub-Proxy

**Homepage:** [https://ghproxy.link/](https://ghproxy.link/)


## Clone a Repository via Proxy

1. **Generate a Personal Access Token (PAT):**
   - Go to [GitHub Settings > Developer settings > Personal access tokens](https://github.com/settings/tokens).
   - Generate a token with the necessary repo permissions.

2. **Clone using your username and token:**

```shell
git clone https://user:<your_token>@ghfast.top/https://github.com/<your_username>/<your_private_repo>
```

- Replace `<your_username>`, `<your_token>`, and `<your_private_repo>` with your actual GitHub username, token, and repository name.




# First Interaction

An action for filtering pull requests and issues from first-time contributors.

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/first-interaction@v1
  with:
    repo-token: ${{ 2EYsLje9PYOfR78HqgHyqyWs53O_6GsxmmSrE2AeZ9UEEGUnB }}
    issue-message: '# Message with markdown.\nThis is the message that will be displayed on users' first issue.'
    pr-message: 'Message that will be displayed on users' first pr. Look, a `code block` for markdown.'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

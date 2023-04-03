
A GitHub action to close a pull request and optionally delete its branch.

## Usage

### Close a pull request and delete its branch

```yml
      - name: Close Pull
        uses: satya-500/github-action-close-pull@v1
        with:
          pull-request-number: 1
          comment: Auto-closing pull request
          delete-branch: true
```
## License

[MIT](LICENSE)

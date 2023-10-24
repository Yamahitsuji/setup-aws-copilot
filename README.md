# setup-aws-copilot
Set up your GitHub Actions workflow with a specific version of AWS Copilot

## Example
```
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - name: Setup AWS Colipot
        uses: Yamahitsuji/setup-aws-copilot@v1
        with:
          version: # [Option] copilot version (Default: latest)
      - name: Other actions
        run: ~~~
```

## References
- [AWS Colilot Versions](https://github.com/aws/copilot-cli/releases)

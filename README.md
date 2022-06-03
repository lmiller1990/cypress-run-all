# Run

```
yarn install
yarn cypress run --e2e --headed --no-exit
```

Problem is we close the browser after each spec - unless `--no-exit` - then we do not. So it hangs after the first spec.

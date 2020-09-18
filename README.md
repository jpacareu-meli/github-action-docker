# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `entryPoint`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage
```yml
uses: jpacareu-meli/github-action-docker@v1
with:
  entryPoint: 'Mona the Octocat'
```

## Release

  > $ git add .

  > $ git commit -m "My commit message"

  > $ git tag -a -m "My release message" v1

  > $ git push --follow-tags
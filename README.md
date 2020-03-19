![.github/workflows/main.yml](https://github.com/mm0202/sandbox_github-action_js-type/workflows/.github/workflows/main.yml/badge.svg)

# sandbox_github-action_js-type
 JavaScriptタイプのGitHubアクションのトライアル

trace from [JavaScript アクションを作成する](https://help.github.com/ja/actions/building-actions/creating-a-javascript-action)

## Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'
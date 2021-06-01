# Sound//Infra GitHub Action
Automatically publish to your domain with a `git push`.

## Inputs
### `publishDomain`
***Required*** A domain, Powered by Sound//Infra.

### `publishDirectory`
The contents of this directory will be published. Default `"public"`.


## Example usage
uses: soundinfra/soundinfra-gh-action@v0.1
with:
    publishDomain: 'example.com'


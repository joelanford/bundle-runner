# Bundle Runner

Bundle Runner is a Helm chart that dynamically runs an operator given a bundle and an optional index image to inject the bundle into.

## Example Usage

```console
$ git clone https://github.com/joelanford/bundle-runner
$ helm install bundle-run-operator bundle-runner -f bundle-runner/example.overrides.yaml
```

# Simple iOS sample app with bitrise.yml

To run this project with `bitrise` just install it: https://github.com/bitrise-io/bitrise/releases

Then to run the `test` workflow (you can find it in the `bitrise.yml` file)
just call `cd` into this directory and call `bitrise run test`.

You can also `bitrise run analyze` and `bitrise run archive` - check
the `bitrise.yml` for all the defined workflows.


## How to run it on [bitrise.io](https://www.bitrise.io)

You have to install the `bitrise` CLI first. You can do that
by adding a Bash Script Step on bitrise.io and then call:

```
bash ./install_bitrise_cli.sh
```

After this you can use the `bitrise` CLI just like you would
on your own Mac.

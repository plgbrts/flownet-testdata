# Testdata for `flownet`

This repository contains some open example data to be used by
https://github.com/equinor/flownet

If you only want to download the data, you can run
```bash
git clone --depth 1 https://github.com/equinor/flownet-testdata
```
That will download the content to a folder called `flownet-testdata`.

## Upload of data

Remember that GitHub does not allow files larger than 100 MB, and will give a warning
when pushing files larger that 50 MB. There is also a repository limit on 100 GB.

You can find files larger than e.g. 50 MB, recursively from your current directory, by
running
```bash
find . -type f -size +50M
```

Occasionally it might be decided to remove repository history and "start fresh"
to keep repository size as small as possible.

## License / Acknowledgements

- The [Norne input model](./norne/input_model) comes from the OPM project, where it is available under the [Open Database License](http://opendatacommons.org/licenses/odbl/1.0/).

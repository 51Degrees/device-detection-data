# Device Detection data files (archived)

This repository is archived and kept read-only. Its free data file, test
evidence and CI files are now in the `device-detection` folder of the
[data](https://github.com/51Degrees/data) repository. The `metrics` folder,
which held the charts for the device data quality page, was not moved and
stays here as it was.

## Get the free data files

The data repository lists each free data file as a link, and a script
downloads the files into place. No License Key is needed. To clone the
repository and download every free file in one command, run this.

```sh
git clone https://github.com/51Degrees/data.git && data/get-data-files.sh
```

In PowerShell, run `./get-data-files.ps1` in the `data` folder instead. The
[data README](https://github.com/51Degrees/data#get-the-data-files) says how
to download only some files, or the newer versions of files you already have.

## Examples and APIs

The examples and APIs that used these files are now in these repositories.

- [C and C++](https://github.com/51Degrees/51degrees-cxx)
- [.NET](https://github.com/51Degrees/51degrees-dotnet)
- [Go](https://github.com/51Degrees/51degrees-go)
- [Java](https://github.com/51Degrees/51degrees-java)
- [Nginx](https://github.com/51Degrees/51degrees-nginx)
- [Node.js](https://github.com/51Degrees/51degrees-node)
- [PHP](https://github.com/51Degrees/51degrees-php)
- [Python](https://github.com/51Degrees/51degrees-python)
- [Rust](https://github.com/51Degrees/51degrees-rust)
- [Varnish](https://github.com/51Degrees/51degrees-varnish)

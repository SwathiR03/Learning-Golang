1. Uninstall the existing version(if any)
To download a go version you will first need to uninstall the original version, if any. To uninstall, delete the /usr/local/go
directory by running `$ sudo rm -rf /usr/local/go`.

2. Install the new version
Go to the [downloads](https://go.dev/dl/) page and download the binary release that works on your system.
I use Linux Mint(Debian).

3. Extract the archive file
To extract the archive file, run `$ sudo tar -C /usr/local -xzf /home/<username>/Downloads/go1.27.0.linux-amd64.tar.gz`.

4. Make sure that your PATH contains `/usr/local/go/bin`
$ echo $PATH | grep "/usr/local/go/bin"

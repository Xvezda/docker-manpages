# manpages

Trying to fill missing pieces from the original [manpages by petrem](https://hub.docker.com/r/petrem/manpages).

[Docker hub](https://hub.docker.com/r/xvezda/manpages)

## Usage

I'm using `extman` which is shorthand for _extra manual_ or _extended manual_ or whatever..

```sh
echo "alias extman='docker run --rm -it xvezda/manpages man'" >> ~/.bash_profile
```

will do the trick.

```sh
extman strace  # Read strace manual on any platform
```

## License

@Xvezda [WTFPL](http://www.wtfpl.net/) License


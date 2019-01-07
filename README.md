# jet

```
     __!__
______(_)______
    !  !  !
```

jet is a small utility for speeding up ssh connections.

## Usage

After typing `jet <pattern>`, the program will look for matches on `known_hosts` file. In case of single match the ssh connection will be immediately attempted, otherwise a choice will be requested.

![jet](https://media.giphy.com/media/DqZMx4VNKvi8uhdCbm/giphy.gif)

## History

There's a little story behind this tool: I wrote the first perl version in 2007, while I was working as a DBA. At that time, I had a Macbook and hundreds of servers to connect to every day, so perl was a reasonable choice.

Then I changed my job and lost the source code, discovering it again twelve years later while looking to an old backup disk.

And since now I work mainly on Windows, I decided to rewrite it for portability: I initially thought about using Go, but after struggling for some time I opted for python.

## Installation

### Windows

Just get the latest release from GH and put `jet.exe` somewhere in your `PATH`.

### MacOS

From terminal:

`curl -o /usr/local/bin/jet https://raw.githubusercontent.com/emyl/jet/master/jet; chmod +x /usr/local/bin/jet`

## Contributing

Contributions are welcome!

## License

MIT

# grafgrep

gragrep is super simple and small a Rust implementation built for educational purpose.

## Installation

Use the package manager [cargo](https://crates.io/) to install grafgrep.

```bash
cargo install grafgrep
```

## Usage

```bash
# file.txt contains 
# Rust is a good tool
# and should be ubberusted

# returns 'and should be ubberusted'
grafgrep rust file.txt

# returns '
# Rust is a good tool'
# and should be ubberrusted
IGNORE_CASE=1 grafgrep rust file.txt
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
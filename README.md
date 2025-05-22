

## Building Kriptokoyn

### Dependencies

- GCC 7.1 or later
- CMake 3.16 or later
- Boost 1.64 or later
- OpenSSL 1.0.1 or later
- Berkeley DB 4.8 or later

### Build Instructions

```bash
# Clone the repository
git clone https://github.com/kriptokoyn/kriptokoyn.git
cd kriptokoyn

# Create build directory
mkdir build
cd build

# Configure and build
cmake ..
make -j$(nproc)
```

## Running Kriptokoyn

```bash
# Start the daemon
./src/kriptokoynd

# Start with GUI
./src/qt/kriptokoyn-qt
```

## Development

Kriptokoyn is open source and welcomes contributions. Please follow our [contribution guidelines](CONTRIBUTING.md) when submitting pull requests.

## License

Kriptokoyn is released under the terms of the MIT license. See [COPYING](COPYING) for more information.

## Security

For security concerns, please contact security@kriptokyng.com

## Community

- Website: [kriptokyng.com](http://kriptokyng.com/)
- Discord: [Join our community](https://discord.gg/kriptokoyn)
- Twitter: [@kriptokoyn](https://twitter.com/kriptokoyn)

## Support

For support and general inquiries, please visit our [support portal](http://kriptokyng.com/support) or email support@kriptokyng.com

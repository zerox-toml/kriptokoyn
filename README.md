# Kriptokoyn

Kriptokoyn is a modern cryptocurrency built on the Bitcoin Core codebase, offering enhanced features and improved performance. Visit [kriptokyng.com](http://kriptokyng.com/) for more information.

## Key Features

- **Faster Block Times**: 2-minute block intervals (vs Bitcoin's 10 minutes)
- **Larger Block Size**: 8MB blocks for improved scalability
- **Lower Fees**: Optimized fee structure for cost-effective transactions
- **Modern Features**: All BIPs enabled from genesis
- **Frequent Halvings**: Halving every ~2 years (105,000 blocks)

## Technical Specifications

- **Block Time**: 2 minutes
- **Block Size**: 8MB
- **Max Block Weight**: 8,000,000
- **Max SigOps per Block**: 160,000
- **Coinbase Maturity**: 50 blocks
- **Network Port**: 18333
- **Halving Interval**: 105,000 blocks

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

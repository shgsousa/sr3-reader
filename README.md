# SR3 Reader

A modern, object-oriented Python library for reading Computer Modelling Group Ltd. (CMG) binary output files.

## About This Project

This project is a fork of [nikolai-andrianov/sr3_reader](https://github.com/nikolai-andrianov/sr3_reader), which provides excellent utilities for reading and visualizing CMG simulation output files. We are grateful to Nikolai Andrianov for the original work and solid foundation.

## Project Status: Under Active Refactoring

This project is currently being refactored with the following goals:

- **🏗️ Modern Build System**: Migrating to a proper Python package structure with `pyproject.toml` and Poetry for dependency management
- **📦 PyPI Distribution**: Making the package installable via `pip install sr3-reader`
- **🎯 Object-Oriented Design**: Refactoring the codebase from procedural to object-oriented architecture for better maintainability and extensibility
- **🧪 Testing & CI/CD**: Adding comprehensive test coverage and automated testing workflows
- **📚 Enhanced Documentation**: Improving documentation and adding type hints for better developer experience

## Current Features

The library provides Python utilities to read and visualize the output of Computer Modelling Group Ltd. (CMG) simulation software, enabling:

- Reading CMG binary output files (`.sr3` format)
- Data extraction and manipulation for analysis workflows
- Support for automated sensitivity studies and history matching
- Integration with popular Python data science libraries

## Installation

### Current (Development)

```bash
# Clone this repository
git clone https://github.com/yourusername/sr3-reader.git
cd sr3-reader

# Install in development mode
pip install -e .
```

### Future (PyPI - Coming Soon)

```bash
pip install sr3-reader
```

## Examples

The `examples/` directory contains sample data files and demonstration scripts:

- **Coreflood Geochemistry**: `plot_coreflood_geochem.py` - Visualization of 1D coreflooding experiment results
- **Cartesian Grid**: `plot_cartesian_grid.py` - 3D visualization of reservoir simulation data

## Roadmap

- [ ] Complete object-oriented refactoring
- [ ] Add comprehensive test suite
- [ ] Publish to PyPI
- [ ] Enhanced API documentation
- [ ] Performance optimizations
- [ ] Support for additional CMG file formats

## Contributing

We welcome contributions! Whether you're interested in:

- 🐛 Bug fixes and improvements
- ✨ New features
- 📖 Documentation enhancements  
- 🧪 Testing and quality assurance
- 🔍 Code reviews

Please feel free to open an issue or submit a pull request.

## License

MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

Since the internal format for binary SR3 files is not officially documented by CMG, interpretation of data fields may not always be complete or accurate. While the code has been tested on various datasets, **NO WARRANTY OF ANY KIND IS PROVIDED** with this software.

# Markdown to JSON Processor

PROPRIETARY AND CONFIDENTIAL

This software is the proprietary information of Ubu English LLC. All rights reserved.
Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited.

## Project Overview

A Python-based markdown processing system that converts markdown documents into structured JSON while preserving formatting and semantic relationships. Designed for batch processing of small to medium-sized documents to prepare training data for Large Language Models (LLMs).

## Documentation

- [Processing Guide](./PROCESSING_GUIDE.md) - Comprehensive guide to markdown processing rules and output structure
- [Version 1.0 Documentation](./v1.0/docs/) - Single-pass implementation details
- [Version 2.0 Documentation](./v2.0/docs/) - Two-pass implementation details

This repository contains two implementations of the processor:

### [Version 1.0](./v1.0/README.md) - Single-Pass Implementation
- Uses a state machine approach
- Processes documents in a single pass
- Memory efficient
- Good for streaming input
- Early development stage (passes 2/6 test cases)
- Limited to basic document structures
- Basic batch processing support
- [View Documentation](./v1.0/docs/)

### [Version 2.0](./v2.0/README.md) - Two-Pass Implementation
- Uses a two-pass processing approach
- Better structure handling
- Enhanced validation
- Improved schema compliance
- Under active development (no test cases passing yet)
- Enhanced batch processing with validation
- [View Documentation](./v2.0/docs/)

## Version Comparison

| Feature                  | v1.0 (Single-Pass)        | v2.0 (Two-Pass)           |
|-------------------------|---------------------------|---------------------------|
| Status                  | Early Development (2/6 tests) | In Development           |
| Processing Approach     | State Machine             | Two-Pass Analysis        |
| Memory Usage           | Low (streaming)           | Higher (full document)   |
| Structure Understanding | Basic                     | Enhanced                 |
| Schema Validation      | Limited                   | Strict                   |
| Best For               | Simple, small documents    | Medium-sized documents with complex structure|
| Batch Processing       | Basic implementation      | Enhanced with validation |

## Development Status

- **v1.0**: Early Development
  - Passes 2 out of 6 test cases
  - Handles basic document structures
  - Limited validation capabilities
  - Active development needed for complex cases
  - Basic batch processing implemented

- **v2.0**: Under development
  - First pass implementation complete
  - Second pass in progress
  - Testing framework established
  - Enhanced batch processing with validation

## Repository Structure

```
Extraction_Pipeline/
├── README.md           # This file
├── .gitignore         # Git ignore patterns
├── v1.0/              # Single-pass implementation
│   ├── README.md      # v1.0 specific documentation
│   ├── docs/          # Detailed documentation
│   ├── md_processor/  # Core processor code
│   ├── schemas/       # JSON schemas
│   └── tests/         # Test suite
└── v2.0/              # Two-pass implementation
    ├── README.md      # v2.0 specific documentation
    ├── docs/          # Detailed documentation
    ├── md_processor/  # Core processor code
    ├── schemas/       # JSON schemas
    └── tests/         # Test suite
```

## Getting Started

Each version has its own setup and usage instructions:
- [v1.0 Setup and Usage](./v1.0/README.md)
- [v2.0 Setup and Usage](./v2.0/README.md)

## Contributing

- Follow the version-specific development guides
- Each version maintains its own test suite
- Cross-version testing available for comparison

## License

This is proprietary software. All rights reserved.
No license is granted for any use without explicit permission.

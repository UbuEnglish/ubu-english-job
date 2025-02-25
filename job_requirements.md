# Job Requirements - Document Processing Pipeline

## Position Overview

**Title**: Senior Python Developer - Document Processing Pipeline

**Project Scope**: 75-95 hours
**Timeline**: 4-6 weeks
**Development Approach**: Modern development practices with AI assistance

## Project Overview

Develop and enhance a Python-based markdown processing system that converts markdown documents into structured JSON for LLM training data preparation. The project is well-structured with comprehensive documentation and clear architectural patterns.

## Key Responsibilities

- Complete v1.0 implementation
- Develop v2.0 with enhanced features and validation
- Implement comprehensive test suite
- Maintain high code quality and documentation
- Collaborate with team using modern development practices

## Required Skills

- 3+ years Python development experience
- 1+ years experience with modern development tools including AI assistants
- Proficiency in:
  - Markdown processing
  - JSON schema validation
  - Test-driven development (pytest)
  - Git version control
  - Modern coding assistants

## Technical Experience

- Demonstrated ability to:
  - Implement complex text processing systems
  - Design and validate JSON schemas
  - Write comprehensive test suites
  - Maintain clear documentation
  - Review and optimize code quality

## Nice to Have

- Experience with LLM training data preparation
- Knowledge of document processing pipelines
- Background in educational technology
- Experience with multiple development environments

## Project Environment

- Well-structured codebase
- Clear architectural patterns
- Comprehensive test suite design
- Modern development tools and practices

## Development Approach

- Efficient implementation using modern tools
- Strong focus on code quality
- Comprehensive testing
- Continuous documentation

## Technical Approach and Decisions

### Established Approaches
The project currently has two implementation approaches:
1. **Single-Pass (v1.0)**:
   - State machine-based processing
   - Memory efficient
   - Good for streaming
   - Currently passes 2/6 test cases

2. **Two-Pass (v2.0)**:
   - Enhanced structure handling
   - Better validation
   - Improved schema compliance
   - Under development

### Decision Making Scope
The developer should decide on one of the following options:
- Complete v1.0 implementation following current architecture
- Evaluate v2.0 approach and either:
  - Continue with current two-pass design
  - Propose improvements with clear justification
  - Suggest alternative approach if significantly better

The developer may also:
- Propose improvements to the JSON schema design
- Suggest schema modifications to better capture document structure
- Recommend schema changes for better maintainability

### Architectural Constraints
- Current JSON schemas provided as reference:
  - v1.0: [v1.0/schemas/markdown_output.schema.json](./v1.0/schemas/markdown_output.schema.json)
  - v2.0: [v2.0/schemas/markdown_output.schema.json](./v2.0/schemas/markdown_output.schema.json)
- Must handle nested document structures
- Must preserve markdown hierarchy and formatting
- Must support batch processing

## Project Phases and Timeline

### Week 1-2: v1.0 Completion (20-25 hours)
- Fix remaining test cases
- Code cleanup and optimization
- Documentation updates

### Week 3-4: v2.0 Development (40-50 hours)
- Core implementation
- Test suite development
- Documentation maintenance

### Week 5-6: Testing & Documentation (15-20 hours)
- Integration testing
- Performance optimization
- Final documentation review

For more information about the project:
- See [PROCESSING_GUIDE.md](./PROCESSING_GUIDE.md) for technical details
- Review the [v1.0](./v1.0/) and [v2.0](./v2.0/) implementations

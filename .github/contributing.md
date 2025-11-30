# Contributing to Terraform Module

Thank you for your interest in contributing to this Terraform module! We welcome contributions that help improve the module's functionality, documentation, and examples.

## Getting Started

Before making changes, please:

1. Open an issue to discuss your proposed changes
2. Fork the repository and create a feature branch
3. Ensure you have Terraform >= 1.3.0 installed
4. Have access to required cloud providers for testing

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/MODULE_NAME
cd MODULE_NAME

# Create a feature branch
git checkout -b feat/your-feature-name

# Test the module
terraform init
terraform plan
```

## Pull Request Process

1. **Update Documentation**: Ensure `README.md` reflects any changes to variables, outputs, or usage examples
2. **Test Changes**: Verify your changes work with expected configurations
3. **Update Examples**: Add or modify examples in the `examples/` directory if relevant
4. **Version Updates**: Update `CHANGELOG.md` with your changes
5. **Run Validation**: Ensure `terraform validate` and `terraform fmt` pass

## Contribution Checklist

- [ ] Semantic commit messages (see below)
- [ ] Documentation updated for any variable/output changes
- [ ] Examples updated if functionality changes
- [ ] Terraform validation passes (`terraform validate`)
- [ ] Code formatting applied (`terraform fmt`)
- [ ] Module functionality tested against target providers
- [ ] Version constraints verified in `versions.tf`

## Semantic Commit Messages

Use conventional commit format:

- `feat:` - New features or module capabilities
- `fix:` - Bug fixes
- `docs:` - Documentation and example updates
- `refactor:` - Code restructuring without feature changes
- `test:` - Testing improvements
- `chore:` - Maintenance tasks
- `ci:` - CI/CD pipeline changes
- `perf:` - Performance improvements

## Testing Guidelines

- Test against supported provider versions
- Verify all module outputs and variables work correctly
- Test with minimum and maximum supported versions
- Ensure examples in `examples/` directory are functional
- Test resource creation, updates, and destruction
- Validate against multiple environments when possible

## Questions?

Open an issue for discussion or reach out to the maintainers. We appreciate your contributions!

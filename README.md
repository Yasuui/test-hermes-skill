# Test Hermes Skill

A template for creating Hermes skills.

## Overview

This repository contains a basic template for a Hermes skill that can be used with the Hermes Agent system.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Yasuui/test-hermes-skill.git
   cd test-hermes-skill
   ```

2. Install the skill by copying it to your Hermes skills directory:
   ```bash
   cp -r test_hermes_skill ~/.hermes/skills/
   ```

## Usage

Once installed, you can use the skill in your Hermes workflows:

```python
from test_hermes_skill import execute

result = execute()
print(result)  # Output: "Hello from test-hermes-skill"
```

## Development

To develop and test changes:

1. Make your changes to the `test_hermes_skill` directory.
2. Test locally:
   ```bash
   python -c "from test_hermes_skill import execute; print(execute())"
   ```
3. Commit your changes and push to your feature branch.
4. Open a pull request for review.

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/amazing-feature`).
3. Commit your changes (`git commit -m 'Add amazing feature'`).
4. Push to the branch (`git push origin feature/amazing-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

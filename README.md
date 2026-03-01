# Playwright Project

This is a Playwright end-to-end testing project for automated browser testing.

## Installation

Install dependencies:
```bash
npm install
```

## Running Tests

Run all tests:
```bash
npm test
```

Run tests in UI mode:
```bash
npm run test:ui
```

Run tests in headed mode (visible browser):
```bash
npm run test:headed
```

Debug tests:
```bash
npm run test:debug
```

Generate test code:
```bash
npm run codegen
```

## Project Structure

- `tests/` - Test files
- `playwright.config.ts` - Playwright configuration
- `package.json` - Project dependencies and scripts

## Configuration

Edit `playwright.config.ts` to customize:
- Base URL for tests
- Browsers to test
- Test directory
- Reporters
- Web server configuration

## Documentation

For more information, visit [Playwright Documentation](https://playwright.dev)

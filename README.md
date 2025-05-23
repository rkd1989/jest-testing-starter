# Jest Testing Starter

This repository is a simple and effective **starter template** for writing unit tests using **Jest** – one of the most popular JavaScript testing frameworks.

Whether you're testing JavaScript or TypeScript, this project is structured to help you hit the ground running with clear examples and setup.

## 🔍 Features

- 🧪 Jest test runner
- ⚙️ Pre-configured setup
- 📝 Sample test cases
- 🔁 Watch mode for development
- 📦 Minimal and extendable project structure

## 🧰 Tech Stack

- JavaScript (ES6+)
- [Jest](https://jestjs.io/)
- Node.js

## 📁 Folder Structure

```
.
├── __tests__/            # All test files
│   └── sample.test.js    # Example test
├── src/                  # Source code files
│   └── sample.js         # Example logic
├── package.json
└── jest.config.js        # Optional: Custom Jest config
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/rkd1989/jest-testing-starter.git
   cd jest-testing-starter
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run tests**
   ```bash
   npm test
   ```

4. **Run tests in watch mode**
   ```bash
   npm run test:watch
   ```

## 🧪 Example

```js
// src/sample.js
function add(a, b) {
  return a + b;
}
module.exports = add;

// __tests__/sample.test.js
const add = require('../src/sample');
test('adds two numbers', () => {
  expect(add(2, 3)).toBe(5);
});
```

## 🤝 Contributing

Feel free to fork this repo, use it as a template, or submit improvements via pull requests.

## 📄 License

This project is licensed under the MIT License.

> Maintained by [@rkd1989](https://github.com/rkd1989)

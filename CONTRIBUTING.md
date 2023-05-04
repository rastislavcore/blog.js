# Contributing

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

If you have found an issue or would like to request a new feature, simply create a new issue detailing the request. We also welcome pull requests. See below for information on getting started with development and submitting pull requests.

Please note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

## Found an Issue?

If you find a bug in the source code or a mistake in the documentation, you can help us by
submitting an issue to our [GitHub Repository](https://github.com/rastislavcore/blog.js/issues/new). Even better you can submit a Pull Request
with a fix.

## Submitting a Pull Request

- If applicable, update the `readme`
- Use `npm run lint` and `npm run prettier` before committing
- Example for a commit message

  ```
  Fix type validation for typescript
  ```

### Developing

Fork, then clone the repo:

```sh
git clone https://github.com/your-username/blog.js.git
cd blog.js
```

Install dependencies:

```sh
npm install
```

### Testing

Run test:

```sh
npm run test
```

Run test coverage:

```sh
npm run test:coverage
```

### Project Structure

```text
root
├── dist
└── src
└── types
```

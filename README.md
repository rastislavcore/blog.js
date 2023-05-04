**blog.js** is a JavaScript client designed to fetch recent blog posts from popular blogging platforms such as Dev, CRYPTO HUB and Medium. By providing a username, users can easily retrieve and showcase their most recent posts on their website or portfolio.

## Installation

Install via NPM.

```
npm install rastislavcore/blog-js#main
```

Or install via Yarn.

```
yarn add rastislavcore/blog-js#main
```

## Usage

- **`getDevPost()`**: Get 10 recent posts from [dev](https://dev.to).

  ```js
  const { getDevPost } = require('blog-js');

  getDevPost({
    user: 'yourusername',
  }).then((res) => {
    console.log(res);
  });
  ```

- **`getCryptohubPost()`**: Get 10 recent posts from [CRYPTO HUB](https://cryptohub.digital).

  ```js
  const { getCryptohubPost } = require('blog-js');

  getCryptohubPost({
    user: 'yourusername',
  }).then((res) => {
    console.log(res);
  });
  ```

- **`getMediumPost()`**: Get 10 recent posts from [medium](https://medium.com).

  ```js
  const { getMediumPost } = require('blog-js');

  getMediumPost({
    user: 'yourusername',
  }).then((res) => {
    console.log(res);
  });
  ```

## Sample Response

```js
[
    {
        title: "Why Enhancing Virtual Reality is Important",
        description: "Virtual reality is seen as a “fun” technology to some without much...",
        thumbnail: "https://cdn-images-1.medium.com/max/2600/0*kz30LOdXT8CyOymh",
        link: "https://medium.com/p/ac19dd21c728",
        categories: ["vr", "technology", "virtual-reality", "engineering", "artificial-intelligence"],
        publishedAt: Wed Aug 11 2021 18:43:34 GMT+0600
    },
    {
        title: "How to Get Started With Data Science: a Brief Guide",
        description: "You’ve heard about data science and machine learning, and you want to get started. Maybe you hear...",
        thumbnail: "https://cdn-images-1.medium.com/max/2600/0*Ah0vLtsvxqUvRWuS",
        link: "https://medium.com/p/88ec244f2fee",
        categories: ["beginner-coding", "data-science-training", "machine-learning-course"],
        publishedAt: Mon Jul 26 2021 22:55:26 GMT+0600
    }
]
```

## Contribute

To contribute, see the [contributing guide](CONTRIBUTING.md).

## License

[MIT License](LICENSE)

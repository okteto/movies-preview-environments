# Movies Sample app

This repository is used to show how you can leverage [Okteto](https://github.com/okteto/okteto)'s [Preview Environments](https://www.okteto.com/docs/cloud/preview-environments/preview-environments/) using the [Okteto Cloud Dashboard](https://www.okteto.com/docs/cloud/preview-environments/dashboard/). The app is deployed using a [Helm Chart](https://github.com/okteto/movies-preview-environments/tree/main/chart). It has the following components:

- A *React* based front-end, using [webpack](https://webpack.js.org) as bundler and *hot-reload server* for development.
- A very simple Node.js API using [Express](https://expressjs.com).
- A [MongoDB](https://www.mongodb.com) database.

This is the application used for the [Preview Environments Using Okteto Cloud Dashboard](https://www.okteto.com/docs/cloud/preview-environments/dashboard/) doc.

Testing

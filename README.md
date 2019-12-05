# cs-5744-project-1
Virginia Tech - CS 5744 - Project 2 - Test Plan for Hypnos Sleep

## Development

Step 1: Clone the Repository

Step 2: Install the dependencies

```
cd cs-5744-project-2/website
yarn install
```

Step 3: Modify pages (in `docs` folder)

Step 4: Run local server

```
yarn start
```

## Deploy to GitHub Pages

From the `website` folder:

```
yarn build
```

```
GIT_USER=USERNAME CURRENT_BRANCH=master USE_SSH=true yarn publish-gh-pages # SSH
# or
GIT_USER=USERNAME CURRENT_BRANCH=master yarn publish-gh-pages # HTTPS
```

To create a static version of the site that can be deployed anywhere comment the following lines in `website/siteConfig.js`:

```js
  // baseUrl: '/cs-5744-project-2/',
  // projectName: 'cs-5744-project-2',
  // organizationName: 'jonathandixon',
```

Then run `yarn build`.
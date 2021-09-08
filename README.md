<a href="https://github.com/3loka/nextjs-aws-stack"><img src="./.github/stacks/use-this-stack.svg"/></a>

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg" alt="Hugo" width="200" height ="100"/>  

 <p>
    <img src="https://assets.vercel.com/image/upload/v1607554385/repositories/next-js/next-logo.png" height="20">
    <img src="https://avatars.githubusercontent.com/u/6844498?s=200&v=4" height="20">
    <b>Use this stack</b> to spin up a static website in seconds and deploy to AWS S3.
</p>


## Why should you use this stack?
You can spin a website in seconds using NextJS.

Next.js gives you the best developer experience with all the features you need for production: hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching and more. No config needed. Read more about [next.js](https://nextjs.org/learn)

The website is hosted in AWS S3

The stack also sets up a proper Github CI/CD environment by taing care of the following things
- creating a "main" branch


## What are the inputs to pass while setting up the stack?
```
- AWS_S3_BUCKET_NAME
- AWS_S3_KEY
- AWS_S3_SECRET_ACCESS_KEY

```

#### Github apps installed with this stack
None

## How to setup local development server?
```
# Start by using github-codespaces developer environments 

# or alternatively start a local development environment.
npm run dev
open http://localhost:3000 

# to run tests
npm test

# to generate a production build
npm run build
```

## Learn more 

### Nextjs
Learn more about [next.js](https://nextjs.org/learn) from the official tutorial.
Visit [https://nextjs.org/docs](https://nextjs.org/docs) to view the full documentation.

## Other Useful links

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Trilok Ramakrishna ([@3loka](https://twitter.com/3loka))

## License
Unless otherwise noted, this GitHub Stack is distributed under the Apache Version 2.0 license found in the LICENSE file.

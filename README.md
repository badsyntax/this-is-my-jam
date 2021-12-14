# this-is-my-jam

An overview of my ideal JAM stack

![e10](https://user-images.githubusercontent.com/102141/145958017-3c2f714a-c116-451e-8cb7-9ee2b834b4cb.jpeg)

- Next.js
- Static front-end - if server side processing is required, this will be achieved using microservices
- CDN to serve static assets from the Edge - without using any lambdas, we want the fastest possible Edge response tmies
- Preview website on pull requests
- Server-side preview - for when we want to preview content changes from the headless CMS
- CMS powered (Strapi)
- Plausible analytics

## Infrastructure

- AWS
- IaC (CloudFormation)
- S3
- CloudFront
- ECS for server apps?

I might or might not script this up to make it easy to provision this stack...

# Kudos app

## Links

1. <https://www.prisma.io/blog/fullstack-remix-prisma-mongodb-4-l3MwEp4ZLIm2>
1. <https://cloudinary.com/blog/guest_post/how-to-upload-images-to-cloudinary-with-remix-app>
1. <https://dev.to/crypticai/uploading-files-in-remix-to-an-s3-compatible-service-35c9>

## Vercel deployment

Error about prisma generate during deployment. Just run the build command as 

        prisma generate && npm run build:css && remix build


## Welcome to Remix!

- [Remix Docs](https://remix.run/docs)

## Deployment

After having run the `create-remix` command and selected "Vercel" as a deployment target, you only need to [import your Git repository](https://vercel.com/new) into Vercel, and it will be deployed.

If you'd like to avoid using a Git repository, you can also deploy the directory by running [Vercel CLI](https://vercel.com/cli):

```sh
npm i -g vercel
vercel
```

It is generally recommended to use a Git repository, because future commits will then automatically be deployed by Vercel, through its [Git Integration](https://vercel.com/docs/concepts/git).

## Development

To run your Remix app locally, make sure your project's local dependencies are installed:

```sh
npm install
```

Afterwards, start the Remix development server like so:

```sh
npm run dev
```

Open up [http://localhost:3000](http://localhost:3000) and you should be ready to go!

If you're used to using the `vercel dev` command provided by [Vercel CLI](https://vercel.com/cli) instead, you can also use that, but it's not needed.

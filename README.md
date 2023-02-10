# Welcome to Remix!

- [Remix Docs](https://remix.run/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/`
- `public/build/`

### Using a Template

When you ran `npx create-remix@latest` there were a few choices for hosting. You can run that again to create a new project, then copy over your `app/` folder to the new project that's pre-configured for your target server.

```sh
cd ..
# create a new project, and pick a pre-configured host
npx create-remix@latest
cd my-new-remix-app
# remove the new project's app (not the old one!)
rm -rf app
# copy your app over
cp -R ../my-old-remix-app/app app
```
<!-- Como se su bio a repositorio Subida -->
echo "# GuitarLA-strapi" >> README.md
<!-- se cre4o en git manualmente -->
Luego en el proyecto (cmd) del programa
git init
git add README.md
git branch -M main
git remote add origin git@github.com:JAlvaroC/GuitarLA-strapi.git
git push -u origin main

<!-- Se agrego -->
git commit -m "first commit"


<!-- El link de produccion se tiende a caer actualizar con el video 300 de juan pablo  -->
BACKKEND
https://guitarla-strapi-2xkr.onrender.com/
Probar si responde con :
https://guitarla-strapi-2xkr.onrender.com/api/guitarras

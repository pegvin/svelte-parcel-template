# Svelte Parcel Template

A Svelte App Template With [Parcel](https://parceljs.org/) Module Bundler

---

## New Project

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit DEVLOPRR/svelte-parcel-template svelte-parcel-app
cd svelte-spa-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-parcel-app
npm install
```

...then start [Parcel](https://parceljs.org):

```bash
npm run dev
```

Navigate to [localhost:1234](http://localhost:1234). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `devDependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).

## Deploying to the web

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name svelte-parcel-app
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public svelte-parcel-app.surge.sh
```
### With [GitHub Pages](https://pages.github.com)

Make sure you have a github account and you've logged into the account.

Then make a [New github repo](https://github.com/new) and name it as follows - `username.github.io` where username is your github username you're using and make sure your repo is public.

Finally, Upload your build files and after a minute goto `username.github.io` where username is your github username.

---

# Thanks

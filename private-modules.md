<hgroup>
<h1>npm Private Modules</h1>
</hgroup>

When you pay for private modules, you can:

- Host as many private packages as you want
- Give read access or read-write access for those packages to any other paid user
- Install and use any packages that other paid users have given you read access to
- Collaborate on any packages that other paid users have given you write access to

<a data-event-trigger="click" data-event-name="billing-via-private-modules-page" class="button" href="https://www.npmjs.com/settings/billing">sign up</a>

## Scopes

All private packages are scoped. Your paid access applies to your scope, which is your username with an `@` in front.

```
@username/project-name
````

Read more about [scopes](https://docs.npmjs.com/getting-started/scoped-packages).

## Access

The access page gives you control over access to your package. To get to it, go to your package page at `https://www.npmjs.com/package/@username/your-package/access`, or click on the Collaborators link on the package page.

<p class="centered">
  <img src="http://npmblog-images.surge.sh/static-pages/collaborators-page.png" class="bordered">
</p>

### Making a package private

All scoped packages default to restricted access. This ensures that you don't make something public by accident. You can change this on the access page.

<p class="centered">
  <img src="http://npmblog-images.surge.sh/static-pages/make-private-ui.gif" class="bordered">
</p>

You can also manage package access via the command:

```sh
npm access restricted <package_name>
```

The package will be removed from listings on the site within a few minutes of making it private.

Learn more about [package access](@LINK).

### Adding collaborators to a project

You can now add collaborators to your project on the website. The new interface is available for
private modules as well as existing unscoped modules.

<p class="centered">
  <img src="http://npmblog-images.surge.sh/static-pages/add-collaborator.gif" class="bordered">
</p>

You can also add collaborators on the command line:

```sh
npm owner add <user> <package name>
```

### Changing collaborator access

If you want to give a user write access, change their access on the package page by clicking on `read-write`. You can also remove collaborators by clicking on the X.


## Logging in

When you try to install a private package from the CLI, you might get an access error. You will need to run `npm login` once to update your `~/.npmrc` file before working with private packages.

## Organizations

Currently, private packages are only available for individual users, but support for organization accounts is coming soon. Feel free to create a user for your organization in the meantime, and we can upgrade it to an organization when support is here.

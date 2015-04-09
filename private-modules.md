<hgroup>
<h1>npm Private Modules</h1>  
</hgroup>

When you pay for private modules, you can:

- Host as many private packages as you want
- Give read access or read-write access for those packages to any other paid user
- Download any packages that other paid users have given you read access to
- Collaborate on any packages that other paid users have given you write access to

<button>Sign up now</button>

## Scopes

All private packages are scoped. Your paid access applies to your scope, which is your username with an `@` in front.

`@your-name/package`

Read more about [scopes](@LINK).

## Making a package private

All scoped packages default to restricted access. This ensures that you don't make something public by accident.

If you have a public scoped package, you can change the access via the web site.

gif goes here

You can also change it via the command line using `npm access restricted <package_name>`.

gif goes here

The package will be removed from listings on the site within 1 minute of making it private.

Learn more about [package access](@LINK).

## Adding collaborators to a project

You can add collaborators to your project from the package page.

gif goes here

You can also use `npm owner add`

New collaborators will be given read-write access by default.

## Changing collaborator access

If you want to give a user read access only, change their access on the package page.

gif goes here

You can also remove collaborators.

## Organizations

Currently, private packages are only available for individual users, but support for organization accounts is coming soon. Feel free to create a user for your organization in the meantime, and we can upgrade it to an organization when support is here.

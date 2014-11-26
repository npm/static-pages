<hgroup>
<h1>npm Private Modules</h1>
<h2>Publish, share and install proprietary code easily</h2>
</hgroup>

Private modules are ordinary npm packages that only you, and people you select,
can view, install, and publish. You publish them in your namespace or your team's namespace, just by giving them a name in package.json:

<code>
{
  name: "@myuser/mypackage",
  ..
}
</code>

You publish them with `npm publish`, just like any other package, and you install
them by name:

<code>npm install @myuser/mypackage</code>

Once installed, use them by requiring them by name, just like any package:

<code>
var mypackage = require('@myuser/mypackage')
</code>

## Re-use your code

You re-use code between projects. npm and the registry make it really easy to
share small modules of useful code with the world. But sometimes the code in that 
package is private, or sensitive, or just too specific to your needs for you to
want to publish it to the public registry. Private packages are great for this.

## Share proprietary code

You work in a team, or you work for clients. You want to be able to easily share 
your work, with the dependency management and version management that npm provides.
By making it easy and granular to select who can see, install and publish packages,
private packages make this easy.

## Coming soon

npm Private Modules are coming in early 2015. 

If you would like early access to the beta of npm Private Modules, you can sign up right now and we'll let you know
when they are available.

<script charset="utf-8" src="//js.hsforms.net/forms/current.js"></script>
<script>
  hbspt.forms.create({ 
    portalId: '419727',
    formId: 'd9ba17d5-606e-456d-a703-733c67f5e708'
  });
</script>

(We will not use this email address to do anything other than notify you of 
the beta of npm Private Modules, and when private packages become globally available)

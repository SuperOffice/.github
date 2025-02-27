# Welcome to SuperOffice' Github page :v:

![SuperOffice][superoffice-ico]

**Welcome, fellow developer, we’re happy to see you here! :tada:**

This github organization contains examples and guidelines for how to integrate with, create an application for or create scripts in SuperOffice.
Please note that examples are not production-ready, and should be used as a starting point to get the basics up and running.

SuperOffice itself uses C#, but you can create applications/customizations in whatever language that suits you!

:rocket: **Samples**

We have code-samples in various different languages and are currently working on re-vamping the samples library to make it easier to navigate.
The plan is to consolidate samples for each language under one repo, but this will be a work in progress.

For running raw HTTP queries towards the REST API, using vscode an the [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) extension, you can take a look at [RESTful-HTTP-Queries](https://github.com/SuperOffice/RESTful-HTTP-Queries). This repo will continuously expand as we add more sample-code to show different ways to interact with our APIs ([RESTful](https://docs.superoffice.com/en/api/reference/restful/rest/index.html) and [Agents](https://docs.superoffice.com/en/api/reference/restful/agent/index.html))

For samples for using the [SuperOffice.WebApi](https://www.nuget.org/packages/SuperOffice.WebApi) nuget package in the [SuperOffice WebApi Samples](https://github.com/SuperOffice/SuperOffice.WebApi-Samples).

We also have samples for [php](https://github.com/SuperOffice/devnet-php-oidc-soap), [NextJS](https://github.com/SuperOffice/devnet-nextjs-chakraui), [python](https://github.com/SuperOffice/devnet-python-system-user), [electron](https://github.com/SuperOffice/devnet-electron-appauth).
Please note that examples in other languages then C# are not regularly updated, so we are depending on feedback to fix issues.

:rocket: **Good to know**

SOAP has officially been marked as [upcoming end-of-life](https://docs.superoffice.com/release-notes/eol/soap.html) and we will not be updating the code-samples that contains samples for using the webservices.
In other words we recommend using the REST-based API's for new applications, and migrate existing SOAP-based applications to use REST instead.

You can also use [AspNet.Security.OAuth.SuperOffice](https://github.com/aspnet-contrib/AspNet.Security.OAuth.Providers) as a middleware in your ASP.NET CORE application.

You can find more documentation for our API on [docs.superoffice.com](https://docs.superoffice.com/en/api/overview/index.html).

If you have any questions feel free to reach out to use on either [appdev\@superoffice.com](mailto:appdev@superoffice.com) or by creating an issue on appropriate repo (if its sample-specific).

<!-- Reference links -->
[superoffice-ico]: ../OWL.ICO

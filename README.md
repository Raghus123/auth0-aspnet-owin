Owin/Katana Authentication Handler for Auth0. Plugs into the ASP.NET 4.5 Owin infrastructure (middleware) and extends default providers with more social providers such as Amazon, Facebook, GitHub, LinkedIn, LiveId, Google, Twitter, PayPal and vKontakte. Also integrates with Enterprise providers like any IdP that speaks SAML Protocol, ADFS, Google Apps, ADFS, Windows Azure AD, etc.

> Note: ASP.NET 5 support is available in the following repository https://github.com/auth0/auth0-aspnet5

## Quickstart

You can find the ASP.NET (OWIN) quickstart which utilizes this package on the Auth0 Documentation Website at [https://auth0.com/docs/quickstart/webapp/aspnet-owin/](https://auth0.com/docs/quickstart/webapp/aspnet-owin/)
 
## Installation

For using inside an ASP.NET MVC project you can install the `Auth0-ASPNET-Owin` package:

```
Install-Package Auth0-ASPNET-Owin
```

The package above also installs an MVC controller which handles the callback from the server. If you want to use just the OWIN middleware, without any dependencies on MVC, then you can use the `Auth0-ASPNET-Owin-Libs` package: 

```
Install-Package Auth0-ASPNET-Owin-Libs
```

## Usage

[Please see this NuGet's README.](nuget/README.txt)

## Examples

In this repository we've also included different Owin samples, using the Auth0 Authentication Handler or standards based (Bearer token, OpenID Connect, ...) handlers.

 - [ASP.NET 4 - MVC sample with Auth0-ASPNET-OWIN](https://github.com/auth0/auth0-aspnet-owin/tree/master/examples/MvcSample)
 - [ASP.NET 4 - MVC seed project with Auth0-ASPNET-OWIN](https://github.com/auth0/auth0-aspnet-owin/tree/master/examples/basic-mvc-sample)
 - [ASP.NET 4 - Web API sample with Bearer Tokens](https://github.com/auth0/auth0-aspnet-owin/tree/master/examples/WebApi)

 ## Issue Reporting

 If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

 ## Author

 [Auth0](auth0.com)

 ## License

 This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.

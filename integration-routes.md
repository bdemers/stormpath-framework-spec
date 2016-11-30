List of Integration Routes, Property Keys and Default Paths
===========================================================

## [Oauth2](oauth2.md)

```
stormpath.web.oauth2.uri = /oauth/token
```

## [Register new user](registration.md)

```
stormpath.web.register.uri = /register
stormpath.web.register.nextUri = /
```

## [Verify user email after registering](email-verification.md)

```
stormpath.web.verifyEmail.uri = /verify
```

## [Login landing page](login.md)

```
stormpath.web.login.uri = /login
stormpath.web.login.nextUri = /
```

## [Logout route](logout.md) (must be a POST)

```
stormpath.web.logout.uri = /logout
stormpath.web.logout.nextUri = /
```

## [Forgot Password routes](password-reset.md#forgot-password-endpoint-forgot)

```
stormpath.web.forgotPassword.uri = /forgot
stormpath.web.forgotPassword.nextUri = /login?status=forgot
```

## [Change Password routes](password-reset.md#change-password-endpoint-change)

```
stormpath.web.changePassword.uri = /change
stormpath.web.changePassword.nextUri = /login?status=reset
stormpath.web.changePassword.errorUri = /forgot?status=invalid_sptoken
```

## [ID Site & SAML callback](idsite.md#stormpathcallback)

```
stormpath.web.callback.uri = /stormpathCallback
```

## [ID Site forgot/register URLs](idsite.md)

```
stormpath.web.idSite.forgotUri = /#/forgot
stormpath.web.idSite.registerUri = /#/register
```

## [Social callbacks](social.md)

```
stormpath.web.social.facebook.uri = /callbacks/facebook
stormpath.web.social.github.uri = /callbacks/github
stormpath.web.social.google.uri = /callbacks/google
stormpath.web.social.linkedin.uri = /callbacks/linkedin
```

## [Current User Info](user-context.md)

```
stormpath.web.me.uri = /me
```

## Default 403 page

```
stormpath.web.unauthorized.uri = /unauthorized
```

## What is OAuth (Links to an external site.)
## What is OAuth? 
An open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.
## Give an example of what using OAuth would look like.
## When you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.
## How does OAuth work? What are the steps that it takes to authenticate the user?

-The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
-The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
-The first site gives this token and secret to the initiating user’s client software.
-The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
-If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
-The user approves (or their software silently approves) a particular transaction type at the first website.
-The user is given an approved access token (notice it’s no longer a request token).
-The user gives the approved access token to the first website.
-The first website gives the access token to the second website as proof of authentication on behalf of the user.
-The second website lets the first website access their site on behalf of the user.
-The user sees a successfully completed transaction occurring.

## What is OpenID? 
OpenID about authentication: as a commenter on StackOverflow pithily put it (Links to an external site.): "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."


Authorization and Authentication flows (Links to an external site.)

## What is the difference between authorization and authentication? 
Authentication is the process of verifying who someone is and authorization is the process of verifying what specific items a user has access to
## What is Authorization Code Flow?
The passing of an authorization code for a token. This must be server-side due to the passing of the client secret as well.
 ## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
An additional layer of protection for public application;  an authorization call to the server to request the access token from the AuthO provider.

## What is Implicit Flow with Form Post? 
With the help of OpenId Connect(OIDC), Implicit Flow with Form Post implements web sign-in, without having to obtain, maintain, use, and protect a secret in the app.

## What is Client Credentials Flow? 
Where the system authorizes and authenticates the app rather than the user

 ## What is Device Authorization Flow?
The use of another user’s device to provide authentication. Similar to 2 part authentication, designed for devices with poor input interfaces.

## What is Resource Owner Password Flow? 
When the user is requested to provide login credentials, this is Not recommended
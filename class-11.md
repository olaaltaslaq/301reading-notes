# Authentication 

- ## What is OAuth?

*It is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.*

- ## Give an example of what using OAuth would look like.

*When I go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.*

- ## How does OAuth work? What are the steps that it takes to authenticate the user?

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
3. The first site gives this token and secret to the initiating user’s client software.
4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
6. The user approves (or their software silently approves) a particular transaction type at the first website.
7. The user is given an approved access token (notice it’s no longer a request token).
8. The user gives the approved access token to the first website.
9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
10. The second website lets the first website access their site on behalf of the user.
11. The user sees a successfully completed transaction occurring.
12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user.


- ## What is OpenID?

*Security technologies that you might hear about in the same context as OAuth.*


<hr>

**HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me**

***click on the [link](https://github.com/olaaltaslaq) to find my GitHub***


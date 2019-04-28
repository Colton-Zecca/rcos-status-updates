## Last Week's Accomplishments

Over the last week, I talked with Frank about the different possibilities of how we could potentially pull and use 
data on the mobile application for LATE. We concluded that there is three main routes we could go through with:

1) Have a login page through the mobile application itself where we grab the user's RCSID and password, passing it in 
through SIS/related in order to pull classes and other students' data.

2) Redirect the application to the CAS mobile web application itself to authenticate, then direct back to the LATE mobile
application. This might be favorable for DotCIO as it doesn't involve the user entering their authentication info
into our mobile application. However, it would be tedious to the user as they would need to go through the following
redirects: Late Mobile Application --> Default Mobile Browser --> CAS Authentication --> Late Mobile Application.
If the user used a password manager such as LastPass, it would be even more inconvenient as they would have to add
an extra step by going to their password manager for getting their login information.

3) Make users have LATE accounts, in which they would then log into through the LATE mobile application. In the long
run, this may be favorable as we would not have to worry about third-party authentication. On the other hand, it would
likely require some rework on the backend of the website application for late.

Regardless of the route we choose, we will likely have to redesign and document LATE REST APIs for a mobile application.
This would be monotonous work, but would be extremely useful in the long run as we would be able to expose REST API 
endpoints for other applications in the future to access for various student information (using an API key or something
of the sort). Frank and I talked about different documentation tools, one of which was https://swagger.io/. This would
also allow for much easier integration with SIS and other tools in the future for all students looking to access 
student information via applications they want to make, without having to worry about the hassle of scraping SIS and
other web pages.

As of now, the current most favorable routes are route 1 and 3.

## This Week's Plan

N/A

## Anything Blocking?

The security limitations that iOS and DotCIO may have on mobile-related authentication.

## Notes

None.

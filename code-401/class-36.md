# Application State with Redux

__What are the advantages of storing tokens in “Cookies” vs “Local Storage”__  
Cookies are read server-side, and local storage is read client-side, so if the server needs the data, then it is better to use cookies.  
https://medium.com/datadriveninvestor/cookies-vs-local-storage-2f3732c7d977#:~:text=Cookies%20and%20local%20storage%20serve,you%20more%20to%20work%20with.  
__Explain 3rd party cookies.__   
These are cookies tracked by websites other than the one you are currently visiting. For example, if you visit websites containing a certain product, it might save a cookie that other webistes can see, and you will see ads about that product in other places you are browsing.  
https://cookie-script.com/all-you-need-to-know-about-third-party-cookies.html#:~:text=Third%2Dparty%20cookies%20are%20cookies,see%20which%20websites%20he%20visited.  
__How do pixel tags work?__   
This is a single transparent pixel added to a web page. This image is served from the ad server's domain so they can record cookies based on the users behavior while not relying on being seen or clicked on.  
https://resources.marketingeffectiveness.nielsen.com/blog/cookies-tags-pixels-tracking-customer-engagement#:~:text=Pixel%20tags%20are%20typically%20single,image%20you%20may%20see%20online.

|Term | Definition |  
|---|---|
| cookies | These are small files on a user's computer that hold data specific to a client and a website, which allow a webpage to be catered to a specific user. https://medium.com/datadriveninvestor/cookies-vs-local-storage-2f3732c7d977#:~:text=Cookies%20and%20local%20storage%20serve,you%20more%20to%20work%20with.|
| authorization | People with different authorization levels have access to different parts of a system or network. First they are authenticated, then they authorized to go to different areas based on what they are allowed to see and do.|
| access control | This restricts access to different areas of a network based on a person's role in an organization. https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more|
| conditional rendering | These are parts of a React app that will only be rendered in certain conditions. For example, in the app we worked on last week, the form was not rendered for users with 'read' access, but it was rendered for users with 'create' access. |


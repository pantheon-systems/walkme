# [WalkMe](http://www.walkme.com/?u=e18cc7d035fb401c801e81a52a56b8e1)
Planning and Issue Tracking for Pantheon's WalkMe implementation. 

## The Widget
Docked to the bottom-right, the widget grows when clicks to expose the following.
### Docs Search
Automatic text search field of google's index of pantheon.io/docs. Opens selected doc in new tab.
### Walkthroughs
Launch users into guided procedures and tours through the product. Walkthroughs are made of steps, which contain a title and body field, can have videos or images embedded into them, and can be segmented based on on-screen elements, current URL, and jquery. Steps can perform redirects, branch to other walkthroughs, or jump ahead in the tour.  
### Content
Links w target="_blank" to docs or videos. Content is segmented according to current URL containing specific patterns (as it was with the doclinks.coffee file removed from the dashboard)
### Onboarding (not deployed)
Tasks, relies on a user ID variable in the dashboard to track whether individual users have completed goals

## Design
@informanddelight owns the .css customization, stored in this Repo and edited/applied through the WalkMe editor.

## WalkThroughs in Development
Access walkthroughs published to Test via any Onebox. Brian's is used almost exclusively for WalkMe testing. Register an account on it using "name+walkme@pantheon.io" and record your issues here. Contact Brian for instructions to test.


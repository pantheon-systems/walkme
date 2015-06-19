
# [WalkMe](http://help.walkme.com/)
Planning and Issue Tracking for Pantheon's WalkMe implementation.

## Help with QA:
Complete instructions at [CONTRIBUTING.md](/CONTRIBUTING.md). Create a new account at https://brian.onebox.panth.io/register. When you get to `/users/UUID#sites/sites` the system will launch the [Create Your First Site](/walkthroughs/create-your-first-site) walkthrough. Run through the walkthroughs and submit issues you find here in the [issues queue](https://github.com/pantheon-systems/walkme/issues), or propose changes to the walkthrough on the Pull Request it is in.

Merging Pull Requests into Master indicates that the walkthrough has been approved as designed and should coincide with that walkthrough's Publication in the walkme interface.

For a walkme account, please ping Brian in slack #docs channel.

## The Widget

Docked to the bottom-right, the widget grows when clicked to expose:

- Docs Search: Automatic text search field of google's index of pantheon.io/docs. Opens selected doc in new tab.
- Walkthroughs: Launch users into guided procedures and tours through the product. Walkthroughs are made of steps, which contain a title and body field, can have videos or images embedded into them, and can be segmented based on on-screen elements, current URL, and jquery. Steps can perform redirects, branch to other walkthroughs, or jump ahead in the tour.  
- Content: Links w `target="_blank"` to docs or videos. Content is segmented according to current URL containing specific patterns (as it was with the doclinks.coffee file removed from the dashboard)
- Onboarding (not deployed) Tasks, relies on a user ID variable in the dashboard to track whether individual users have completed goals

## Design
@informanddelight owns the .css customization, which we will archive in [walkme.css](/walkme.css) and edit/apply through the WalkMe editor.

## WalkThroughs in Development
Access walkthroughs published to Test via any Onebox. Brian's is used almost exclusively for WalkMe testing. Register an account on the onebox it using "name+walkme@pantheon.io" and record your issues here. Contact Brian for instructions to test.
The content plan will be reflected in this repository's [Pull Requests](https://github.com/pantheon-systems/walkme/pulls). The MVP will launch with the merge to master for the `launch` branch of this repository.

##Walkthrough Design Docs
While it adds a bit of overhead to walkthrough creation, I think that a normal place to outline a walkthrough before building them will help our ability to communicate about them. Create a new document with the name of the goal, and outline the procedure required to meet it.

---
Permalink: /?walkme=72752
In Widget: Yes

---
#On-Server Development with SFTP Mode
Guides users through making a code change and commit it.
##Segmentation
No segments

##Engagement
 - No Autoplay
 - Links to walkthrough:
  - End of Create your first site
  - End of Site Dashboard Tour walkthroughs

##Outline
###App Logic Steps
Steps 1-9 Get the user to the Site Dashboard at #dev/code

###Get into SFTP Mode

If the git ssh string element exists, the walkthrough will play the switch to SFTP mode step. If not, it will skip and continue into waiting for SFTP connection information text.

###Development Steps
1. Develop
 - On the connection mode toggle:
 - Your site's code is now available for you to edit in any way you choose. You can install extensions and themes through your application's admin interface, or edit the code directly.
 - Triggered by next button
5. Add or update code
  Log in to your site and either
 - Install a new module, plugin, or theme
 - Update an existing extension.

 Return to this tab when you're done. 

6. Wait for File Changes to be noticed

###Commit Steps
1. The Dashboard Knows
 - On the _n_ files have changed and are ready to Commit
 - Any time you have saved code changes, you'll see this message. Click it to see the files that have changed.
 - Triggered by Click
2. Check the diff
 - On the changed files list
 - We'll display the code diff.
 - Triggered by next

3. Describe the Changes
 - On the active Commit Message box

 ```
 [b]You are writing to your future self.
Keep commits small: [/b]
 - Make one commit per logical change
 - Make one commit per extension installation or update[b][/b]
 - Commits take a snapshot of working code
[b]Messages: [/b]
  - ~ 50 characters for the description
  - SHIFT+return to make a new line
  - Use new lines to explain changes
  ```
 - Triggered by next step trigger
6. Wait for commit spinner to appear
7. Wait for Commit spinner to disappear
8. Here it is
 - On the first commit in the Log
 - Click on the commit to see the diff.
 - Triggered by click/next
9. Wait for diff away
10. You Did It!
 - Pop-up-step
 ```
 If you want us to walk you through that again,
select "On Server Development wit SFTP Mode"
from the New User Walkthroughs in the Help widget.
```
 - Triggered by Done

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
2. Access your code
 - On the SFTP Connection information
 - Triggered by click
3. Click here
 - On the SFTP default login link
 - Log in to your server using your Pantheon password or [url=https://pantheon.io/docs/articles/users/loading-ssh-keys/]SSH key[/url].
 - Triggered by click
4. If that doesn't work
 - Left of the connection info strings
 - Copy and Paste the connection info strings into your preferred SFTP client or IDE. [b]Remember to change the port to 2222[/b]
Set that application as your default client for the [b]sftp://[/b] protocol.
  - Triggered by Next
5. Go Make a Change to Your Codebase
  - Pop-up-step

```
  We'll wait here for the change to be made.
  [b]Example Code Changes[/b]
  - Install or update a Drupal module or theme from the admin interface
  - Create a [b][u]hello-world.txt[/u][/b] file inside of the [u][i][b]~/code[/b][/i][/u] directory.
```
6. Wait for File Changes to be noticed

###Commit Steps
1. The Dashboard Knows
 - On the _n_ files have changed and are ready to Commit
 - Any time you have saved code changes, you'll see this message. Click it to see the files that have changed.
 - Triggered by Click
2. Click on a File
 - On the changed files list
 - We'll display the code diff.
 - Triggered by click
3. Changes in Red and Green
 - On the first + and - line in the diff
 -
 - Triggered by Next
4. Wait for Diff to disappear
5. Describe the Changes
 - On the active Commit Message box

 ```
 [b]You are writing to your future self.
Keep commits small: [/b]
 * Make one commit per logical change
 * Make one commit per extension installation or update[b][/b]
 * Commits take a snapshot of working code
[b]Messages: [/b]
  * ~ 50 characters for the description
  * SHIFT+return to make a new line
  * Use new lines to explain changes
  ```
 - Triggered by next
6. Make it Deployable
 - On the Commit button
 - Only committed code can be deployed to Test or Live environments.
 - Triggered by click
7. Wait for Commit spinner to disappear
8. Here it is
 - On the first commit in the Log
 - Click on the commit to see the diff.
 - Triggered by click
9. Wait for diff away
10. You Did It!
 - Pop-up-step
 ```
 If you want us to walk you through that again,
select "On Server Development wit SFTP Mode"
from the New User Walkthroughs in the Help widget.
```
 - Triggered by Done

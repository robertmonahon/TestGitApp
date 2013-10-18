TestGitApp
==========

This test of GitHub shows two branches off master, and how to merge them back together.

<<<<<<< HEAD
As of this writing, we are up to the point of how-to-do-it. But I don't know how.

Here's what's happened so far:

 - One branch (fixDB) is changed, committed, and merged back to master.
=======
As of this writing, we are up to the point of how-to-do-it.  But I don't know how.

Here's what's happened so far:
 - One branch (fixDB) is changed, committed, and merged back to master.  
>>>>>>> origin/fixBat
 - The other branch (fixBat) is also changed and committed.
 - The change in fixBat conflicts with the change in fixDB.

When I try to merge fixBat back into master, I get the message:

<<<<<<< HEAD
  unable to merge 
  you might have to shell in to diagnose this repo

=======
  unable to merge
  you might have to shell in to diagnose this repo
  
>>>>>>> origin/fixBat
Hmm. Stuck

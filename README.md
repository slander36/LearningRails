LearningRails
=============

Learning Rails using ruby.railstutorial.org

###Things Learned So Far:###
1. Always reload shell after installing ANYTHING that changes config files, especially RVM and TMUX
2. You have to update app/assets/\*/application.\* to include anything you added to vendor/
3. Heroku just acts like a git repo, so working from multiple computers is as easy as using Github - just `git remote add heroku`
4. TMUX uses .bash_profile, not .bashrc, so make sure and symlink .bashrc to .bash_profile if you don't feel like renaming the file or copying the contents over every time your .bashrc is changed
5. You always have to hold Apple's hand when it comes to local servers. Remember to add `localhost` as the host to everything.
6. YAML doesn't like tabs. I keep forgetting this...
7. Guard and Spork don't like it when you change routing. Make sure and turn off Guard when adding and updating things as it likes to fail on code errors instead of just on failed tests.
8. The above is true for Gemfile as well. DON'T update your Gemfile with Guard running if you're using TMUX+VIM as it seems to cause an issue.


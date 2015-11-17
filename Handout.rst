==================
Handout for new contributors
==================

Overview of TYPO3 sites
==================

- typo3.org: https://typo3.org/
- Slack: https://typo3.slack.com/ + https://typo3.org/slack/
- Forge: https://forge.typo3.org/
- Gerrit: https://review.typo3.org/
- Forger: https://forger.typo3.org/
- Wiki: https://wiki.typo3.org/
- API: http://api.typo3.org/
- Server team contact (use in case of problems): admin (at) typo3 (dot) org

Coding Standards
==================

- TYPO3 Coding Guidelines: https://docs.typo3.org/typo3cms/CodingGuidelinesReference/
- TYPO3 Code of Conduct: https://typo3.org/community/code-of-conduct/
- Semantic Versioning: http://semver.org/

Github
==================

- Example project: https://github.com/stucki/typo3-frontend-rendering-explained
- Github mirror of TYPO3 SVN repositories: https://github.com/TYPO3-svn-archive
- Github mirror of TYPO3 Git repositories: https://github.com/TYPO3-extensions

Gerrit Review
==================

- Contribution Walkthrough Tutorials: https://wiki.typo3.org/Contribution_Walkthrough_Tutorials
- Vagrant box for doing reviews: https://github.com/Tuurlijk/TYPO3.Review

Shell commands
==================

- Push to Gerrit instead of git.typo3.org
::

  git config --global url."ssh://<username>@review.typo3.org:29418".pushInsteadOf git://git.typo3.org
- Rebase on pull
::

  git config --global branch.autosetuprebase remote
- Set an alias "git hist" to see 1 commit per line
::

  git config --global alias.hist \
    "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
- Show origin/master + all local branches in a tree view, limit to 10 last commits
::

  git hist origin/master --all -n 10

Documentation
==================

- Documentation website: https://docs.typo3.org/
- Information for contributors: https://wiki.typo3.org/Contributing_to_the_documentation
- Github project: https://github.com/TYPO3-Documentation/
- Forge project: https://forge.typo3.org/projects/typo3cms-documentation
- ReST Syntax: https://wiki.typo3.org/ReST_Syntax

Translation
==================

- Translation server (Pootle): https://translation.typo3.org/
- Information for contributors: https://wiki.typo3.org/Translations

Other stuff
==================

- Git online workshop: http://gitimmersion.com/
- Oh My Zsh: https://github.com/robbyrussell/oh-my-zsh
- see which changes need to be merged into release branches: http://tools.typo3.org/cms/merged/

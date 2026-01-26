
Un poco de historia de como hice el fork de este repositorio: 

❯ this is what I see:
  ➜  dotfiles-pancho git:(master) git remote -v
  origin  git@github.com:fgarau/dotfiles-pancho.git (fetch)
  origin  git@github.com:fgarau/dotfiles-pancho.git (push)
  upstream        git@github.com:omerxx/dotfiles.git (fetch)
  upstream        git@github.com:omerxx/dotfiles.git (push)

--  This is exactly right. Your setup is correct:

  - origin → Your fork (where you push your changes)
  - upstream → Original repo (where you pull updates from)

  Common workflow with this setup:

  # Push your changes to your fork
  git push origin master

  # Pull latest changes from the original repo
  git fetch upstream
  git merge upstream/master

  You're all set to start making changes.

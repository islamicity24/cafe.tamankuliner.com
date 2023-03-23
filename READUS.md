…or create a new repository on the command line
echo "# cafe.tamankuliner.com" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/islamicity24/cafe.tamankuliner.com.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/islamicity24/cafe.tamankuliner.com.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


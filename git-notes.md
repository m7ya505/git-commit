printf "# Git Notes\n\nA commit is a snapshot of my whole project at one moment.\n" > git-notes.md
cat git-notes.md

printf "\n## Commands I learned\n- git status\n- git add <file>\n- git commit -m \"message\"\n- git push\n" >> git-notes.md
git add git-notes.md
git commit -m "git-notes: add commands cheat-sheet"
git push

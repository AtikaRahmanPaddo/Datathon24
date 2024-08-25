# Emory Health AI Bias Datathon 2024

### Please upload your code to your respective team folder!

### Instructions:

First, clone the repository to your server with:

`git clone https://github.com/Emory-HITI/Datathon24.git`

`cd Datathon24`

Then, create a new branch where you can register your changes. For example, if you were in team3 you could use:

`git checkout -b team3-branch`

Then, add your code to your team's individual folder. **Please only modify YOUR FOLDER and don't include any data (like CSVs you've generated)!**

Use `git add` to register your changes. For example, if you were in Team 3 you would use:

`git add team3`

Then add a quick commit note like:

`git commit -m "adding team files"`

And push your files with:

`git push --set-upstream origin feature-branch`

Finally, submit a pull request to merge your branch into `main` with a command like the following (or from the Github website if you don't have the Github CLI installed):

`gh pr create --base main --head team3-branch --title "Team3 Pull Request" --body "Merging in team 3 files"`

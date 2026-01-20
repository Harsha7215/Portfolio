1. Make Sure You Have a Commit
If you just initialized Git but didn’t commit anything:

bash
git add .
git commit -m "Initial commit"


2. Check Your Current Branch
Run:

bash
git branch
If you see * master, your branch is master.

If you see * main, your branch is main.

3. Push Correctly
If your branch is master:

bash
git push -u origin master
If your branch is main:

bash
git push -u origin main


4. Rename Branch (Optional)
If you want to standardize on main:

bash
git branch -M main
git push -u origin main

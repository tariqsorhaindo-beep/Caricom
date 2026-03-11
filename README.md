cd /Users/tariqsorhaindo/Desktop/CariCom

# if you didn’t initialise with a README:
git init
git add .
git commit -m "Initial commit"

# add the GitHub remote (replace with your actual URL)
git remote add origin git@github.com:your-username/caricom-site.git

git branch -M main           # make sure you’re on main
git push -u origin main      # upload all files

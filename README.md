# Initialize a local Git repository
git init -b main

# Stage all your new files
git add .

# Save the files to your local version history
git commit -m "Initial commit: Added app script, readme, and gitignore"

# Link your local machine to your remote GitHub repository
# (Replace the URL below with your actual GitHub repository URL)
git remote add origin https://github.com

# Push your code up to GitHub
git push -u origin main


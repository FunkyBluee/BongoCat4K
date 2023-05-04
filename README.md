# BongoCat4K
It's a FNF Skin Version That Is Made By Me

from github import Github
import os

# Replace YOUR_GITHUB_USERNAME and YOUR_GITHUB_PASSWORD with your own credentials
g = Github("YOUR_GITHUB_USERNAME", "YOUR_GITHUB_PASSWORD")

# Replace YOUR_GITHUB_USERNAME and YOUR_REPOSITORY_NAME with your own information
repo = g.get_user("YOUR_GITHUB_USERNAME").get_repo("YOUR_REPOSITORY_NAME")

# Replace LOCAL_DIRECTORY with the local directory where you want to clone the repository
local_directory = "LOCAL_DIRECTORY"

# Clone the repository to the specified directory
os.system(f"git clone {repo.clone_url} {local_directory}")

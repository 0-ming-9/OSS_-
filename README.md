# OSS_-
import kagglehub
import os

# Download latest version
path = kagglehub.dataset_download("shivamb/netflix-shows")

print("Path to dataset files:", path)

print(os.listdir(path))

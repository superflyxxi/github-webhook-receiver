# Introduction
The point of this repo is to provide flexible, plugable logic to common github webhooks. Things like on delete of a 
branch, delete appropriate build artifacts from servers.

## Requirements
- On delete of a branch, delete its corresponding docker images in a private repository.
  - Repo URL
  - Repo User
  - Repo password
  - Regex for matching images/labels


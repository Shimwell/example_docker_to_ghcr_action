# example_docker_to_ghcr_action

Builds a Dockerfile and uploads the image to GitHub Packages / Container Registry (ghcr)

The uloaded package can be found here 
https://github.com/Shimwell?tab=packages

This has a few advantages of uploading to dockerhub
  - authentification is easier, no need for another user password account
  - uploading is quicker (GH actions builds and uploads to GH packages very quickyl)
  - downloading into GH based CI is quicker

There is also at least one disadvantage:
  -names space for dockerimage is a bit longer (ghcr.io/ must be included in front of image name)

# GHCR
# Push a image to Github Packages (GHCR)
    1.Create image
    2.Create PAT on Github
    3.Authenticate GHCR
    4.Tag and push our image to GHCR

 ```
export CR_PAT=<TOKEN>
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
```

# Use Github Actions to Publish a Docker image to Github Packages (GHCR)
    Create repo - and Checkin our Dockerfile
    Build your Github action workflow
    Trigger our workflow
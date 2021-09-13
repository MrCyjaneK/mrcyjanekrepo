# mrcyjanek's repo

To install this repo:

```plain
# curl https://repo.mrcyjanek.net/abstruse_at_mrcyjanek.net.pgp.raw > /usr/share/keyrings/cyjan.gpg && \ 
echo "deb [signed-by=/usr/share/keyrings/cyjan.gpg] https://repo.mrcyjanek.net/ default main" > /etc/apt/sources.list.d/cyjan.list
```

after that you can install `mrcyjanek-repo` package to get automatic updates (for example if I change the repo url or signing key)
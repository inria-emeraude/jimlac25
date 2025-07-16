# JIMLAC 2025 Website Repo

## How to deploy website on Inria server?

```
su
cd /tmp
mkdir dav
mount.davfs https://files.inria.fr:8443/jimlac25 dav
cd dav
cp -r /home/romain/reps/jimlac25/docs/* .
```

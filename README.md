# flux-experiment-apps

```
# prerequisite: docker login

cd apps/app-a
docker build -t oschira/app-a .
docker images
docker tag 4448fea14b16 oschira/app-a:1.0
docker push oschira/app-a

# repeat for b and c
```

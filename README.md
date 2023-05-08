# expressapi example in Typescript

CD to folder
```
cd ./EXPRESSAPI
```

build image
```
docker build -t expressapi .
```


run container
```
docker run -p 3000:8080 expressapi
```

open browser
```
http://localhost:3000
```


=======================================================

init tsconfig.json
```
npx tsc --init
```


install express for typescript
```
npm install -D @types/module-name
```

## Dev

`docker build -f Dockerfile.dev .`

`docker run -p 3000:3000 48ae9e6c1863`
`docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app 120ca70fc4c4`

`docker-compose up`

# Test

`docker run -it 5bbf01a30d26 npm run test`

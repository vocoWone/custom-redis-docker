## image build 
- docker build -t custom-redis-docker --no-cache  .docker/

## image run 
- docker run -d -p 6379:6379 --name custom-redis-docker custom-redis-docker

## image stop
- docker stop custom-redis-docker
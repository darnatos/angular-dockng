## Build Development Image
docker build -t dockng:dev --build-arg configuration=development .

## Run Development Container
docker run -p 80:80 dockng:dev

## Build Prod Image
docker build -t dockng:prod .

## Run Production Container
docker run -p 80:80 dockng:dev
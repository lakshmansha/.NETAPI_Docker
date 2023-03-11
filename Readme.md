# DOT NET 7 API

Sample is used for Youtube Video: [**How to Dockerize your .NET Core API**](https://youtu.be/Hm4qWCiNdoY)

For PPT [Click Here](https://www.slideshare.net/LakshmanS10/how-to-dockerize-your-net-core-api)

To Build your docker image,
```sh
docker build -t dotnet7api:dev -f Dockerfile .
```

To Run you docker image,

```sh
docker run --it --rm -p 5260:80 --name dotnet7api dotnet7api:dev
```
# BlazorMicroserviciosPostgreSQL_IMPORTANTE

## How to run the application

1. Run this command to create the ContentPlatform.Api docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-api:latest -f ContentPlatform.Api/Dockerfile .
```

2. Confirm the image was created:

```
docker images
```

3. Login Docker Hub with this command:

```
docker login
```

4. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-api:latest
```

5.  Run this command to create the ContentPlatform.Reporting.Api docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-reporting-api:latest -f ContentPlatform.Reporting.Api/Dockerfile .
```

6. Confirm the image was created:

```
docker images
```

7. Login Docker Hub with this command:

```
docker login
```

8. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-reporting-api:latest
```

9. Run this command to create the contentplatform-ui docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-ui:latest -f ContentPlatform.Presentation/Dockerfile .
```

10. Confirm the image was created:

```
docker images
```

11. Login Docker Hub with this command:

```
docker login
```

12. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-ui:latest
```

13. Press the "Docker-Compose" button in Visual Studio 2022

See the application output

![image](https://github.com/user-attachments/assets/4697bff1-e05d-4baa-9ba2-f891f365b337)


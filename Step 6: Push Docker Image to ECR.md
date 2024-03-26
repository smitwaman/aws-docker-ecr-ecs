1. Go back to the AWS Management Console.

2. In the Amazon ECR console, select your repository from the list.

3. In the repository details, click the “View push commands” button.


4. Follow the provided instructions to authenticate Docker with your ECR registry and push your Docker image.


Retrieve an authentication token and authenticate your Docker client to your registry. Use the AWS CLI:

```
aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 211125656815.dkr.ecr.ap-south-1.amazonaws.com
```

2. Build your Docker image using the docker build command. You can skip this step if your image is already built.

3. After the build completes, tag your image so you can push the image to this repository:

```
docker tag demo-app:latest 211125656815.dkr.ecr.ap-south-1.amazonaws.com/demo-app:latest
```

4. Run the following command to push this image to your newly created AWS repository:
```
docker push 211125656815.dkr.ecr.ap-south-1.amazonaws.com/demo-app:latest
```


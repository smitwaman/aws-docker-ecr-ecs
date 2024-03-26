You can create Repository using AWS management console or AWS cli.

Run the following command to create a new ECR repository using AWS cli. Replace repository-name with your desired repository name.

```
aws ecr create-repository --repository-name your-repository-name

```

Go to AWS management console, then go to Amazon ECR service
![](https://github.com/smitwaman/aws-docker-ecr-ecs/blob/main/images/Step-4/1711426067621459963268144488211.jpg)

In the Amazon ECR console, select “Repositories” from the left navigation pane.

![](https://github.com/smitwaman/aws-docker-ecr-ecs/blob/main/images/Step-4/17114260759301310302018141265097.jpg)
Click the “Create repository” button.
![](https://github.com/smitwaman/aws-docker-ecr-ecs/blob/main/images/Step-4/17114260823451717533507468804597.jpg)
Enter a unique name for your repository in the “Repository name” field.
![](https://github.com/smitwaman/aws-docker-ecr-ecs/blob/main/images/Step-4/17114260883861151632885893087801.jpg)
Click the “Create repository” button.
![](https://github.com/smitwaman/aws-docker-ecr-ecs/blob/main/images/Step-4/17114260947547544927750511048275.jpg)

Repository is created


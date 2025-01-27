# EC2 Image Builder Lab

Objective 

1. Create Image Builder Pipelines for Nginx on Ubuntu image

2. Use Custom Component to build Nginx

3. Submit with the SS of Successful Pipeline

Step 1 : Build the image pipeline in EC2 Image Builder.

![image.png](image.png)

Step 2 : Run the image pipeline and Build Instance for nginx-based-image is being run in EC2.

![image.png](image%201.png)

Workflow for based-image is being processed.

![image.png](image%202.png)

All work flows for based-image are completed.

![image.png](image%203.png)

Workflows for test-image are now being processed.

![image.png](image%204.png)

Instance state of Test instance for nginx-based image is running state.

![image.png](image%205.png)

All workflows for Test-image are now completed.

![image.png](image%206.png)

AMI for nginx-based has been created 

![image.png](image%207.png)

Run the instance by using the created AMI from image builder pipeline.

![image.png](image%208.png)

Nginx server has already been running state in running instance.

![image.png](image%209.png)
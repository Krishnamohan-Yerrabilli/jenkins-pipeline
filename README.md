<div align="center">

# Dockerfile - Configure Webhook - Trigger Jenkins Job - git

</div>

![dgj](https://user-images.githubusercontent.com/58173938/196911210-8f4e96eb-5b4b-4195-81f8-271d41dc1965.png)

### Create a [Dockerfile](https://github.com/Krishnamohan-Yerrabilli/Deployment-on-K8s-cluster-using-jenkins-CI-CD/blob/main/Dockerfile%20-%20Configure%20Webhook%20-%20Trigger%20Jenkins%20Job%20-%20git/Dockerfile/Dockerfile)

And push the Dockerfile to a separate [Repository](https://github.com/Krishnamohan-Yerrabilli/jenkins-pipeline)

### Why we need separate repo?

#### Because it makes it easy to Jenkins to fetch the file(more on this later)

![1-Dockerfile](https://user-images.githubusercontent.com/58173938/196869950-4b9bee5c-885e-456b-8ed1-c0ab2a8b67a4.png)

#### Now login into your Jenkins account

![2-jenkins-login](https://user-images.githubusercontent.com/58173938/196870673-f1b72fa9-64a4-48d1-a6ae-1a1b2cbfb7c9.png)

#### Creating a pipeline, click on the new item

![3-creating-pipeline-new-item](https://user-images.githubusercontent.com/58173938/196874960-598d3ba3-c0f0-487a-ae23-0ba5685dc358.png)


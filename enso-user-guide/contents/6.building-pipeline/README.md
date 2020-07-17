# 6.Building Pipeline



Pipeline is built to integrate all services, models, and custom functions into a solution. 

1. Get inside the pipeline tool. Click on the new pipeline and enter the details such as version, pipeline name

![](../../../.gitbook/assets/image%20%2859%29.png)

  2. Now the pipeline can be created by using various task, service task, and task group with simple drag and drop options.

![](../../../.gitbook/assets/image%20%2860%29.png)

3.         Service tasks are used if there is requirement to use a enso pre-built services or microservices. Tasks are used when we want to integrate custom made model \(pre-processing, post processing\) to the pipeline. Task groups are used when another pipeline is required to be used within a pipeline.

a.               How to use service task: 

Drag and drop the service task block into the platform. Select the task and type the service name on the right-hand pane.

![](../../../.gitbook/assets/image%20%28202%29.png)

In the above screenshot, a service named “extract document entities” is defined in the right panel.

b.               How to integrate a ML Model

Bring a service task block into the platform through a simple drag and drop option. Select the service task block and type run model in the field “Services” on the right-hand side panel. Once the run model is selected, model has to be integrated by providing correct model name from drop down menu as shown in the screenshot.

![](../../../.gitbook/assets/image%20%28110%29.png)

![](../../../.gitbook/assets/image%20%2843%29.png)

c.           How to use a custom function:

Bring a task block into the platform through a simple drag and drop option. Select the required function on the right-hand side panel as shown in the screenshot.

![](../../../.gitbook/assets/image%20%2876%29.png)

4.             Publish and enable the pipeline:

Once the pipeline is built, it needs to be published and enabled. If there are multiple present in a pipeline, then required version needs to be marked as default. Please note that a pipeline needs to be enabled along with the version.

![](../../../.gitbook/assets/image%20%2862%29.png)

![](../../../.gitbook/assets/image%20%28125%29.png)

![](../../../.gitbook/assets/image%20%2826%29.png)

   
5. Modifying a pipeline

  Pipeline can’t be modified in the published version. Any modification in the pipeline can be done by creating a new version. Click on the edit option in a published version of pipeline. Fill the version name & details and submit. Now, after modification in pipeline, it needs to be published by clicking on the publish tab. After a modified pipeline gets published, it must be enabled and set as default.


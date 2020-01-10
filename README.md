# Face-correlation
Display similarity matrix between all faces found in a batch of images.

## This notebook uses Face API Service provided by Microsoft
You first need to own Azure subscription and then follow bellow described steps. <font color='red'>*Below instruction is mostly copied from EDX course "Introduction to Artificial Intelligence (AI)".*</font>

### Create a Face API Service
To provision a Computer Vision API service in your Azure subscription, Follow these steps:

1. Open another browser tab and navigate to https://portal.azure.com.
2. Sign in using your Microsoft account.
3. Click **+ New**, and in the **AI + Cognitive Services** category, click **See all**.
4. In the list of cognitive services, click **Face**.
5. In the **Face** blade, click **Create**.
6. In the **Create** blade, enter the following details, and then click **Create**
  * **Name**: A unique name for your service.
  * **Subscription**: Your Azure subscription.
  * **Location**: Choose the Azure datacenter location where you want to host your service.
  * **Pricing tier**: Choose the F0 pricing tier.
  * **Resource Group**: Choose the existing resource group you created in the previous lab (or create a new one if you didn't complete the previous lab)
  * Read the notice about the use of your data, and select the checkbox.
7. Wait for the service to be created.
8. When deployment is complete, click **All Resources** and then click your Face service to open its blade.
9. <font color='red'> In the blade for your Face service, copy the *full* **Endpoint** URL and paste it into **faceEndpoint** variable **in the notebook**.</font>
10. In the blade for your Face service, click **Keys** and then copy **Key 1** to the clipboard and paste it into the **faceKey** variable assignment value **in the notebook**. 

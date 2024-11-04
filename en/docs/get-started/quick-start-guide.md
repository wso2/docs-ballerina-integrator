## Overview
In this guide, a simple integration will be built using the Kola Integrator plugin for Visual Studio Code. An HTTP service with a single resource (`greeting`) will be created to invoke the public [`HelloWorld`](https://apis.wso2.com/zvdz/mi-qsg/v1.0) API endpoint and return the response.
<a href="{{base_path}}/assets/img/get-started/introduction.png"><img src="{{base_path}}/assets/img/get-started/introduction.png" alt="introduction" width="70%"></a>

### Step 1: Download the Visual Studio Code (VSCode) IDE.
Download and install the Visual Studio Code IDE from [here](https://code.visualstudio.com/download).

### Step 2: Install the Kola VSCode profile.
1. Open the Visual Studio Code IDE.
2. Download and unzip the Kola VSCode profile from [here](https://gist.github.com/kanushka/8d08c83230151840ac22a64fdbe2fb6f/archive/e3facddf34e08ac5c0e4f15b98527354388b6fc1.zip).
3. Navigate to Settings->Profile->Profiles.
4. Click on Profile dropdown and select `Import Profile`.
5. Select the extracted Kola VSCode `Kola.code-profile` profile and click `Create`.
    <a href="{{base_path}}/assets/img/get-started/import-profile.gif"><img src="{{base_path}}/assets/img/get-started/import-profile.gif" alt="Import Profile" width="70%"></a>
6. Navigate to Settings->Profile and select the `Kola` profile from the dropdown.


### Step 3: Setup Kola for the first time.
1. Click on the Kola Integrator icon on the sidebar.
   <a href="{{base_path}}/assets/img/get-started/kola-icon.png"><img src="{{base_path}}/assets/img/get-started/kola-icon.png" alt="Kola Icon" width="70%"></a>
2. Click on the `Setup` button.
3. The setup wizard will install and configure the [Ballerina](https://ballerina.io/) distribution required for Kola.
4. Click on the `Restart VSCode` button to complete the setup.
   <a href="{{base_path}}/assets/img/get-started/kola-setup.gif"><img src="{{base_path}}/assets/img/get-started/kola-setup.gif" alt="Kola Setup" width="70%"></a>

### Step 4: Create a new Integration Project.
1. Click on the Kola Integrator icon on the sidebar.
2. Click on the `Create New Integration` button.
3. Enter the project name as `HelloWorld`.
4. Select Project Directory by clicking on the `Select Location` button.
5. Click on the `Create New Integration` button to create the integration project.
   <a href="{{base_path}}/assets/img/get-started/create-integration.gif"><img src="{{base_path}}/assets/img/get-started/create-integration.gif" alt="Create Integration" width="70%"></a>


### Step 4: Create an Integration Service.
1. In the design view, click on the `Add Construct` button.
2. Select `Service` from the menu.
3. Select `HTTP Service` from the Service Type dropdown.
4. Select `Design From Scratch` option. 
5. Enter the service name as `HelloWorldService`, path as `/hello`, and `9090` as the port.
6. Click on the `Create Service` button to create the new service with the specified configurations.
   <a href="{{base_path}}/assets/img/get-started/create-service.gif"><img src="{{base_path}}/assets/img/get-started/create-service.gif" alt="Create Service" width="70%"></a>


### Step 5: Design the Integration.
1. Now that you have created the service, you can design the integration by adding resources and methods to it. The generated service will have a default resource named `greeting` with a `GET` method.
2. Click on the `greeting` resource to view the resource details. Let's modify the resource to invoke the [`HelloWorld`](https://apis.wso2.com/zvdz/mi-qsg/v1.0) API endpoint.
3. Hover to the arrow after start and click the ➕ button to add a new action to the resource.
4. Select `Add Connection` from the node panel on the left. 
5. Select `HTTP Connection` as the connection type.
6. Change the variable name to `externalEP`.
7. Add the URL `https://apis.wso2.com` to the connection URL field and click `Save`.
   <a href="{{base_path}}/assets/img/get-started/create-connection.gif"><img src="{{base_path}}/assets/img/get-started/create-connection.gif" alt="Create New Connection" width="70%"></a>

8. Click the ➕ button again and select `Connections`->`externalEP`->`Get` from the node panel.
9. Enter the path `/zvdz/mi-qsg/v1.0` in the URL field and click `Save`.
   <a href="{{base_path}}/assets/img/get-started/add-action.gif"><img src="{{base_path}}/assets/img/get-started/add-action.gif" alt="Add Action" width="70%"></a>

10. Click on the ➕ button again and select `Return` from the node panel.
11. Select the `value` variable from the dropdown and click `Save`. This step will return the response from the `HelloWorld` API endpoint.
   <a href="{{base_path}}/assets/img/get-started/add-return.gif"><img src="{{base_path}}/assets/img/get-started/add-return.gif" alt="Add Return" width="70%"></a>

### Step 6: Run the Integration.
1. Click on the `Run` on the run button at top right corner to run the integration.
2. The integration will be compiled and started in the embedded Ballerina runtime.
3. Once the integration is started, you can access the service by navigating to `http://localhost:9090/hello/greeting` in your web browser.
   

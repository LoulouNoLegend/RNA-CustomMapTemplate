The custom map template now has it's own repo instead of being with *CML*.

## Step 1: Unzip the Project Folder
1. **Download the project template** if you haven't already.
2. **Right-click** the `.zip` file and select **Extract All**.
3. Choose a destination for the unzipped folder and click **Extract**. This will unzip the folder with all the project files.

## Step 2: Opening the Project in Unreal Engine
1. Navigate to the folder where you unzipped the project.
2. Locate the `.uproject` file inside the unzipped folder.
3. **Double-click** the `.uproject` file to open it in Unreal Engine 5.2.1 *(You need to have it installed)*.

## Step 3: Renaming Files
### 1. **Rename the Asset Label**
   1. In the Unreal Engine project, open the **Content Browser**.
   2. Locate the asset label inside the `Content` folder.
   3. Right-click the asset and select **Rename**.
   4. Change the name to `Label_YourMapName`, where `YourMapName` is the name of your map.

### 2. **Set a Unique Chunk ID**
   1. After renaming the Asset Label, open the asset by double-clicking it.
   2. Find the **Chunk ID** field in the asset's settings.
   3. Enter a unique number between 1000 and 100,000 for the chunk ID.
   
### 3. **Rename The Level in the CustomMaps Folder**
   1. Navigate to `Content/CustomMaps` in the **Content Browser**.
   2. Right-click the level and choose **Rename**.
   3. Change the name of the level to `CM_YourMapName` *(`YourMapName` is the name of your map)*. It will be what you will need to enter inside a map loader to load the map.
   
### 4. **Rename the Folder**
   1. A folder is placed to contain your map files.
   2. Rename this folder to `Files_YourMapName` *(`YourMapName` is the name of your map)*.

## Final notes and tips:
- Do not touch any other folder than the `CustomMaps` one if you don't know what you are doing.
- Remember to save all your changes a lot *(crashes are never fun!)*.
- Organizing the files and using proper naming conventions makes managing large Unreal projects much easier.

## Download:

# UE_RNBO README

### Link to video tutorial: https://youtu.be/UNz12D4YEYo

### Prerequisites
- Unreal Engine 5.3.2
- Visual Studio
- Max/Msp and RNBO

## Step-by-step Guide to Project Setup

### 1. Download Template Project
https://assets.cycling74.com/rnbo/unreal-engine/example-projects/rnbo.metasounds.testproj-08.13.24.zip

### 2. Create New Unreal Project
- Launch Unreal 5.3.2
- Select Games > Blank template project
	- Under "Project Defaults" Select C++ (not Blueprints)
- Create new project "RNBO_TEST"
- Save and close Unreal Editor and Visual Studio

### 3. Copy Plugin Files to Project Folder
- Navigate to RNBO Template Project Folder
	- copy Plugins folder "~\\rnbo.metasounds.testproj-10.13.23\\rnbo.metasounds.testproj\\RNBOTester\\Plugins"

### 4. Add Plugins folder to New Project
- Navigate to Main folder of RNBO_TEST and paste plugins folder

### 5. Delete old RNBO exports
- Navigate to Exports folder ("~\\RNBO_TEST\\Plugins\\RNBOMetasound\\Exports")
- Delete Contents

### 6. Export RNBO C++ File
- Export RNBO project as C++ Source Code Export to target ("~\\RNBO_TEST\\Plugins\\RNBOMetasound\\Exports")

### 7. Rebuild RNBO_TEST
- Navigate to Main folder of RNBO_TEST
- Open RNBO_TEST.sln
- In Visual Studio Menu > Build > Build All > RNBO_TEST

### 8. Open Unreal Project
- Create new MetaSounds source and locate your new RNBO patch

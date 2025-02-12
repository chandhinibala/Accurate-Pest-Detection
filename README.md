# Accurate-Pest-Detection
**Outline of Project**
The low-power image sensor is an wireless autonomous monitoring system that is based on a low-cost image sensor and allows the farmer to activate pest control in specific areas of their fields that are densely populated with pests, thereby saving the cost and resources to administer the pesticide to the entire field.
Integrated pest management relies on the accuracy of pest population monitoring techniques. At the farm level, human operators typically must perform periodical surveys of the traps disseminated through the field. This is a labor-, time- and cost-consuming activity, in particular for large plantations or large forestry areas, so it would be of great advantage to have an affordable system capable of doing this task automatically in an accurate and a more efficient way.The proposed system will bring higher scalability, being able to deploy in small monitoring areas (greenhouses) as in large plantation extensions.

**Product Functions**
The proposed system should have the following functions:
- 1. **Pest Image Classification**
     - a. Labeling of Image: Shows the names of each pest identified.
     - b. Percentage: Shows the probability percentage of the identified being the pest label.
- 2. **Pest count**
     - a. Count number: Allows user to see the number of pests from each classification
- 3. **Analysis :** 
       - Pest vs Month : A graphical analysis of pest on x-axis and month on y-axis. 
       -  Pest vs Count : A graphical analysis of pest on x-axis and count on y-axis.
- 4. **Measures to control infestation**
       - a. Possible solution: Depending on the severity of the infestation, will tell the user whether pesticide is required at this stage or not. If required, will provide the steps and instructions to execute the measures.

 - **1.Technology constraint:**
     - a. TensorFlow
     - b. Flutter for application
     - c. Firebase


**DEMO VIDEO:**

. -[PEST_CONTROLLER_APP_DEMO](https://drive.google.com/drive/folders/1ElEgGOBm8TQzSfTvOmIQJY77KKqiWHkN?usp=sharing)

**PRESENTATION LINK:**

. -[PRESENTATION_LINK](https://docs.google.com/presentation/d/1urmNG-o4WYp9pegM-LadK7NdNcTtr6w5TnDo1pb8q2E/edit?usp=sharing)

**FILE DESCRIPTION**
1) **Android** - The Android folder contains the files and folders required for the application to run on an Android operating system. These files and folders are generated automatically when the flutter project is created. It is recommended that you consider leaving these folders and files alone.

2) **Assets** - An asset is a file that is bundled and deployed with your app, and is accessible at runtime. Common types of assets include static data (for example, JSON files), configuration files, icons, and images (JPEG, WebP, GIF, animated WebP/GIF, PNG, BMP, and WBMP). We have attached our project related app UI images and pest label files.

3) **ios** - The ios folder contains the Dart files that are required to build an app for the respective platforms. They also assist us in incorporating permissions and platform-specific functionality into our project. In a nutshell, those folders are complete apps that set the stage for the Flutter code to run.

4) **lib** - This is the most important folder in the project, where the majority of the dart code is written. The lib folder contains the main. dart file by default, which serves as the application's entry point. This configuration, however, is modifiable.
Our lib consists of:

- **Login** : all login related dart files. 

- **Signup**: all signup related dart files.

- **Welcome**: all Welcome page related dart files.

- **Graph**: the graphical analysis dart files that are integrated with firestore.

- **Components**: all components such as button and essential UI features related dart files.
                   
- **imagesize.dart**: intergrating firebase data to flutter app.                     
              
- **main.dart**: the main function file of the application.
                    
- **tfpractice.dart** : intergrating tensorflow trained model , drawing detection boxes, into our flutter app.                     
                     
- **viewDetails.dart** : displaying all the details , such as pestname , region ,  count of pest , inference and solution of each detected pest in the app. 
                       
 
5) **Accurate_pest_detection.ipynb** - This is the google collab file where the entire object detection and training of model take place , downloading the Mobilenet SSD v2 Model for our project , cloning our dataset that we annotated in roboflow , running inference , converting tf model to tflite model.

6) **pubspec.lock** - This file lets you test your package against the latest compatible versions of its dependencies.

7) **pubspec.yaml** - Every Flutter project contains a pubspec.yaml file, also known as the pubspec. When you create a new Flutter project, it generates a basic pubspec. The pubspec file specifies project dependencies, such as specific packages (and their versions), fonts, or image files.

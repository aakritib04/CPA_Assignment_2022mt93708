# Tasks List - A cross platform application built with Flutter and Back4App 

## **Assignment Title**: Flutter App with Back4App Integration

## **Assignment Description:** 

  #### In this assignment, I have created a Flutter app that connects to Back4App, a Backend-as-a-Service (BaaS) platform, to manage tasks. 

## **Assignment Github Repository Link :**  
  #### https://github.com/aakritib04/CPA_Assignment_2022mt93708.git

## **Name : Aakriti Bhardwaj** 

## **Roll Number : 2022MT93708**


## **Assignment Steps:**

  ## **Step 1: Set Up Back4App**
  
  ### a.) _Sign up for a Back4App account and Login._
  ![login](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/00caa452-0dd9-4103-b7c2-ea6b9fb4da89)


  ### _b.) Create a new Back4App app_
  ![back4app_login](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a6ccad54-f002-4304-9832-c49205fc3e2e)

  ![back4app_baas](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a1fac1b5-86c2-46bc-9528-91ae80d8df69)


  ### _c.) Create a class in Back4App named Task with columns title (String) and description (String)._
  
  ### Create Class:
   
  ![class](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/2b00a901-a74a-48d1-88d6-c655f9eaae94)

  ### Create Column:
    
  ![back4app 6 (1) columns added](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/dc2b1003-7823-49eb-81da-e9b82d364833)

  ### Class Setup:
  
  ![back4app 6 columns added](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/1ed905bb-d1f3-48ac-92fe-152cfb582d8e)

  ### Dashboard :
  ![dashboard](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/8d00e706-0a7d-4546-9680-999bb0afcbfd)

  ### Class Records:
  ![records](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/7e7e3190-3ca4-4dbb-93b6-dccabe6ba336)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------

    

 ## **Step 2: Flutter Setup**
 
 ### _a.) Download & install Flutter using : https://docs.flutter.dev/get-started/install/windows_
 
 ### _b.) Update Path Variable to be able to use in CMD_
 
 ### _c.) Confirm Installed Tools for Running Flutter_
 
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/63437f3a-6567-4ced-b76d-c9b9991fd3b6)

 ### _d.) Download and install Android Studio using https://developer.android.com/studio/index.html_

 ### _e.) Re-confirm Installed tools for flutter_
 
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/7fb332af-a953-4760-bfe3-53296db80448)

 ### _f.) To resolve issue of:_
  
   #### _i.) 'missing cmdline-tools'_ : open Android Studio and go to SDK Manager, switch to the SDK Tools tab and check Android SDK Command-line Tools (latest)
      
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/d198f46e-e981-4442-844f-f969207f38cd)

  #### _ii.) 'Android licenses'_ : execute  command `flutter doctor --android-licenses`
  
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a2c034c0-8392-4cb0-b8b5-19af9bcc7b9e)

  ### _g.) Re-confirm Installed tools for flutter - successful:_ 

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/5c6b7b9d-6731-4ddf-9cab-cf5c4f314a67)

  ### _h.)Create a new Flutter project using commands:_
  
    % mkdir CPA_Flutter_Assignment
    % cd CPA_Flutter_Assignment
    % flutter create tasks_app
   
   ![setup 1](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/b83685c0-a55a-4849-8054-cf2b66de27ab)

   ![setup 2](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/fe77cb16-d084-4cb1-9b47-abbd7fd25245)

   ### _i.) Confirm Flutter setup:_

     % flutter run

   ![setup 3 flutter setup](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/feb38cde-d5c1-4bd9-9ba3-0b49103a7ec1)


  ### _j.) Add the required dependencies to pubspec.yaml file. Initialize Parse SDK and intl_

    % flutter pub add parse_server_sdk_flutter
    % flutter pub get
   ![setup 5 dependency](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/b240521c-c1e8-4c89-b53a-057ed2924224)

    
    % flutter pub add intl
    % flutter pub get
    
   ![setup 6 dependency](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/ccc9abc2-788f-4fa5-aad2-2e4680e08a06)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------


  
 ## **Step 3: Task List**

  ### Create a screen in your Flutter app to display a list of tasks. Implement a function to fetch tasks from Back4App using the Back4App API. Display the tasks in a list view with titles and descriptions.
  
  ### _Refer `Class TaskListScreen` in lib/main.dart_

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/fb00cdf2-a7f9-460b-9faf-612f16492c6e)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Step 4: Task Creation**

  ### Create a screen for adding new tasks. Implement functionality to create and save tasks to Back4App.Verify that newly created tasks appear in the task list.

  ### _Refer `Class TaskCreationScreen` in lib/main.dart_

  ![create](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/c3b946d7-2397-4d57-bd7c-c3f3ed491dde)

  ### Task Creation:

  ![create 1](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/21690c2c-304e-43fd-be0f-21fa42b17568)

  ### Post task creation:

  ![post create](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a6a84bba-247f-4b20-a7c4-f05c89ae132d)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Step 5: Task Details**

  ### Add a feature to view task details when a task is tapped in the task list.Display the title and description of the selected task.

  #### _Refer `Class TaskDetailsScreen` in lib/main.dart_

  ![task display](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/47d50d0c-03c0-4feb-ae8c-343a80605bd2)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------




 ## **Step 6: Bonus Features** 
 
  ### a.) _Feature to edit and update existing tasks_

   ### Refer `Class TaskUpdateScreen` in lib/main.dart

   #### Before Update
       
   ![before update](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/c4f3e9c9-9b4e-49d5-852a-1a04b5205f2f)

   #### After Update

   ![after update](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/3a0f66b4-ee2c-488c-9499-dd2dd6ded05a)



   ### _b.) Implement a feature for task deletion._

   #### Refer `Future<void> deleteTask` in lib/main.dart

   #### Before Delete

   ![before delet](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/d3a345bd-ef27-4096-a332-e19f0485c19f)


   #### On Delete

   ![during delete](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/0768cbd5-29d4-4b24-8aa7-a4b943787fc7)


   #### Post Delete

   ![after delete](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/e857f5d5-0ff4-445d-a13d-d0e05fb54884)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------



  ## **Step 7: Additional Features/Enhancements** 

   ### -	**Color coding** - For Tasks with status as `todo`, those tasks are colored as `Red` and for Tasks with status as `complete`, those tasks are colored as `Green`

   ![color](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a064ff32-0968-4d1e-ba1e-08d9e13a21b1)

     
   ### -	**Order of Tasks** -  The newly created tasks are appended at the last of the Todo tasks and the completed tasks are ordered on the basis of latest completed task at the top.

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/35e24868-0b55-49bf-b3b5-29028e7f9d8b)

   ![complete order](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/97aa95d8-f430-465e-a025-437c079c119a)

   


   ### -	**Refresh button** - Button to reload the tasks list

   ![refresh](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/f0f319b1-97b1-4a07-ac4a-9df9f57f026d)


   ### -	**Status** - Added status information for each tasks and status gets toggled based in selected checkbox along with color change based on status

   ![status](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/328a6c3f-dfd5-4931-8dfe-a41cadc2e8c3)


     
   ### -	**Strick Off** - Todo to complete tasks gets stricken off

  ![strick](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/d98be7fc-ac3f-442a-8491-20f5df455025)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Additional Details:** 

  ### a.) To Launch on emulator:
  
     % flutter emulators --launch Pixel_4_XL_API_34
     % flutter run

   ![emulator](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/ff823b7f-e4f9-4413-9671-ff69e3de7945)

     

   ### b.) To run on devices:
   
      % flutter devices
      % flutter run –d chrome

   ![chrome](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/5471bb00-616b-4529-af6b-bcafc09e1378)


   ### c.) To demonstrate Cross-Platformness of the application:

   ![crossplatform](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/006c799f-3d37-47fe-8df8-cf51107207fb)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------


## **References:**

- https://www.back4app.com/docs/flutter/parse-sdk/data-objects/flutter-crud

- https://www.liquidweb.com/kb/how-to-install-and-configure-flutter-sdk-windows-10/

- https://pub.dev/packages/parse_server_sdk_flutter/install

- https://stackoverflow.com/questions/68236007/i-am-getting-error-cmdline-tools-component-is-missing-after-installing-flutter

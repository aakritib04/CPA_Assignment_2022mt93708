# Tasks List - A cross platform application built with Flutter and Back4App 

## **Assignment Title**: Flutter App with Back4App Integration

## **Assignment Description:** 

  #### In this assignment, I have created a Flutter app that connects to Back4App, a Backend-as-a-Service (BaaS) platform, to manage tasks. 

## **Assignment Github Repository Link :**  
  #### https://github.com/aakritib04/CPA_Assignment_2022mt93708.git

## **Roll Number : 2022MT93708** 


## **Assignment Steps:**

  ## **Step 1: Set Up Back4App**
  
  ### a.) _Sign up for a Back4App account and Login._
  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/f0ee092f-0a35-4ddc-8028-93011cc49c0a)

  ### _b.) Create a new Back4App app_
  ![back4app_login](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/42467567-b8e1-40a2-a839-f0a91a602d9d)
    
  ![back4app_baas](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a5decb00-8ed1-4e16-bbd6-56865849d760)


  ### _c.) Create a class in Back4App named Task with columns title (String) and description (String)._
  
  ### Create Class:
   
  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/319507d7-d9ed-483e-8981-28350b05c700)

  ### Create Column:
    
  ![back4app 6 (1) columns added](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/9ffb0135-63ba-4d49-bf2c-613cb9178f21)

  ### Class Setup:
  
  ![back4app 6 columns added](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/c0844ce2-3173-42d6-89d3-245ecaffabd8)

  ### Dashboard :
  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/9106b67d-304f-4c7f-9227-eb3f8d18256d)

  ### Class Records:
  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/2e0a2be9-0604-41c8-9975-f36fc096dd75)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------

    

 ## **Step 2: Flutter Setup**
 
 ### _a.) Download & install Flutter using : https://docs.flutter.dev/get-started/install/windows_
 
 ### _b.) Update Path Variable to be able to use in CMD_
 
 ### _c.) Confirm Installed Tools for Running Flutter_
 
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/d2794f93-068a-4a6a-9305-8a305fdac0d4)

 ### _d.) Download and install Android Studio using https://developer.android.com/studio/index.html_

 ### _e.) Re-confirm Installed tools for flutter_
 
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/156c6c4e-3090-41fe-a0ce-93111aa14e65)

 ### _f.) To resolve issue of:_
  
   #### _i.) 'missing cmdline-tools'_ : open Android Studio and go to SDK Manager, switch to the SDK Tools tab and check Android SDK Command-line Tools (latest)
      
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/6e263467-494e-4770-918d-65c7eff5c62a)

  #### _ii.) 'Android licenses'_ : execute  command `flutter doctor --android-licenses`
  
   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/94c93f3f-e93e-42cf-8776-89478c0be1b6)


  ### _g.) Re-confirm Installed tools for flutter - successful:_ 

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/45abd250-d4b4-4fab-bc2d-3bd334ea1846)

  ### _h.)Create a new Flutter project using commands:_
  
    % mkdir CPA_Flutter_Assignment
    % cd CPA_Flutter_Assignment
    % flutter create tasks_app
   
   ![setup 1](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/82f2c08d-1b58-4a52-be45-c431fd07f9e0)
   ![setup 2](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/786acca1-3507-4ce9-b4f8-f49186bc8e1e)

   ### _i.) Confirm Flutter setup:_

     % flutter run

   ![setup 3 flutter setup](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/e1cd717b-0bee-4aea-bd4a-34ca02c5bc6b)


  ### _j.) Add the required dependencies to pubspec.yaml file. Initialize Parse SDK and intl_

    % flutter pub add parse_server_sdk_flutter
    % flutter pub get
   ![setup 5 dependency](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/dee43565-9123-47f1-90ea-fa3ab349d6ef)

    
    % flutter pub add intl
    % flutter pub get
    
   ![setup 6 dependency](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/6940d6e6-c5c8-4392-9c04-043e67a35393)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------


  
 ## **Step 3: Task List**

  ### Create a screen in your Flutter app to display a list of tasks. Implement a function to fetch tasks from Back4App using the Back4App API. Display the tasks in a list view with titles and descriptions.
  
  ### _Refer `Class TaskListScreen` in lib/main.dart_

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/756ea667-d960-43ce-a373-bb7dc45cade9)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Step 4: Task Creation**

  ### Create a screen for adding new tasks. Implement functionality to create and save tasks to Back4App.Verify that newly created tasks appear in the task list.

  ### _Refer `Class TaskCreationScreen` in lib/main.dart_


  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/30b96a0e-37a2-4cf6-89ea-653ea3c0ffb1)

  ### Task Creation:

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/bd09f327-82fc-4afa-ac13-cbd54053834a)

  ### Post task creation:

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/e951c7b7-8482-4309-9adc-9ee49dcb8745)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Step 5: Task Details**

  ### Add a feature to view task details when a task is tapped in the task list.Display the title and description of the selected task.

  #### _Refer `Class TaskDetailsScreen` in lib/main.dart_

  ![task display](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a94e4c5c-1916-4237-bec2-fa4cd7bf7704)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------




 ## **Step 6: Bonus Features** 
 
  ### a.) _Feature to edit and update existing tasks_

   ### Refer `Class TaskUpdateScreen` in lib/main.dart

   #### Before Update
       
   ![before update](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/4e253514-1921-4de6-8eb3-81419ebcb8b8)

   #### After Update

   ![after update](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/4e925f81-4350-4784-8050-a5812054a295)


   ### _b.) Implement a feature for task deletion._

   #### Refer `Future<void> deleteTask` in lib/main.dart

   #### Before Delete

   ![before delet](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/e3bde4a1-4bb9-4665-8c38-26c252270b69)

   #### On Delete

   ![during delete](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/be9a9c27-46ee-41da-ab28-04a4cb8756a3)

   #### Post Delete

   ![after delete](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/7a7a24a0-f9d2-4d73-a629-5530bae4e6d3)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



  ## **Step 7: Additional Features/Enhancements** 

   ### -	**Color coding** - For Tasks with status as `todo`, those tasks are colored as `Red` and for Tasks with status as `complete`, those tasks are colored as `Green`

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/8be705ed-1e9d-477b-a85e-205385d781b2)
   

     
   ### -	**Order of Tasks** -  The newly created tasks are appended at the last of the Todo tasks and the completed tasks are ordered on the basis of latest completed task at the top.

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/34ee2bf0-c713-430f-802f-0e08bb570d98)

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/3d3eb0d5-1fb2-4684-bc3e-98ee0cb57755)
   


   ### -	**Refresh button** - Button to reload the tasks list

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/b8ed7b4e-12e5-4662-aa65-9dbb523d742b)
   

   ### -	**Status** - Added status information for each tasks and status gets toggled based in selected checkbox along with color change based on status

   ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/c2e458fd-6834-458b-918d-6403c6cfcf6b)
   

     
   ### -	**Strick Off** - Todo to complete tasks gets stricken off

  ![image](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/048ee7c3-f6d0-471c-9a1b-c0da36dea2a1)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------



## **Additional Details:** 

  ### a.) To Launch on emulator:
  
     % flutter emulators --launch Pixel_4_XL_API_34
     % flutter run

   ![emulator](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/cc7823b5-57cb-4166-a51c-984895f87ea6)

     

   ### b.) To run on devices:
   
      % flutter devices
      % flutter run –d chrome

   ![chrome](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/8f3c486c-9658-4b76-ade6-06c40bcb3071)


   ### c.) To demonstrate Cross-Platformness of the aaplication:

   ![crossplatform](https://github.com/aakritib04/CPA_Assignment_2022mt93708/assets/146528030/a1a2dd08-9fd9-42bc-a4ce-e84172e6c40a)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------


## **References:**

- https://www.back4app.com/docs/flutter/parse-sdk/data-objects/flutter-crud

- https://www.liquidweb.com/kb/how-to-install-and-configure-flutter-sdk-windows-10/

- https://pub.dev/packages/parse_server_sdk_flutter/install

- https://stackoverflow.com/questions/68236007/i-am-getting-error-cmdline-tools-component-is-missing-after-installing-flutter

# GitignoreAutomationUnity3D

*create-u3d-gitignore.sh* is a bash script developed to quickly create a .gitignore file inside your Unity3D project. The script was developed to be integrated with .bashrc.


## How to integrate with .bashrc?

1) Clone this repository into your machine;
2) Open your .bashrc using your favorite text editor. It's usually under ~/.bashrc;
3) Create an alias for the create-u3d-gitignore.sh file:
    1) The command structure should be: ```alias + your_desired_command_name="cd PATH/TO/CLONED/REPOSITORY + && + ./create-u3d-gitignore.sh"```;
    2) The final result should look similar to this: ```alias create_unity3d_gitignorefile="cd ~/Downloads/GitignoreAutomationUnity3D && ./create-u3d-gitignore.sh"```. Considering you cloned the repository directly into your 'Downloads' folder;
    3) Save and close your ~/.bashrc;
    4) Execute the following command on your terminal: ```source ~/.bashrc```;
4) Navigate to your Unity3D project folder using terminal;
5) Execute the command you created previously inside the project;
6) If there are no errors or warnings, you should have a .gitignore file inside your project folder;


## Executing

When executing this file, you should receive several messages while the script add contents to your .gitignore file.

After adding the default value, you'll be prompt with the following message: **Would you like to add 'unitypackage' to your .gitignore file? [1] Yes - [0] No.**. Select your option and press enter. This will guarantee that exported unitypackages will not be ignored.


## Contributing

1. Fork the repository on Github;
2. Clone the project into your machine;
3. Commit your changes to your own branch;
4. Push your work to your fork;
5. Submit a pull request for review;


## Copyright

This project is under Apache 2.0 license.

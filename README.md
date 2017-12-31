# GitignoreAutomationUnity3D

GitignoreAutomationUnity3D is a shell script developed to quickly create a .gitignore file inside your Unity 3D project. This script was developed to be integrated with .bashrc and allow a quick bash command set-up.


## How to integrate with .bashrc?

1) Clone this repository into your machine;
2) Open your .bashrc file. It's usually under ~/.bashrc;
3) Create an alias for the create-u3d-gitignore.sh file:
    1) The command structure is: ```alias + command_name="cd PATH/TO/REPOSITORY/FOLDER + && + ./create-u3d-gitignore.sh"```;
    2) The final result should look similar to this: ```alias create_unity3d_gitignorefile="cd ~/Downloads/GitignoreAutomationUnity3D && ./create-u3d-gitignore.sh"```. Considering you cloned the repository directly into your 'Downloads' folder;
    3) Save and close your ~/.bashrc;
    4) On terminal, execute: ```source ~/.bashrc```;
4) Navigate to your Unity3D project folder using terminal;
5) Execute the command you created previously inside the project;
6) You should now have a .gitignore file inside your project folder;


## Contributing

1. Fork the repository on Github;
2. Clone the project into your machine;
3. Commit your changes to your own branch;
4. Push your work to your fork;
5. Submit a pull request for review;


## Copyright

This project is under Apache 2.0 license.

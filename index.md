# What is the terminal? Why is it an important tool for a web developer?
####The terminal is a text-based window inside of a GUI that is used for entering commands to your file system. The way it works is by entering your commands which in tern will then come back with a displayed output of your command. The terminal is used for a multitude of things like navigating through your files whether your trying to find something or running text based applications like python or C++. Just about anything you can do in the drag and drop UI for your file system (mines windows so the file explorer) you can do in the terminal like creating files, copying files, moving files and so forth.

#### The terminal is a very important tool for a developer because whether you want to or not you will use it at points throughout your developement life. Within most text editors now you will have an option of using a terminal within their and as we just learned will help us use npm or other package managers you will use. On that same note you may also use the CLI to commit changes made to code for git, or even just changing your remote repo for a project, and among many other things. Sure you could use the GUI and may be easier to use but when your able to understand the terminal it can be faster and more efficient for large projects.
![terminal](https://user-images.githubusercontent.com/97576252/213946641-d20a0caa-1e3b-46dd-8575-e3edf8843119.jpg)

# For you, what are some important built-in commands to know. What do they do, and why are they important? (At least 5)
## 1. **cd** 
#### One you'll definitely end up using is cd (change directory). This one allows you to do what the acronym implies, which is changing your directory into another one. The way you would do this if you wanted to move up one directory and is referred to as the "parent directory"
`cd ..` 
Now if you just wanted to cut to the chase and go straight to the root directory where the OS is, you can use this
`cd /`
Now going up the directory is easier than going down the directory due to there being many different branches, if you wanted to go down it would be much easer to do this `cd <file path>`
``` 
PS C:\> cd Users\10919
# output
PS C:\Users\10919>
````

## 2. **mkdir**
#### This one can be useful for creating your dev projects as it allows you to create a new folder
`mkdir <folder name>`

## 3. **ls**
#### This will show me what files or content is in the directory I am currently in. It is also very self explanatory why it is important, because it allows you to know whe files are in there, and what if there is a file that you accidentally put in there or created by accident you can check using ls.
![ls](https://user-images.githubusercontent.com/97576252/213948278-75480107-485c-4c12-a04a-20aac201f637.jpg)
It will also tell me the last time I made changes to it, what the file names are in there, and the mode.

## 4. **clear** 
#### clear is one of my favorites because I hate scrolling when using the terminal and seeing a bunch of text can also be distracting to what I need to do next. So, this one is very straight forward and you would just type clear and it will clear all previous commands and the outputs.
![before](https://user-images.githubusercontent.com/97576252/213951638-8b12441b-8a64-4e32-8c84-bc1965ad3858.jpg) ![after](https://user-images.githubusercontent.com/97576252/213951731-a94f28ae-c17b-46cf-95ed-9c205b323093.jpg)

## 5. **man**
#### This one is also another useful one for me when your brain is scattered or you don't remember the command, you can use "man". When you enter man it will give you a mutli page "dictionary" on commands we can execute on the terminal. ![man](https://user-images.githubusercontent.com/97576252/213954135-85672fea-fb9d-49c5-99e2-8eedd6df9160.jpg)

# What is the root?
#### The root in the linux system is the super user, typically this is disabled for added security which can be accessed by the sudo command before your following command. Another way this may also be explained is root also sit at the top of the file system. It will often be shown as your operating system or in my case since I am windows it will be (C). ![root](https://user-images.githubusercontent.com/97576252/213955448-85c478d2-7120-4c8b-ae2b-19f3849259eb.jpg)

# What is the path?
#### The path is just like breadcrumbs on a website to show you where you are within your tree like file system. ![path](https://user-images.githubusercontent.com/97576252/213956300-fa5a2ce3-49fc-48f6-9906-22b492a9ea74.jpg)
#### Within this image you will see the root directory is (C) my OS, then we moved into the users folder containing all users on this computer, then we go into a specific folder, and then continue into another folder. It shows the location we are but also shows you where that file is located.


# What is the present working directory?
#### The current working directory is the directory in which you are currently working in. When you notice the path displayed in the terminal that is the directory which you are enacting commands to. To make it short, the present working directory is the file your currently sitting in within the terminal. If you are deep within your file system the very end of your path is where you are currently located. In this example the present working directory will be "cabot_cruises" folder.![path](https://user-images.githubusercontent.com/97576252/213958133-a1342bd9-3a37-4f7e-80cc-84ad562a18d6.jpg)


# What is the bin? How does it work?
#### The bin is located in the file system but more specifically it is located inside the root directory. The bin folder is where all the executable files for your programs and scripts are stored, it is also where all the commands for the terminal are located. When a program is installed those files are generally copied to the bin folder. 


# Write about at least two new things you have personally learned about the command line.
#### Since I have just tried out the LSW for my windows system I was unaware of some of the linux based commands and I am in love with the touch command. Windows wont let me do that but it will let me make folders which to me doesn't make a whole lot of sense. However, I am still working on my understanding of the linux terminal so I'm sure there will much more to learn in the future. 
#### I am one of those guys who typically stays away from the terminal because I am a little intimdated by it, but the more I look it seems a little less intimidating. There are commands that make doing certain things much easier that using the GUI, like shutting down the computer, restarting, hiding files, even creating files and folders, which for me is a plus because I know at times my file explorer will act up and I can't even access it. So, knowing these commands I can just cut straight to the chase and create what I need without having to wait for the GUI to show me the files in that directory and it if it successfully was created.

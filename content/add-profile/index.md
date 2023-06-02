---
title: Adding your profile
summary: Instruction to add an user on the mlgh webpage
date: "2023-06-02T00:00:00Z"

reading_time: true # Show estimated reading time?
share: false  # Show social sharing links?
profile: true  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
---
- First thing is to fork the website [repository](https://github.com/MLGlobalHealth/starter-hugo-research-group)
- Clone the fork on your local machine. Let us assume the directory you have cloned is named `base_dir` 
- Next is to install hugo for local development. You can find instructions  at this [page](https://gohugo.io/installation/). You may skip this page if you are not looking to have a local version, this will just not let you preview how you changes would look on the website.
- Now go to the `base_dir` using the shell of you r choice on your local computer.
![Use Shell](add_person_1.png "Mac OS Sheel after cloning the repo.")
- To add a new user run the following command `hugo new content/authors/firstname-lastname` . Remember to change first and last names as the name you want for yourself (surely you can be Swapnil and want to be known as Samir/Seth that can be benefecial :P )
- This will create a new folder `firstname-lastname` inside  `content/authors/`
- Now you can open the whole folder in a text editor of your choice and navigate to the file `content/authors/firstname-lastname/_index.md`
- Please fill in the details in this file as per your requirement. most of the stuff is self explanatory. In case of any issues raise a concern on zulip
- Only thing to know is that in area with `user_groups` the allowed values are:
    - Principal Investigators
    - Researchers
    - Grad Students
    - Administration
    - Visitors
    - Alumni
- Delete `avatar.jpg` in your folder and replace with a file with pic you want to be displayed. Remember you need to have the name of the file as `avatar.jpg/avatar.png`.
- This is how it look on vscode for reference
![Text Editor View](add_person_2.png "VSCODE view of the repo and added new folder.")
- Now go back to terminal and to the `base_dir` and run `hugo serve`
![Hugo Serve View](add_person_3.png "View of the terminal after running hugo serve.")
- This will display you changes on a localhost as informed on the terminal. Open that local host to see your changes 
![Changed website](add_person_4.png "Your changes on the local host.")
- If you are  happy then press `ctrl+c` to stop
- Now delete the the public directory. The command for unix systems is `rm -rf public`
- Commit your changes and push it to your fork
- Now submit a PR to the MLGH repository when happy 
- If you want to add other content than authors you can have a more detailed look at  [Wowchemy Documentation](https://wowchemy.com/docs/getting-started/) for Hugo themes. Nothing more sophisticated than adding appropriate markdown files.

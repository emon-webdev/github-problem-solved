# github-problem-solved
Github related any issue solved in this repository.


## List of github problems:
- [GithubCollaboration](#GithubCollaboration)
- [fataLRemoteOriginAlreadyExists](#fataLRemoteOriginAlreadyExists)
- [originSetUrl](#originSetUrl)


### GithubCollaboration

```js
// change branch
git checkout (your branch name)
or
git pull origin (your branch name)

//
======= Github Collaboration Docs =======

step 1:
create repository  
step 2: 
echo "# Github-Collaboration" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/emon-webdev/Github-Collaboration.git
git push -u origin main

step 3: 
// your cmd
git checkout -b branchName

// Example
Emon_Hossain@DESKTOP-GAQCCLA MINGW64 /d/Github Collaboration (main)
 git checkout -b branchName
Switched to a new branch 'branchName'
// branch name (main change branchName)
Emon_Hossain@DESKTOP-GAQCCLA MINGW64 /d/Github Collaboration (branchName)

step 4: 
// change code and select branchName than see update
git push --set-upstream origin branchName


step 5:
Pull requests
New Pull requests
base:Main < compare: your branch select
create pull requests
again create pull requests
Merge pull requests
Confirm Merge

========================
// Collaboration and workflow (group project access other people)

step 1: 
create a new repository

step 2:
//
add collabortors
way: 
your project Settings > COllaborators > Add People (search username / email (demo))
Click Add people 
check his(demo) eamil / gitHub notification
Accept Invitation

step 3:
//demo works project
//clone project
git clone https://github.com/emon-webdev/Github-Collaboration.git

step 4: 
//create development branch
git checkout -b development
git push --set-upstream origin development

step 5:
//create homepage branch
git checkout -b homepage/emon
git push --set-upstream origin homepage/emon

step 5:
//create loginpage branch
git checkout -b loginpage/demo
git push --set-upstream origin loginpage/demo

// সব কিছু development branch রাখতে হবে এবং pull করতে হবে development branch থেকে  main branch এ হাত দিব না
// development branch থেকে নিলে merge conflict করবে না
// best practice development branch push/ merge করার আগে development branch থেকে তুমি pull করে নিবা। যাতে 
কেউ  development branch code update করলে conflict না করে।
// 
step 6:
Pull requests
New Pull requests
base:development (অবশ্যই development select korte hobe ) < compare: your branch select (homepage/ loginpage)


step 7:

===============================
Resolving Merge Conflicts
// same line 2 code 




```

### fataLRemoteOriginAlreadyExists

```js
// Problem
if you have (fatal: remote origin already exists.)
// Solved
rm -rf .git

```
### originSetUrl

```js

// step 1 
$ create you repository
// step 2
$ git remote set-url origin (your origin url)
// step 2
git remote -v (comfirm your origin)

// step 3

```

### Delete node_modules

```js

git rm -r --cached node_modules
git add .
git commit -m "removed"
git push

```



### Table
<div class="overflow-x-auto">
  <table class="table w-full">
    <!-- head -->
    <thead>
      <tr>
        <th></th>
        <th>Name</th>
        <th>Describe</th>
        <th>Favorite Color</th>
      </tr>
    </thead>
    <tbody>
      <!-- row 1 -->
      <tr>
        <th>1</th>
        <td>origin check</td>
        <td>git remote -v</td>
        <td>Blue</td>
      </tr>
    </tbody>
  </table>
</div>



## 🌐 Socials: Connect with Emon Hossain!

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.com/emonhossain6) [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emon007iu/) [![Twitter Badge](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@emon_hossain7) [![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emon.hossain.wd@gmail.com)

<h4>❤️🤔 You can follow my Github and other social accounts 🤔❤️</h4>
<h2>❤️ Thank you very much! ❤️</h2>

```



### Table
<div class="overflow-x-auto">
  <table class="table w-full">
    <!-- head -->
    <thead>
      <tr>
        <th></th>
        <th>Name</th>
        <th>Job</th>
        <th>Favorite Color</th>
      </tr>
    </thead>
    <tbody>
      <!-- row 1 -->
      <tr>
        <th>1</th>
        <td>Cy Ganderton</td>
        <td>Quality Control Specialist</td>
        <td>Blue</td>
      </tr>
      <!-- row 2 -->
      <tr>
        <th>2</th>
        <td>Hart Hagerty</td>
        <td>Desktop Support Technician</td>
        <td>Purple</td>
      </tr>
      <!-- row 3 -->
      <tr>
        <th>3</th>
        <td>Brice Swyre</td>
        <td>Tax Accountant</td>
        <td>Red</td>
      </tr>
    </tbody>
  </table>
</div>



## 🌐 Socials: Connect with Emon Hossain!

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.com/emonhossain6) [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emon007iu/) [![Twitter Badge](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@emon_hossain7) [![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emon.hossain.wd@gmail.com)

<h4>❤️🤔 You can follow my Github and other social accounts 🤔❤️</h4>
<h2>❤️ Thank you very much! ❤️</h2>

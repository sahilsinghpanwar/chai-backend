models links: [https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj];


step:1--------- (git branch -M) jo bhi branch hoge git per uska name change kr sakhte h  jaise git (branch -M main)
tb ye main show hoga source control per,  aab hum main brach mai aa gye h 


step:2-------- then we se remote in git bash (git remote add origin https://github.com/sahilsinghpanwar/chai-backend.git)
remote bhi add ho gya h aab


step:3------ then upstream it command(git push -u origin main)

or ye sara ka saara code push bhi kr deya



this all command given by github, your repository 



step:4------ create public/temp/.gitkeep

step:5------ create .gitignore file (jo hume push ne krne github pe)


step:6------ jo packages ya file hume push ne krne github pe toh website (gitignore generator  main node search kro) or usse jo package ya file hoga usko add krdo .gitignore mai


step:7------- create .env



aage koi file create krne ho kisi folder kai under toh 
commands ======>  cd src (folder ka name);
                  ls 
                  touch app.js constants.js index.js (creation of files)



step:8---package.json mai import krange files ko add krna hoga
two types ke importing hote h js mai
1) common.js
2) module




again files ko save krange github pe
use command 
git add .
git commit -m "setup project files - part 1"
git push

step:9------- src kai under folder create krne k liye we use this commands cd src, ls then go to step:10

step:10-----  folder create karne kai liye we use  mkdir command  or aage ke command mai files ka naam hoga
use command ----> mkdir controllers db middlewares models routes utils


step:11----- insall prettier
command(npm i -D prettier) and also add file .prettierrc

step:12----- also add file .prettieignore (jo files hume add ne krne)
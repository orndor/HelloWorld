# My first hello world project on Github

This is my first project on github. Isn't it great?

```bash
git init
dotnet new console

echo "obj/" >> .gitignore
echo "bin/" >> .gitignore

git add .

git config --global user.email "rorndoff@gmail.com"
git config --global user.name "Rob Orndoff"
git commit

git remote add origin git@github.com:orndor/HelloWorld.git

git push -u origin master
```

git init
git add README.txt
git commit -m "add readme"

git remote add origin https://github.com/cwook0/chatbots.git
git push origin master

git clone https://github.com/cwook0/chatbots.git .
git checkout master

git add README.txt
git push origin master
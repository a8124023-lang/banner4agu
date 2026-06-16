# banner4agu
#!/bin/bash

echo "********************************"
echo "*                              *"
echo "*      Welcome to AGU          *"
echo "*                              *"
echo "********************************"

chmod +x bannercmd.sh

git clone https://github.com/あなたのユーザー名/banner4agu.git

cd banner4agu

cp ../bannercmd.sh .

git add bannercmd.sh
git commit -m "Add bannercmd.sh"
git push origin main

 1016  mkdir  ssha
 1017  cd ssha/
 1018  ;s =;
 1019  ls -al
 1020  echo "# sasha" >> README.md
 1021  git init
 1022  git add README.md
 1023  git commit -m "first commit"
 1024  git remote add origin https://github.com/feget/sasha.git
 1025  git push -u origin master
 1026  ls -al
 1027  cd ..
 1028  ls -al
 1029  git clone https://github.com/feget/sasha.git
 1030  ls -la
 1031  cd sasha/
 1032  ls -la
 1033  vim README.md 
 1034  git status
 1035  git commit -m "Add word"
 1036  git push
 1037  git add  README.md 
 1038  git add  --all
 1039  git commit -m "new"
 1040  git push
 1041  ?? -??
 1042  ls -al
 1043  rm README.md 
 1044  ls -al
 1045  git pull
 1046  ls -al
 1047  cd ..
 1048  ls -la
 1049  cd ssha/
 1050  ls -al
 1051  git status
 1052  gi pull
 1053  git pull
 1054  ls -la
 1055  vim README.md 
 1056  cd ..
 1057  ls -al
 1058  cd sasha/
 1059  ls -al
 1060  git status
 1061  git add --all
 1062  git commit -m "delete all"
 1063  git push
 1064  ??? ???
 1065  git log
 1066  git checkout ca669fca7b0d3389edb3c038ba2d6370817896b8
 1067  ls -al
 1068  vim README.md 
 1069  git checkout 5c26511ae9b8595b95b3931b044e0614255673a2
 1070  vim README.md 
 1071  git push
 1072  ls -a
 1073  ls -al
 1074  git branch
 1075  git branch issue1
 1076  git branch
 1077  git checkout issue1
 1078  ls -al
 1079  vim README.md 
 1080  git status
 1081  git add --all
 1082  git commit -m "sdfsdaf "
 1083  git push origin issue1
 1084  git branch -a
 1085  git checkout issue1
 1086  git checkout master
 1087  vim README.md
 1088  ls -al
 1089  git add --all
 1090  git commit -m   "create file"
 1091  git push
 1092  vim README.md 
 1093  git pull
 1094  vim README.md 
 1095  history 


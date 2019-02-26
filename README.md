# hello-world
Testing

https://guides.github.com/activities/hello-world/

# 測試分支(master)

by 網址內文中第3步

# TOC 目錄

- [hello-world](#hello-world)

- [測試分支(master)](#測試分支master)

- [本地 -> 遠端](#本地---遠端)

- [**將專案資料夾建立成 git repository (初始化git)**](#將專案資料夾建立成-git-repository-初始化git)

- [**將檔案加入 git 此例為加入README.md(git add . 為加入此目錄下所有檔案)**](#將檔案加入-git-此例為加入readmemdgit-add--為加入此目錄下所有檔案)

- [**加入暫存區 並註記**](#加入暫存區-並註記)        - [**設定遠端結點**](#設定遠端結點)


# 本地 -> 遠端

### **將專案資料夾建立成 git repository (初始化git)**
    
    git init

### **將檔案加入 git 此例為加入README.md(git add . 為加入此目錄下所有檔案)**
    
    git add README.md

### **加入暫存區 並註記**
    
    git commit -m "new code"

### **設定遠端結點**

    git remote add origin git@github.com/ZhongIan/hello-world.git

    說明：

    1. git remote 指令，顧名思義，主要是跟遠端有關的操作。
    2. add 指令是指要加入一個遠端的節點。
    3. 在這裡的 origin 是一個「代名詞」，指的是後面那串 GitHub 伺服器的位置。

### **推送至遠端**

    git push -u origin master

    1. 把 master 這個分支的內容，推向 origin 這個位置。

    2. 在 origin 那個遠端 Server 上，如果 master 不存在，就建立一個叫做 master 的同名分支。

    3. 但如果本來 Server 上就存在 master 分支，便會移動 Server 上 master 分支的位置，使它指到目前最新的進度上。

    4. 設定 upstream，就是那個 -u 參數做的好事，這個稍候說明
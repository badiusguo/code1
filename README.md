# code1
git绑定测试

git 从github同步repository:
	      git clone(https:..github.com/badiusguo/repo name.git


不同repo的pull 和push要在子文件夹中进行
                  
git 指定从github下载文件的路径及pull文件指令：
                      git remote add origin git@github.com:badiusguo/repository name.git
                      git pull git@github.com:badiusguo/repository name.git


git 将文件上传到github:其中，在本地更改后上传，（git add . 和git commit -m " "一定要加，否则新内容无法同步至github)
                      git add .
                      git commit -m "说明"
                      git push git@github.com:badiusguo/repository name.git
                      
                      
git 允许pull不同repo下的文件
                      git pull origin master --allow-unrelated-histories





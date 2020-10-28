# GithubCheckoutMethod
这是上传自己代码+整合代码到主分支的操作步骤

git checkout develop
git pull origin develop
git checkout -b dev-tsj origin/develop
git checkout feature-user-security + 修改文件

git checkout feature-user-security ./src/main/java/com/controller/AuthorityController.java
git checkout feature-user-security ./src/main/java/com/dao/AdminDao.java
git checkout feature-user-security ./src/main/java/com/pojo/Permission.java
git checkout feature-user-security ./src/main/java/com/service/AdminConfigService.java
git checkout feature-user-security ./src/main/java/com/service/impl/AdminConfigServiceImpl.java
git checkout feature-user-security ./src/main/java/com/utils/EmailUtils.java
git checkout feature-user-security ./src/main/resources/mapper/AdminMapper.xml

git add . 
git commit 
git rm -r  .idea
git 切换
git merge --no-ff
git push origin develop

this is a new file
github is a free software
it is helpful for us

git add : add the modify to the index
git commit : save the modify to the master

8:30 2020/8/16
git commit:commit message
commit message include:1.header 2.body 3.footer
1.header 包括 type(needed),scope(unnecessary),subject(needed)
{
  type:
  1.feat:新功能（feature）
  2.fix:修补bug
  3.doc:文档
  4.style:格式（不影响代码运行）
  5.refactor:重构
  6.test：增加测试
  7.chore:构建过程或辅助工具变动
  scope:
  scope用于说明commit的影响范围
  subject:
  commit目的的简短介绍，第一个字母需要小写，结尾不加.	
}
2.body
{
  body是对本次commit的详细描述
}
3.footer
{
  1.不兼容变动:
  如果与上个版本不兼容，可以开头添加breaking change，后面是对变动的描述，以及变动理由和迁移方法
}

# MySQL三件套 <br>
插播一则广告：作为一名大数据学生，你还在因数据匮乏感到焦虑吗？还在因为MySQL空空如也感到鸡肋吗？为了解决这个问题正是我写这个项目的原因。<br> 
本项目包括python爬虫，数据导入MySQL，数据导出<br>

## Spider <br>
基础功能：输出地址，即可在指定地址处生成爬取的数据，以csv文件呈现。 <br>

版本： <br>
1.0: 豆瓣读书Top250（包括：排名，书籍，封面，作者，时间，时间（无月日），出版社，评分， <br>
评价人数，售价（元））。 2023-12-17<br>
1.1: 增加豆瓣电影Top250（包括：排名，电影导演，主演，时间，国家，类型，评分，评价人数，评语）。 <br>
增加B站【每周必看】（包括：排名，视频名，作者，IP地址，摘要，观看网址，观看次数，点赞数，收藏数， <br>
投币数，转发数）。2023-12-24 <br>

## 导入向导 <br>
基础功能：连接到数据库，自定义表格，支持列名修改，支持数据类型修改，支持主键创建。<br>

版本：<br>
1.00: 将csv文件导入MySQL, 使用之前最好先打开MySQL。 <br>
1.15: 不必再导入全部列了，支持列自定义删除。优化用户体验。修复部分bug。 2023-12-20<br>
1.25: 支持导入excel表格。主键可以不必定义。支持数据类型选择性的修改。增加输入输出的容错性。 2023-12-24<br>
1.29: 1.25画饼太大，导致bug频出，在此进行进一步修改，支持导入常见的excel后缀（包括：'.xls', '.xlsx', '.xlsm', '.xlsb', <br>
'.odf', '.ods', '.odt', '.csv'）。增加容错性。 2023-12-27<br>

## 导出向导<br>
基础功能：连接数据库，需要会使用基础的SELECT语句，可导出查询的数据，支持多表查询，支持数据预览。 <br>

版本：<br>
1.18: 增加导出excel格式。目前可同时导出csv和xlsx文件。修复部分bug。 2023-12-23<br>

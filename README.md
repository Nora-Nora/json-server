<!-- get请求 -->
//获取所有用户信息
http://localhost:3000/users

//获取id为1的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取公司id为3的公司信息
http://localhost:3000/companies/3

//获取所有公司中id为3的用户
http://localhost:3000/companies/3/users

//根据公司名来获取信息
http://localhost:3000/companies/?name=Microsoft

//根据多个公司名来获取信息
http://localhost:3000/companies/?name=Microsoft&name=Apple

//获取一个页面中只有个信息
http://localhost:3000/companies/?_page=1&_limit=2

//根据给定值进行升序排序(asc)和降序排序(desc)
http://localhost:3000/companies/?_sort=name&_order=asc

//获取用户中年龄在20以上的
http://localhost:3000/users?age_gte=20

获取年龄在20到25的用户信息
http://localhost:3000/users?age_gte=20&age_lte=25

//搜索用户信息
http://localhost:3000/users?q=tom

//运行命令行
npm run json-server
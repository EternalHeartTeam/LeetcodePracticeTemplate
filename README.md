# LeetcodePracticeTemplate
A template project to use leetcode-practice......

## Usage

### 1. first step - install dependency

The only one dependency is `leetcode-practice`.

```shell
# run npm i 
npm i 
# or run yarn
yarn
```
### 2. second step - use npm run to run

And then, you only need to run the command `npm run lc` to create the question today.

```shell
# run lc to create
npm run lc 
```

and you can see the console, and the question be created at the directory `src`.

```shell
yarn run v1.22.19
$ lc -d src
MODE: today
题目[2235.将标题首字母大写]获取成功!
题目文件地址为:file:///Users/mac-106/wh131462/workspace/LeetcodePracticeTemplate/src/2235.capitalize-the-title/question.js:35
✨  Done in 2.96s.
```

### 3. third step - check your resolution

Just run the command `npm run lk`.

```shell
# run lk to check
npm run lk
```

and you can see(the example is empty code):

```shell
yarn run v1.22.19
$ lk -d src
MODE: today
题目[2235.将标题首字母大写]检测结果:
┌────────────┬──────────────────────────────────────────┬──────────────────────────────────────────┬────────────┬────────────┐
│  测试结果  │                 预期结果                 │                 执行结果                 │  执行用时  │  内存占用  │
├────────────┼──────────────────────────────────────────┼──────────────────────────────────────────┼────────────┼────────────┤
│   未通过   │          "Capitalize The Title"          │                                          │  0.5894ms  │  2.42 KB   │
│   未通过   │       "First Letter of Each Word"        │                                          │  0.0182ms  │  2.56 KB   │
│   未通过   │            "i Love Leetcode"             │                                          │  0.0087ms  │  2.56 KB   │
└────────────┴──────────────────────────────────────────┴──────────────────────────────────────────┴────────────┴────────────┘
点击跳转到题目提交: https://leetcode.cn/problems/capitalize-the-title/
✨  Done in 0.36s.
```

### 4. forth step - if you want to search

If you want to search one question , you can use the `lf`.

```shell
# run lf to search
npm run lf
```
and then follow the hints to search what you want.
```shell
# such as I want to find the question two number of sum
yarn run v1.22.19
$ lf -d src
? 请选择查找的模式? 关键词搜索
? 请输入关键词 two number sum
? 请选择题目 1.两数之和
1
MODE: identity
题目[1.两数之和]获取成功!
题目文件地址为:file:///Users/mac-106/wh131462/workspace/LeetcodePracticeTemplate/src/1.two-sum/question.js:30
✨  Done in 13.68s.
```

## More...

If you want to know more about the leetcode-practice. Please check the github : [leetcode-practice](https://github.com/EternalHeartTeam/leetcode-practice)
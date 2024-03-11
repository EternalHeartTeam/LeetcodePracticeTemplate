# Leetcode Practice Template

A template project for using LeetCode practice.

## Usage

### 1. First Step - Install Dependencies

The only dependency is `leetcode-practice`.

```shell
# Install dependencies with npm
npm i 

# Or with yarn
yarn
```

### 2. Second Step - Run with npm

After installing dependencies, run the command `npm run lc` to create today's question.

```shell
# Create today's question
npm run lc 
```

You will see the console output, and the question will be created in the `src` directory.

```shell
yarn run v1.22.19
$ lc -d src
MODE: today
题目[2235.将标题首字母大写]获取成功!
题目文件地址为:file:///Users/mac-106/wh131462/workspace/LeetcodePracticeTemplate/src/2235.capitalize-the-title/question.js:35
✨  Done in 2.96s.
```

### 3. Third Step - Check Your Solution

To check your solution, run the command `npm run lk`.

```shell
# Check solution
npm run lk
```

You will see the results (the example shows an empty code):

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

### 4. Fourth Step - Search

To search for a question, use `lf`.

```shell
# Search for a question
npm run lf
```

Follow the prompts to search for what you want.

```shell
# For example, searching for the two number sum question
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

## More Information

For more information about `leetcode-practice`, please check the GitHub repository: [leetcode-practice](https://github.com/EternalHeartTeam/leetcode-practice)
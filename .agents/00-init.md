# 初始化

- 检查ref-projs下的项目是否存在，如果不存在则git clone对应的仓库
  - ref-projs/teaql-agent-kit    https://github.com/teaql/teaql-agent-kit

- 如果是claude环境，完成如下检查并初始化
  - 检查.claude/skills是否目录链接指向.agents/skills，如果没有，则创建该目录链接

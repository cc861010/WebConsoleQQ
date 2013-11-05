## WebConsoleQQ
* 描述：一个基于webQQ的ConsoleQQ
* 背景：chrome中的console已经成文了继移动平台之后的另一个新的战场，
      中国互联玩的三巨头阿里，百度，腾讯已经开始行动了，为此推出consoleQQ，LOL
* 用法：
   * f():查询所有好友
     输出格式：
        [0,好友名称0]
        [1,好友名称1]
        [2,好友名称2]
   * f('好友名称1'):查询名称为'好友名称1'的好友
     输出格式：[0,好友名称1]
   * l():查询所有接收消息
   * l(0):显示'好友名称1'的所有消息
   * s('a message',0):向 '好友名称1' 发送一条消息，消息正文为：a message
* 依赖平台 [node-webkit](https://github.com/rogerwang/node-webkit)



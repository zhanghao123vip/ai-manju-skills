# AI 漫剧 Skills

21 个题材的 AI 漫剧全流程模板。发一句故事点子，就能得到企划案、资产图提示词、分集剧本、分镜图与视频提示词，以及发布文案。

每个模板都是一个 `SKILL.md` 文件，不需要安装任何依赖，可以用在 Claude Code、WorkBuddy，也可以直接粘贴到 DeepSeek 等聊天工具。

## 题材列表

| 分类 | 题材 | 文件 |
|---|---|---|
| 幻想 | 玄幻修仙 | [xuanhuan-manju](skills/xuanhuan-manju/SKILL.md) |
| 幻想 | 西幻魔法 | [xihuan-manju](skills/xihuan-manju/SKILL.md) |
| 幻想 | 星际机甲 | [xingji-manju](skills/xingji-manju/SKILL.md) |
| 幻想 | 系统无限流 | [xitong-manju](skills/xitong-manju/SKILL.md) |
| 幻想 | 末日废土 | [moshi-manju](skills/moshi-manju/SKILL.md) |
| 古代 | 穿越重生 | [chuanyue-manju](skills/chuanyue-manju/SKILL.md) |
| 古代 | 宫斗 | [gongdou-manju](skills/gongdou-manju/SKILL.md) |
| 古代 | 宅斗 | [zhaidou-manju](skills/zhaidou-manju/SKILL.md) |
| 古代 | 权谋朝堂 | [quanmou-manju](skills/quanmou-manju/SKILL.md) |
| 古代 | 武侠江湖 | [wuxia-manju](skills/wuxia-manju/SKILL.md) |
| 古代 | 种田经商 | [zhongtian-manju](skills/zhongtian-manju/SKILL.md) |
| 现代 | 都市逆袭 | [dushi-manju](skills/dushi-manju/SKILL.md) |
| 现代 | 总裁甜宠 | [tianchong-manju](skills/tianchong-manju/SKILL.md) |
| 现代 | 家庭伦理 | [jiating-manju](skills/jiating-manju/SKILL.md) |
| 现代 | 重生复仇 | [chongsheng-manju](skills/chongsheng-manju/SKILL.md) |
| 现代 | 职场商战 | [shangzhan-manju](skills/shangzhan-manju/SKILL.md) |
| 现代 | 年代文 | [niandai-manju](skills/niandai-manju/SKILL.md) |
| 现代 | 娱乐圈 | [yule-manju](skills/yule-manju/SKILL.md) |
| 现代 | 大学校园青春 | [xiaoyuan-manju](skills/xiaoyuan-manju/SKILL.md) |
| 类型片 | 悬疑刑侦 | [xuanyi-manju](skills/xuanyi-manju/SKILL.md) |
| 类型片 | 民俗怪谈 | [minsu-manju](skills/minsu-manju/SKILL.md) |

## 怎么用

### DeepSeek 等聊天工具
1. 打开对应题材的 `SKILL.md`，复制全部内容。
2. 开一个新对话，粘贴发送。
3. 它回复"模板已就绪"后，发一句故事点子。

一部剧用一个对话，一个对话只用一个模板，否则容易串设定。

### Claude Code
把需要的题材文件夹复制到 `~/.claude/skills/`，然后直接发故事点子。

### WorkBuddy
如果你的版本支持导入 Skill，就导入对应文件夹；不支持就按聊天工具的方法整段粘贴。

## 常用指令

| 你说 | 它做 |
|---|---|
| 一句故事点子 | 输出立项卡和企划案 |
| 继续 | 写当前阶段的下一批，写完后进入下一阶段 |
| 第3集手册 | 写第3集的资产图和镜头 |
| 第3集发布包 | 写第3集的封面和文案 |
| 改：女主改成冷面师姐 | 只改相关部分，并检查前后是否矛盾 |

## 输出内容

1. **企划案**：故事、人物、世界体系、逐集剧情、伏笔、美术、声音、发布
2. **资产库**：人物、道具、场景、特效的出图提示词
3. **分集剧本**：分场与逐字对白
4. **分集导演手册**：本集资产图、分镜图提示词、分时段视频提示词
5. **发布包**：封面提示词、片尾与预告方案、发布文案

默认 30 集、每集约 4 分钟、9:16 竖屏，可以在点子里指定别的。镜头数和时长不固定：每个题材有自己的节奏，每集再按内容调整。

内容较长，所以分批输出，每批开头标明进度，回复"继续"写下一批。能直接写文件的工具可以连续写完，文件结构写在 `SKILL.md` 第一章。

## 使用前请注意

- **测试状态**：当前版本已在 WorkBuddy 实测通过；此前玄幻修仙版经过实际使用测试，宫斗、宅斗、年代文、系统无限流、总裁甜宠、重生复仇、职场商战做过安装校验或阶段1试跑；其余题材尚未逐一实测。
- **视频工具**：提示词里的 `{{Mixed N}}` 是参考图的引用写法，换工具时请改成对应写法。
- **上线合规**：发布前请按所在平台的规则确认内容，并标注 AI 生成内容。悬疑刑侦、民俗怪谈等题材平台要求较多，请先确认。
- **原创**：模板要求人物和设定全部原创。生成内容的版权与合规责任由使用者自行承担。

## 许可证

[MIT](LICENSE)

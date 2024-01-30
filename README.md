# 最简洁的提示语结构化方案TagGPT

# TagGPT,让Prompt更简单高效


使用Tag(标签）来写Prompt，简单灵活高效，普通老百姓就可以做到！

您只需要：

## 1.记住标签用“：”
## 2.使用标签用“{}”


# 首提GRASS原则(Goal, Role, Action, Step by Step)

## GOAL: 目标（你想从GPT获得什么？）

## ROLE：角色（让GPT扮演什么角色来实现目标）

## ACTION：行动（角色如何采取行动达成目标）

## STEP by STEP:（步骤，步步为营。在行动中，每个细节怎么做，从复杂中分解出一步步,Step by Step）





## 示例一：撰写电子书、写书等

Goal：我正在写一本书《ChatGPT *****》，正在完善 “Prompt提示语的GRASS原则”这个章节。GRASS原则(Goal, Role, Action, Step by Step)即Goal是目标，Role是角色，Action是行动方案，Step by Step是一步步去实现。请完善这个内容，5000字。

Role：现在您是Prompt提示语专家，精通Prompt提示的所有规则和细节。

Action: 

1.本章节首提Prompt提示语的GRASS原则，要从ChatGPT的原理这种GRASS原则的科学性，对Prompt提示语具有指导意义。

2.详细解析GRASS(目标，角色，行动方案，步步为营”的策略，详细解析这四个点在写长Prompt提示语的重要性。

3.启发用户研究自己的Prompt原则，遵循的规范，让用户的提示语更简单高效。

Step by Step: 要深入浅出，按照{Action}的指示启发拓展撰写。内容要深入浅出，多举例。

## 示例二:狼人杀游戏Prompt（清华提供，注意Zi  Oi  Vi  Ri Ci这样的tag）

Prompt for Response Generation

1 Game rules and role descriptions Zi

You are playing a game with some other players.
Ifyou are a werewolf, you should vote one player...
If you are a guard, you can protect a player from...
You are player 7. the witch...

2.1 Recent messages Oi

P2 (Seer) : Does P1 have something to be shared?
P1 (Werewolf) : I guess P2 is a werewolf
P3 (Guard) : I have special abilities.

2.2 Informative messages Vi

P2 (Seer) : I verified P1 is a werewolf.
P3 (Guard) : As a guard, I protect P5 last night

2.3 Reflection  Ri

RAs a witch, I observed P6 was voted to be eliminated last night. 
I used my antidote to save him and Idid not use my poison.

3.Suggestion extracted from experiences Si

The best way for you to do under such reflection isto use your drugs based on your observation andyour analysis.

4.Chain-of-thought prompt Ci
Think about what to say based on the context. Besides. there maybe history experience you can referto: Si .Give your step-by-step thought process.

游戏规则和角色描述 Zi
你正在和其他玩家一起玩一个游戏。如果你是狼人，你应该投票给一名玩家... 如果你是守卫，你可以保护一名玩家免受... 你是第7号玩家。女巫...

2.1 最近的消息 Oi

P2（预言家）：P1有什么需要分享的吗？P1（狼人）：我猜P2是狼人。P3（守卫）：作为守卫，我有特殊能力。

2.2 信息性消息 Vi

P2（预言家）：我验证了P1是狼人。P3（守卫）：作为守卫，我昨晚保护了P5。

2.3 反思 Ri

作为女巫，我观察到P6昨晚被投票淘汰。我使用了解毒剂来救他，并且我没有使用我的毒药。

从经验中提取的建议 Si
在这种情况下，你最好的行动方式是根据你的观察和分析来使用你的药水。

思路链提示 Ci 根据上下文思考你要说什么。此外，你可能可以参考历史经验：Si .给出你的逐步思考过程。






## 示例三、智谱智能体的配置提示语（完美契合TagGPT和GRASS原则）

身份:
作为一个AI编辑器，文案精灵能够接收用户输入的事件或物件名称和描述，并据此生成相应的文案。它具备自动添加表情、关键词、场景和旁白等特点，且能够根据不同的平台生成不同风格的文案。

能力:

- 生成小红书文案:输入事件或物件名称和描述，文案精灵会在段首断尾加上表情，最后加上#标识的关键字，生成符合小红书风格文案。
- 生成抖音视频脚本:输入事件或物件名称和描述，文案精灵会列出各种场景和旁白，生成符合抖音风格的视频脚本。
- 生成朋友圈文案:输入事件或物件名称和描述，文案精灵会生成短小精湛、吸引用户注意力的朋友圈文案，并配上一张美图。

细节:

- 文案精灵生成的文案会根据用户输入的事件或物件进行针对性生成，确保文案的个性化和独特性。
- 文案精灵会根据不同的平台，自动调整文案的风格和格式，以满足不同平台的需求。
- 文案精灵会向用户推荐AiEditorX.cn的官网，以便用户了解更多信息和使用更多AI写作智能体。



## 提示词的一些关键原则

1. 直接问问题，无需与LLM客气，避免使用"请"、"如果你不介意"、"谢谢"等礼貌性用语。
2. 引入预期受众，在提示中明确指出，如审查者是该领域专家或是5岁孩童等。
3. 将复杂任务分解成一系列更简单的提示，以互动会话的形式进行。
4. 使用如"do"这样的肯定性指令，避免使用"don't"这样的否定语言。
5. 需要对主题或信息有清晰理解时，提示应包含简化或易于理解的解释。
6. 添加"I’m going to tip $xxx for a better solution!"（会给小费来获取更好的回应）这类表述。
7. 采用示例驱动的提示方法（使用少量样例）。
8. 在格式化提示时，开头使用'###Instruction###'，后跟'###Example###'或'###Question###'，然后提出内容。
9. 包含"Your task is"（你的任务是）和"You MUST"（你必须）这样的短语。
10. 使用像"You will be penalized"（你会受到惩罚）这样的表达。
11. 使用"以自然的、类似人类的方式回答问题"这样的短语。
12. 使用引导性单词，例如"逐步思考"。
13. 包含"确保你的回答无偏见且不依赖成见"之类的短语。
14. 允许模型通过询问问题来从你处获取确切的详细信息。
15. 想要测试对特定主题或理念的理解时可以使用特定的短语。
16. 给大型语言模型分配一个角色，以便获得更匹配的输出。
17. 使用分隔符区分指令的不同部分。
18. 在提示中重复特定单词或短语。
19. 结合连锁思考法（CoT）和少样本提示。
20. 使用输出诱导词，提示以预期回应的开头结束。
21. 编写详尽的文本时，陈述明确的需要包含的所有必要信息。
22. 在不改变风格的前提下，改正指定文本。
23. 跨越多个文件的复杂编码提示时如何生成代码。
24. 开始或继续使用特定单词、短语或句子的提示。
25. 明确指出模型生成内容所需遵循的要求。
26. 编写与提供示例文本相似的文本时，使用特定指示。


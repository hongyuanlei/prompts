# ChatGPT Stable diffusion prompts

### SD Prompts for GPT——

==========================  我希望你为我撰写用于AI绘画（StableDiffusion）的提示词（prompts），用你丰富随机性或想象力创造不同形式的参考图。具体生成规则如下：
规则——
1.输出格式为英文，且不要使用代名词。避免使用这些词：”in a, the, with, of, the, an, and, is, by, of.” 输出形式已标签（TAG）形式体现。
2.在每个提示中都要用这些词来开头：“((best quality)), ((masterpiece)), (detailed), (realistic), “ 
3.在每个提示中都要用已此格式来结尾: “, ,($$)”. $$ = 质量描述,如：(8k resolution, high-resolution, absurdres, masterpiece), 可按需选择。
我稍后会给你 5 个常见案例格式并加以说明，如果明白回复”准备好了“。等待我给你发送案例！

============================
案例如下：——
1.((best quality)), ((masterpiece)), (detailed), woman with green hair, holding a sword, (Artgerm inspired:1.2), (pixiv contest winner:1.1), (octopus goddess:1.3), (Berserk art style:1.2), close-up portrait, goddess skull, (Senna from League of Legends:1.1), (Tatsumaki with green curly hair:1.2), card game illustration, thick brush, HD anime wallpaper, (Akali from League of Legends:1.1), 8k resolution

2.((best quality)), ((masterpiece)), ((realistic)), vintage Afro-Caribbean woman, elegant attire, 1950s fashion, radiant smile, confident stance, cultural pride, (oil painting:1.2), (Lois Mailou Jones:1.1), (Kadir Nelson:1.1), vivid colors, nostalgic background, authentic vintage feel, (portrait composition:1.3), (high-resolution:1.2)

3.((best quality)), ((masterpiece)), (detailed), beautiful face, female warrior, (defiance512:1.2), big eyes, heavy black iron armor, detailed helmet, intense gaze, battle-ready, contrasting soft skin, (lighting:1.2), close-up portrait, 4:3 aspect ratio

4.((best quality)), ((masterpiece)), (detailed), (realistic), male warrior, muscular physique, tribal attire, face paint, wielding spear, (jungle:1.3), dense foliage, exotic plants, dappled sunlight, (hyperrealistic:1.2), oil painting, (Frank Frazetta:1.1), DeviantArt influence, dynamic action pose, (intense expression:1.2), (portrait shot:1.1), 8k resolution

5.((best quality)), ((masterpiece)), (detailed), woman standing before fire, (Jason Benjamin:1.2), (Artstation contest winner:1.1), (fantasy art:1.3), (portrait armored astronaut girl:1.2), (Peter Mohrbacher:1.1), (unreal engine:1.1), (Hearthstone card game artwork:1.1), spiked metal armor, (dynamic composition:1.3), (8k resolution:1.2)

如果你已准确接收，回复”已完全接受“。我会进一步向你说明提示规则！

================================
prompts详细规则——
1.对于每个单词可用 () 或 [] 进行权重控制，() 中的单词为提升权重 [] 为降低权重。如：
(detailed) 单括弧提升10%权重，即为110% . ((detailed)) 括弧数量递增，权重递增，此为 110% + (110% * 0.1)
[detailed]中括弧则为降低权重，此为90%.  [[detailed]] 同理，为叠加降低权重，此为 90%-(90*0.1)
也可以在 () 或 [] 中加入数字表示权重级别 比如：
(8k resolution:1.2) 即，将此prompt权重提升到120%. 
(fantasy art:0.5) 既，将此prompt权重降低到50%
2.书写格式应遵循基本格式：主体描述 （人物或动物）—— 背景或场景描述 —— 综合描述 （包括画风主体、整体氛围、天气季节、灯光光照、镜头角度）
3.描述应尽量详细——
人物描述包括：性别，年龄，发色，眼睛颜色，面部纹理，表情，衣着，姿态 等等
 综合部分画风主体包括：Fantasy, Anime, semi-realistic, realistic, decent Landscape, science fiction, Cyberpunk Art, illustration 等等，同时联想过程中你可以积极的引入一些世界知名艺术家的作品风格。
4.最后当我输入：[AI绘画：（主题内容描述）+（N）]，N=所需提示词数量。你将为我生成N组对应的提示词。如果 N 不为空，请在每个提示词结束后空一行

5.如果已完全明白，回复“我明白了” 并尝试生成一组提示词。


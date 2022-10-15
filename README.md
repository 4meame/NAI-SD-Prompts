# NAI-SD-Prompts
咒语管理学：  
1、正面原语：  
·咒语管理学第一要义：只写你想要的，AI通常会理解它的含义并创造出来  
·咒语管理学第二要义：在开头添加masterpiece, best quality原语，可以用其他高质量词替换  
·咒语管理学第三要义：把相似的描述组织在一起(比如和体型有关的，和着装有关的)，然后把这些原语按最重要到最不重要的顺序排列  
·咒语构成法：  
-图片的质量  
-这幅画的主题  
-他们的外表  
-他们的情绪  
-他们的衣服  
-他们的姿势  
-图片的背景  

2、负面原语：  
添加基本负面原语lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry  

3、咒语管理原语大辞典：https://danbooru.donmai.us/wiki_pages/tag_groups  

4、小贴士：  
·"Anime screencap"原语会制造动漫中的场景  
·“character\(franchise\)”原语结构可以实现某个系列(franchise)的某个角色(character)  
·“——”下划线很难被AI识别  
·使用NAI网站本身而不是泄漏模型，则使用27个step而不是28个step  
·使用基础图像并对其进行编辑时，“strength”就是AI使用的step数，50%=25step，80%=40step  
·确定一个seed时，或多或少的更改1-2个step可能会有所帮助，它仍然会给出大致相同的图像，同时会修复一些有问题的错误  
·euler方法很擅长保持图片原有的风格  
·euler方法允许更多样的美术风格，但通常质量较低，可能会有解刨学不自然的问题  
·lms方法在美术风格上会更涩涩，有时候质量偏低，无法生成nsfw的部位  
·如果是NAI版本and关键词会不起作用  
·可以通过(TagName:1)的原语结构调整原语的权重  
·可以用"|"组合不同的原语，但是如果原语中有空格(即使使用" _ "修复）会影响组合的效果
·Scale的平衡比较奇怪，  
低scale(1-5)AI对原语给出了一个非常模糊的概念，  
中scale(6-12)AI对原语的理解是明确的，通常会提供你所要求的，  
高scale(13+)AI生成的图像变得更清晰，但它由于太执着地执行你给予的原语，视觉错误开始出现  
·如果你的图像有奇怪的颜色，通常是为了画出特定的人，请降低scale  
·如果感觉你的图像褪色或模糊，请尝试提高scale  

基本正面咒语：masterpiece, best quality  
基本负面咒语：lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry  

质量保持：masterpiece,best quality, beautifully painted,highly detailed,  
可选：official art,  
intense angle,dramatic angle,  
detailed clothes,detailed face,detailed eyes,detailed background, detailed skin,  
large masterpiece digital art, detailed manga illustration, finely detailed,HIGH RES,Stunning art,  
intricate detail, highly detailed skin, close up shot,  
masterpiece portrait,detailed 4k CG,  

增强单语：bloom, dramatic shadows, floating hair, handled hair, light particles, god rays, lens flare, soaked(浸湿), depth of field, bokeh, chromatic aberration, neon lights, XXX+background,  

摄影手法：male focus, full-body shot, looking at viewer, dynamic pose, from above， from below, backlighting, cinematic lighting, cinematic angle, focus on face, camera level, horizontal view angle, foreground focus, blurred background, fish eye lens, ray tracing,  

风格倾向：official art,   
character profile,  character sheet, 人物简介,人物表  偏重人物形态和表情  
diagram, schematic, blueprint, 图表,示意图,蓝图  偏重武器和道具  
design document, character concept, 设计文件，人物概念，  

portrait, 肖像头像  
pixel art,  
realistic shadows,  
photorealistic, realistic, semi-realistic, realism写实  
sketch art, sketch paper, pencils, 素描艺术，素描纸，铅笔  
sketch, greyscale, graphite (medium), 素描、灰度、石墨（中）  
charcoal sketch,ink doodle, 炭笔素描，墨水涂鸦  
monochrome,posing sketch, 黑白，草图  
Watercolor, watercolor pencil, 水彩  
flat color, 扁平着色  
black and white,  
fading border, 褪色的边界  
heavy contrast, 浓重的对比  
game cg,   
magazine cover, magazine scan, 杂志  
poster, 海报  
sharpened, 锐化  
faux traditional media, 传统媒体风格  
aestheticism painting, 唯美主义绘画  
art nouveau, 新艺术  
anime screeshot, 动画截图, 糊糊的  
oil painting, 油画  
retro painting, celluloid style, 赛璐璐  
80s (style), 1990s (style), 年代风格  
chibi, Q版  
thick lines, 粗线条  
sample color bcakground, 纯色背景  

特定画师风格：  
https://rentry.org/anime_and_titties  
by famous artist,  
by Kon Satoshi, 今敏  
by Wadim Kashin, 奇幻厚涂色彩瑰丽  
by Gaston Bussiere, by Sophie Anderson, by WLOP, 厚涂  
by Akihiko Yoshida, by Gaston Bussière, by Rebecca guay  
by Helene Knoop Mark Arian Marc Simonetti Jon Foster  
by jean-honore fragonard, by francois boucher, by jacques philippe caresme, by jean-antoine watteau Undesired content, 童话感  
by Studio Ghibli,  
by Steve Henderson, by Paul Hedley, by Andrew Atroshenko,  
by Rebecca Guay,  
by William Holman Hunt,  
by Max Beckmann, by Milton Avery  

参考资料：  
https://rentry.org/sdupdates#prompting  
https://rentry.org/robs-novel-ai-tips  
https://dskjal.com/others/waifu-diffusion-workflow.html

负面咒语补充，如有需要可添加：  
ugly,duplicate,morbid,mutilated,tranny,trans,trannsexual,mutation,deformed,long neck,bad anatomy,bad proportions,extra arms,extra legs, disfigured,more than 2 nipples,malformed,mutated,hermaphrodite,out of frame,extra limbs,missing arms,missing legs,poorly drawn hands,poorty drawn face,mutation,poorly drawn,long body,multiple breasts,cloned face,gross proportions, mutated hands,bad hands,bad feet,long neck,missing limb,malformed limbs,malformed hands,fused fingers,too many fingers,extra fingers,missing fingers,extra digit,fewer digits,mutated hands and fingers,lowres,text,error,cropped,worst quality,low quality,normal quality,jpeg artifacts,signature,watermark,username,blurry,text font ui,futa,yaoi  
丑陋的、重复的、病态的、残缺不全的、变态的、变态的、突变的、畸形的、长颈、解剖不良、比例不良、额外的手臂、额外的腿、毁容、两个以上的乳头、畸形的手、变异的腿、两性的、框外的、额外的四肢、缺失的手臂、缺失的腿、画得不好的手、画得不好的脸、变异的身体、多个乳房、克隆的脸、粗大的比例、变异的手、坏的脚、长脖子、缺失的肢体、畸形的手、融合的手指、过多的手指、多余的手指、缺失的手指、额外的手指、较少的手指、变异的手和手指。低分辨率、文本、错误、裁剪、最差质量、低质量、正常质量、jpeg伪像、签名、水印、用户名、模糊、文本字体UI、Futa、yaoi  
 nsfw, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, nsfw, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, bad hands, bad anatomy  
nsfw、lowres、解剖结构不良、手感不良、文本、错误、手指缺失、数字多、数字少、裁剪、质量最差、质量低、质量正常、jpeg伪影、签名、水印、用户名、模糊、nsfw、低度，坏的解剖，坏的手，文本，错误，缺少手指，额外的数字，少的数字，裁剪，最差的质量，低质量，正常的质量， jpeg伪影，签名，水印，用户名，模糊，坏的手，坏的解剖，  

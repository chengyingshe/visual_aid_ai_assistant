# visual_aid_ai_assistant

## 项目介绍

基于 InternLM 的视障人群视觉辅助项目。利用语音识别、文字转语音等技术基于开源多模态大语言模型开发一个能够利用摄像头采集的环境图像和文字输入等信息生成对话来帮助改善视力残疾人士的生活。

欢迎大家也来参加书生大模型实战营项目：http://github.com/internLM/tutorial

## 项目目标

1. OCR文字识别：通过图片输入和对话请求，模型能够识别图片中的文字内容，并利用TTS技术进行播报

2. 场景理解：通过图片输入和对话请求，模型能够识别图片中的场景内容，并能够通过多轮对话详细描述图片中的场景内容

3. 路线规划和导航：能够根据图片输入和用户的需求，为用户生成规划路线并进行室内（甚至室外）导航

   > 目标识别->SLAM定位->路径规划->实况语音播报

4. 信息检索：接入互联网或特定的知识库，根据对话要求检索信息并生成回答

   


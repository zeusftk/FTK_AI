# FTK_AI 项目介绍

## 项目概述  
FTK_AI_Auto（Fast Toolkit AI Automation）是一款功能强大的多媒体处理与自动化工具集，专注于视频、音频处理及智能剪辑。  

该工具集成多项先进AI技术，覆盖视频、音频、剪辑全流程处理，核心能力包括 **✨ AI剪辑、AI特效、智能配音** 等。其内置横竖屏分类、场景切片、动作片段提取、字幕添加、音色转换等实用功能，支持 **🚀 开箱即用零配置**。  

针对12G显存设备与Mac M系列芯片深度优化，可精准释放硬件性能，让AI驱动的多媒体创作高效流畅。

## windows版本
下载地址:https://pan.baidu.com/s/1vQplT_mcC6upgnl9NRsrzA?pwd=q68x

## 🔥 Latest Upate!!
* 2025-08-01: 👋 v6.03 已发布，添加视频外补功能，位于 【视频批量转绘】 中 修改视频长宽比 模式。添加【视频批量人物动作迁移】功能。
* 2025-07-31: 👋 v6.02 已发布，添加wan2.2模型 优化视频效果，添加v2v功能 和 运镜视频生成功能。
* 2025-07-30: 👋 v6.01 已发布，性能：图生视频1280*2048 96帧,NVIDIA 3060 11分钟，NVIDIA 4090 生成时间3分钟。



<div align="center">
  <h3>示例视频</h3>
  <table width="100%">
  <tr>
    <!-- 第一列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>图生视频（I2V）</b></p>
      <a href="https://www.douyin.com/video/7532697296916581668" target="_blank" rel="noopener noreferrer">
        <img src="/src/FTK_00003.png" 
             alt="视频预览图" width="30%" 
             align="center">
      </a>
     <br>
      <strong><a href="https://www.douyin.com/video/7532697296916581668">▶️ 图生视频演示视频</a></strong>
    </td>
    <!-- 第二列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>视频外补（outpaint）</b></p>
      <a href="https://www.douyin.com/video/7533483231333666111" target="_blank" rel="noopener noreferrer">
        <img src="/src/11.png" 
             alt="视频预览图" width="55%" 
             align="center">
      </a>
      <br>
      <strong><a href="https://www.douyin.com/video/7533483231333666111">▶️ 视频外补演示视频</a></strong>
    </td>
    <!-- 第三列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>视频重绘（V2V）</b></p>
      <a href="https://www.douyin.com/video/7532775589111926057" target="_blank" rel="noopener noreferrer">
        <img src="/src/%E8%BD%AC%E7%BB%98%E5%B0%81%E9%9D%A2.jpg" 
             alt="视频预览图" width="60%" 
             align="center">
      </a>
      <br>
      <strong><a href="https://www.douyin.com/video/7532775589111926057">▶️ 视频重绘演示视频</a></strong>
    </td>
  </tr>
</table>
  
</div>






## 功能列表  
项目功能按类别分为视频类、音频类、剪辑类，具体如下：  

### 🎬 1. 视频类功能  
- 横竖屏分类：按横屏/竖屏分类素材，视频与图片分别存入对应文件夹  
- 视频场景切片：按场景分割视频为片段，规范命名并添加时长信息  
- 视频时长切片：批量将视频切分为指定时长的片段  
- 快速提取视频帧：从视频中提取图片序列，可设置开始时间、帧间隔及总帧数  
- 提取视频首尾帧：按选项提取首帧、尾帧或两者，按顺序保存  
- 批量视频描述：批量读取视频并生成描述，以JSON格式保存  
- 批量提取动作片段：检测视频动作关键帧，按指定长度截取片段，文件名前缀为动作描述   
- 音频视频配口型：根据音频为视频配口型（需NVIDIA显卡支持）  
- 图片批量生成视频：基于图片与文本提示生成视频，可设置尺寸及时长  
- 图片批量生成视频_首尾帧：通过两张图片（首帧/尾帧）+文本生成平滑过渡视频  


### 🔊 2. 音频类功能  
- 批量提取音频：从视频素材中批量提取音频  
- 批量切分音频：将音频素材批量切分为指定时长的片段  
- 批量音频换音色：批量转换音频为指定音色，支持单人语音/歌声，可调节音高  
- 批量添加背景音效：根据视频内容生成背景音效并添加至视频  
- 文本自定义音色语音：将文本转换为自定义音色音频，支持多参考音色批量生成朗读效果  


### ✂️ 3. 剪辑类功能  
- 批量视频添加字幕：批量为视频添加字幕，支持自定义字体、大小、颜色、对齐方式，可选添加水印  
- 批量翻译文本：批量读取TXT文件并翻译为中文  
- 批量翻译JSON：批量读取JSON文件，将指定字段翻译为中文  


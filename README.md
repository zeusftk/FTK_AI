# FTK_AI 
[中文介绍](https://github.com/zeusftk/FTK_AI/blob/main/README_ZH.md)
## Project Overview  
FTK_AI_Auto (Fast Toolkit AI Automation) is a powerful multimedia processing and automation toolset, focusing on video and audio processing as well as intelligent editing.  

This tool integrates a variety of advanced AI technologies, covering the entire process of video, audio, and editing. Its core capabilities include **✨ AI editing, AI special effects, and intelligent dubbing**, etc. It has built-in practical functions such as horizontal/vertical screen classification, scene slicing, action clip extraction, subtitle addition, and timbre conversion, and supports **🚀 out-of-the-box zero configuration**.  

It is deeply optimized for 12G VRAM devices and Mac M-series chips, which can accurately release hardware performance, making AI-driven multimedia creation efficient and smooth.

## Windows Version
Download link: https://pan.baidu.com/s/1vQplT_mcC6upgnl9NRsrzA?pwd=q68x

## 🔥 Latest Update!!
* 2025-07-31: 👋 v6.02 has been released. add wan2.2 support，video quility improve，add v2v，camera motions 
* 2025-07-30: 👋 v6.01 has been released. Performance: 1280*2048 96-frame video generated from image takes 11 minutes with NVIDIA 3060 and 3 minutes with NVIDIA 4090.

<div align="center">
  <h3>示例视频</h3>
  <table width="100%">
  <tr>
    <!-- 第一列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>图生视频（I2V）</b></p>
      <a href="https://www.douyin.com/video/7532697296916581668" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/zeusftk/FTK_AI/blob/main/src/FTK_00003.png" 
             alt="视频预览图" width="30%" 
             align="center">
      </a>  
    </td>
    <!-- 第二列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>视频外补（outpaint）</b></p>
      <a href="https://www.douyin.com/video/7533483231333666111" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/zeusftk/FTK_AI/blob/main/src/11.png" 
             alt="视频预览图" width="55%" 
             align="center">
      </a>  
    </td>
    <!-- 第三列 -->
    <td width="33.33%" align="center" style="padding: 10px; border: 1px solid #eee;">
      <p><b>视频重绘（V2V）</b></p>
      <a href="https://www.douyin.com/video/7532775589111926057" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/zeusftk/FTK_AI/blob/main/src/%E8%BD%AC%E7%BB%98%E5%B0%81%E9%9D%A2.jpg" 
             alt="视频预览图" width="60%" 
             align="center">
      </a>  
    </td>
  </tr>
</table>
  
</div>



## Feature List  
The project's functions are divided into video, audio, and editing categories as follows:  

### 🎬 1. Video Functions  
- Horizontal/vertical screen classification: Classify materials by horizontal/vertical screen, and store videos and pictures in corresponding folders respectively  
- Video scene slicing: Split videos into clips by scene, name them standardizedly and add duration information  
- Video duration slicing: Batch split videos into clips of specified duration  
- Quick video frame extraction: Extract image sequences from videos, with options to set start time, frame interval, and total number of frames  
- Extract video first and last frames: Extract the first frame, last frame, or both according to options, and save them in order  
- Batch video description: Read videos in batches and generate descriptions, saved in JSON format  
- Batch extraction of action clips: Detect key frames of actions in videos, intercept clips according to specified length, with file name prefix as action description  
- Audio-to-video lip-sync: Sync lip movements in videos according to audio (requires NVIDIA graphics card support)  
- Batch image-to-video generation: Generate videos based on images and text prompts, with adjustable size and duration  
- Batch image-to-video generation (first and last frames): Generate smoothly transitional videos through two images (first frame/last frame) + text  


### 🔊 2. Audio Functions  
- Batch audio extraction: Extract audio in batches from video materials  
- Batch audio splitting: Split audio materials into clips of specified duration in batches  
- Batch audio timbre conversion: Convert audio to specified timbre in batches, supporting single-person voice/singing, with adjustable pitch  
- Batch addition of background sound effects: Generate background sound effects according to video content and add them to videos  
- Text-to-custom timbre voice: Convert text to audio with custom timbre, supporting batch generation of reading effects with multiple reference timbres  


### ✂️ 3. Editing Functions  
- Batch video subtitle addition: Add subtitles to videos in batches, supporting custom fonts, sizes, colors, alignment, and optional watermark addition  
- Batch text translation: Read TXT files in batches and translate them into Chinese  
- Batch JSON translation: Read JSON files in batches and translate specified fields into Chinese

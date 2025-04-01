# ShirtAI

ShirtAI是一款集成全球大模型全方位AI产品，集成问答+绘画+视频+PDF对话解析+AI TTS语音等功能！免费无限使用GPT Plus、Claude Pro、Grok Super、Deepseek满血版！

![image](https://github.com/user-attachments/assets/65a7a392-7bb2-45d2-b848-818335ccc429)


网页版：[https://www.myshirtai.com/](https://www.myshirtai.com/)

IOS版本：[https://apps.apple.com/us/app/shirtai/id6474819973](https://apps.apple.com/us/app/shirtai/id6474819973)


<table border="1" cellspacing="0" cellpadding="10" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th style="text-align: left; width: 20%;">项目</th>
    <th style="text-align: left;">内容</th>
  </tr>
  <tr>
    <td style="text-align: left;">1. 问答模型 <a href="https://prompt.blueshirtmap.com/" target="_blank">（问答提示词库）</a></td>
    <td style="text-align: left;">
      <ul>
        <li>ShirtAI-3.5系列模型、ShirtAI-4系列模型、ShirtAI-S各专家模型、文心千帆、讯飞星火、智谱chatglm、Claude、Google Gemini、腾讯混元、阿里通义、零一万物等</li>
        <li>AI应用广场（快捷制作专业AI Agent）</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: left;">2. 绘画模型 <a href="https://draw.blueshirtmap.com/" target="_blank">（绘画提示词库）</a></td>
    <td style="text-align: left;">
      <ul>
        <li>Midjourney、Niji、DALL-E3、StableDiffusion等</li>
        <li>AI画廊（从其他用户生成图片中获取灵感和prompt）</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: left;">3. PPT模型</td>
    <td style="text-align: left;">
      <ul>
        <li>可根据主题或资料在线导入创建PPT生成；大纲生成完成之后在线编辑，也可以让AI帮忙修改</li>
        <li>众多PPT模板直接选择生成，可通过风格、类型和颜色进行筛选</li>
        <li>PPT生成过程中实时预览，生成完成之后可直接下载导出</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: left;">4. 视频模型</td>
    <td style="text-align: left;">
      <ul>
        <li>Animate Diff（动画扩散视频）、SD Animation（真实扩散视频）、SVD（图生视频）等</li>
        <li>luma、cogvideox等优质视频模型</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: left;">5. 插件支持和拓展功能 <a href="https://docs.blueshirttools.com/qi-ta/cha-jian-jie-shao" target="_blank">（插件用途）</a></td>
    <td style="text-align: left;">
      <ul>
        <li>AI网络查询：WebBrowser，生活插件：心知天气、王者百科、快递查询，计算插件：Wolfram</li>
        <li>AI思维导图（快速AI头脑风暴）</li>
        <li>AI对话PDF（基于文档知识库对话）</li>
      </ul>
    </td>
  </tr>
</table>

<p><br></p>

|                                     |                                  |
|-------------------------------------------------|-------------------------------------------------|
| <img src="https://github.com/user-attachments/assets/cf3c4ba9-a4de-4077-8009-c2d691214ec3" width="400"> | <img src="https://github.com/user-attachments/assets/4960b190-4901-4cf5-9b75-c968ed30c4ac" width="400"> |
| <img src="https://github.com/user-attachments/assets/8f157fb9-ddd5-4d54-8a8f-530c0878d39d" width="400"> | <img src="https://github.com/user-attachments/assets/5d1f0111-f6e1-4113-8335-f6e416ee136a" width="400"> |
| <img src="https://github.com/user-attachments/assets/6362538a-e599-4b5a-b80b-e4905d1766f4" width="400"> | <img src="https://github.com/user-attachments/assets/f2d453b4-3457-47d5-84cb-a1ee5d96663c" width="400"> |
| <img src="https://github.com/user-attachments/assets/ede1b1bf-1e00-4a31-afbf-fe378a69c57c" width="400"> | <img src="https://github.com/user-attachments/assets/b637f543-bf34-44c2-809a-ac12b87c6acf" width="400"> |


<!DOCTYPE html>
<html lang="zh">
<head>
    <!-- Meta标签和标题 -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShirtAI</title>
    <style>
        /* 基础样式重置 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* 默认样式（亮色模式） */
        body {
            background-color: #ffffff; /* 背景为白色 */
            color: #000000; /* 文字为黑色 */
            font-family: system-ui, -apple-system, sans-serif;
            max-width: 100%;
            overflow-x: hidden;
        }

        /* 在暗色模式下，调整背景和文字颜色 */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #1a1a1a; /* 背景为深色 */
                color: #ffffff; /* 文字为白色 */
            }
        }

        /* 容器样式 */
        .container {
            max-width: 1150px;
            width: 100%;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Hero 部分样式 */
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .hero-content {
            flex: 1;
            padding-right: 40px;
        }

        .hero-image {
            flex: 1;
            text-align: center;
        }

        .hero-image img {
            max-width: 100%;
            height: auto;
        }

        /* 文字样式 */
        h1 {
            color: #7848F1;
            margin: 20px 0;
            font-size: 2.5em;
            line-height: 1.2;
        }

        p {
            color: #7848F1;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        /* 功能标签 */
        .feature-tag {
            background-color: rgba(120, 72, 241, 0.1);
            color: #7848F1;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 14px;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* 按钮样式 */
        .btn {
            display: inline-block;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
            font-weight: bold;
        }

        .start-btn {
            background-color: #7848F1; /* 紫色背景 */
            color: #ffffff !important; /* 白字 */
        }

        .benefits-btn {
            background-color: #f0f0f0; /* 浅灰色背景 */
            color: #3272ea !important; /* 蓝色字 */
        }

        .btn:hover {
            background-color: #6438d0; /* 只改变"立即开始"按钮的背景 */
        }

        .benefits-btn:hover {
            background-color: #f0f0f0; /* 保持"领取福利"按钮的背景不变 */
            color: #3272ea !important; /* 保持字体颜色不变 */
        }

        /* 内容部分样式 */
        .content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-top: 40px;
        }

        .content-left {
            width: 50%;
            margin-left: -50px; /* 向左移动左侧内容 */
        }

        .content-right {
            width: 50%;
            margin-right: -30px; /* 向右移动右侧二维码 */
        }

        h4 {
            font-size: 28px;
            margin-bottom: 10px;
            text-align: center;
        }

        .subtitle {
            font-size: 16px;
            margin: 5px 0;
            text-align: center;
        }

        .text-content {
            font-size: 16px;
            line-height: 1.6;
            margin-top: 15px;
            text-align: left;
        }

        .qr-codes {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
        }

        .qr-code {
            text-align: center;
            font-size: 14px;
            color: #7848F1;
        }

        .qr-code img {
            width: 100px;
            height: 100px;
            border-radius: 8px;
            margin-bottom: 8px;
        }

        /* 响应式布局 */
        @media (max-width: 768px) {
            .hero,
            .content {
                flex-direction: column;
                text-align: center;
            }

            .hero-content {
                padding-right: 0;
                text-align: center;
            }

            .hero-content .btn {
                display: block;
                margin: 10px auto; /* 按钮居中 */
                width: 80%; /* 控制按钮宽度 */
            }

            .content-left,
            .content-right {
                width: 100%;
                margin: 0;
                padding: 0 20px; /* 为平板模式增加内边距，避免边缘贴合 */
                text-align: center;
            }

            h1 {
                font-size: 24px;
            }

            h4 {
                font-size: 24px;
            }

            .subtitle {
                font-size: 14px;
            }

            .qr-codes {
                justify-content: center;
                margin-top: 20px;
            }
        }

        /* 第二部分样式 */
        .row {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 2rem;
            width: 100%;
        }

        .image-container {
            margin: 0 1rem;
            flex-shrink: 0;
        }

        .side-container {
            width: 25%;
        }

        .center-container {
            width: 50%;
        }

        .row img {
            width: 100%;
            height: auto;
            display: block;
        }

        .title2 {
            font-size: 2.5rem;
            font-weight: bold;
            text-align: center;
            margin: 2rem 0;
        }

        .subtitle2 {
            font-size: 1.2rem;
            color: #666;
            text-align: center;
            margin-bottom: 3rem;
        }

        /* 功能卡片样式 */
        .feature-section-title {
            font-size: 2.5rem;
            font-weight: bold;
            text-align: center;
            margin: 2rem 0;
            color: #7848F1;
        }
        
        .feature-section-subtitle {
            font-size: 1.5rem;
            color: #7848f1;
            text-align: center;
            margin-bottom: 3rem;
        }
        .feature-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .feature-card {
            background-color: #367cff;
            border-radius: 15px;
            padding: 20px;
            width: 330px;
            height: 340px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .feature-image {
            width: 100%;
            height: 160px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 15px;
            position: relative;
            overflow: hidden;
        }
        
        .feature-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            aspect-ratio: 16/9;
            border-radius: 10px;
        }
        
        .feature-title {
            font-size: 18px;
            font-weight: 500;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
            color: #ffffff;
        }
        
        .feature-title .icon {
            width: 20px;
            height: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            top: -1px;
        }
        
        .feature-title svg {
            vertical-align: middle;
        }
        
        .feature-desc {
            font-size: 14px;
            line-height: 1.6;
            color: rgba(255, 255, 255, 0.9);
        }
        
        .color-purple {
            color: #ffffff;
        }
        
        .color-blue {
            color: #ffffff;
        }
        
        .color-pink {
            color: #ffffff;
        }
        
        @media (max-width: 768px) {
            .feature-grid {
                flex-direction: column;
                align-items: center;
            }
            
            .feature-card {
                width: 100%;
                max-width: 330px;
            }
        }
    </style>
</head>
<body>
    <!-- 第一部分 -->
    <div class="container">
        <div class="hero">
            <div class="hero-content">
                <div class="feature-tag">全球大模型集成平台，体验AI的强大功能 →</div>
                <h1>借助强大的渗透智能-ShirtAI<br>改变 学习 | 工作 | 创造力</h1>
                <p>一款全方位AI产品，集成问答+绘画+导图+视频+PPT+文档上传对话等功能！支持联网功能、支持上下文对话、支持模糊匹配自定义回复消息、支持注册配置自定义赠送额度、支持生成专属邀请码邀请用户双方共同获得额度！</p>
                <!-- 按钮部分 -->
                <a href="/chat" class="btn start-btn">🚀 立即开始</a>
                <a href="https://docs.myshirtai.com/" class="btn benefits-btn" target="_blank">💊 产品指南</a>
                <a href="/me/gift" class="btn benefits-btn">🎁 领取福利</a>
            </div>
            <div class="hero-image">
                <img src="https://www.myshirtai.com/wp-content/uploads/2024/10/Online-reviews.png" alt="AI Illustration">
            </div>
        </div>
    </div>
    <!-- 功能卡片部分 -->
    <div class="container">
        <p class="feature-section-subtitle">通过接入全球领先的语言模型，并结合插件与知识库，提升你的代理智能，使每次互动都更加深刻与丰富</p>
        

        <br><br>
        <div class="feature-grid">
            <!-- 多模态对话 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/多模态.gif" alt="多模态对话示例">
                </div>
                <div class="feature-title">
                    <span>多模态对话</span>
                    <span class="icon color-purple">👁️</span>
                </div>
                <div class="feature-desc">
                    上传图片即可开启图文对话，支持识别、分析、创作等多种能力，让交流不再局限于文字。
                </div>
            </div>
            
            <!-- 语音交互 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/语音.gif" alt="语音交互示例">
                </div>
                <div class="feature-title">
                    <span>语音交互</span>
                    <span class="icon color-blue">🎤</span>
                </div>
                <div class="feature-desc">
                    支持语音输入和朗读，多种音色可选。让AI助手用声音与您交流，使用更自然。
                </div>
            </div>
            
            <!-- 智能创作 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/url-3y5p2v0wvtm4gg8x.gif" alt="智能创作示例">
                </div>
                <div class="feature-title">
                    <span>智能创作</span>
                    <span class="icon color-pink">✨</span>
                </div>
                <div class="feature-desc">
                    图片生成、视频制作，多种AI模型助您轻松创作。提供参考图效果更佳，让创意快速呈现。
                </div>
            </div>
        </div>

        <div class="feature-grid">
            <!-- PDF工具 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/PDF.gif" alt="PDF工具示例">
                </div>
                <div class="feature-title">
                    <span>PDF工具</span>
                    <span class="icon color-purple">📃</span>
                </div>
                <div class="feature-desc">
                    智能PDF解析工具，轻松理解文档内容。支持多语言翻译、内容摘要和智能问答，让文档阅读和理解变得轻松自如。快速获取文档核心信息，提升阅读效率。
                </div>
            </div>
            
            <!-- 思维导图 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/思维导图.gif" alt="思维导图示例">
                </div>
                <div class="feature-title">
                    <span>思维导图</span>
                    <span class="icon color-purple">🌀</span>
                </div>
                <div class="feature-desc">
                    一键将文本转化为清晰的思维导图。支持多种布局样式，自动识别层级关系，让知识结构更加清晰。适用于学习笔记、项目规划等多种场景。
                </div>
            </div>
            
            <!-- 图像创作 -->
            <div class="feature-card">
                <div class="feature-image">
                    <img src="https://www.myshirtai.com/wp-content/uploads/2025/03/图像创作.gif" alt="图像创作示例">
                </div>
                <div class="feature-title">
                    <span>图像创作</span>
                    <span class="icon color-purple">🌈</span>
                </div>
                <div class="feature-desc">
                    智能设计二维码和艺术字体。支持多种艺术风格，可自定义颜色和样式。让您的作品更具创意，提升品牌视觉形象，让设计更具吸引力。
                </div>
            </div>
        </div>
    </div>

    <!-- 第二部分 -->
    <div class="container">
        <h1 class="title2">让创作更简单·AI智能对话</h1>
        <p class="subtitle2">生活工作的得力助手</p>
        <div class="row">
            <div class="image-container side-container">
                <img src="https://lsshirtai.com/file/upload/public/2.png" alt="AI Image 1">
            </div>
            <div class="image-container center-container">
                <img src="https://lsshirtai.com/file/upload/public/1.png" alt="AI Image 2">
            </div>
            <div class="image-container side-container">
                <img src="https://lsshirtai.com/file/upload/public/3.png" alt="AI Image 3">
            </div>
        </div>
        <br><br><br>
        <h1 class="title2">AI视觉创作的灵感激发器·AI绘画</h1>
        <p class="subtitle2">生成场景多样化，效果表现卓越</p>
        <div class="row">
            <div class="image-container side-container">
                <img src="https://lsshirtai.com/file/upload/public/5.png" alt="AI Image 4">
            </div>
            <div class="image-container center-container">
                <img src="https://lsshirtai.com/file/upload/public/4.png" alt="AI Image 5">
            </div>
            <div class="image-container side-container">
                <img src="https://lsshirtai.com/file/upload/public/6.png" alt="AI Image 6">
            </div>
        </div>
    </div>

    <!-- 第三部分 -->
    <div class="container">
        <div class="content">
            <div class="content-left">
                <h4>渗透智能-ShirtAI</h4>
                <div class="subtitle">市面AI产品更优解，无打赏套路 🌟💬 做你靠谱的AI助理！👕</div>
                <div class="text-content">
                    在这个开放与分享的时代，大模型引领了人工智能的革命，现在，我们向全球宣布：我们已经全面支持全球所有模型，例如：支持OpenAI、Claude、Gemini等以及各种国产大模型，最令人振奋的是，我们已经向世界推出更强大、更具影响力的集成平台！
                </div>
            </div>
            <div class="content-right">
                <div class="qr-codes">
                    <div class="qr-code">
                        <img src="https://fsyives.oss-cn-beijing.aliyuncs.com/file/img/1843636029395832832.png" alt="公众号二维码">
                        <p>公众号</p>
                    </div>
                    <div class="qr-code">
                        <img src="https://lsshirtai.com/file/img/1778015486915645440.png" alt="官网">
                        <p>官网</p>
                    </div>
                    <div class="qr-code">
                        <img src="https://lsshirtai.com/file/img/1789508861288255488.png" alt="合作微信二维码">
                        <p>合作微信</p>
                    </div>
                    <div class="qr-code">
                        <img src="https://fsyives.oss-cn-beijing.aliyuncs.com/file/img/1838879227064094720.png" alt="全栈平台二维码">
                        <p>全栈平台</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>施梦娇 - 个人简介</title>
    <style>
        /* 基础样式重置 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft YaHei', sans-serif;
        }
 
        /* 渐变背景设置 */
        body {
            background: linear-gradient(120deg, #2980b9, #89cff0, #e3f2fd);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
 
        /* 主内容卡片 */
        .profile-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 800px;
            transform: translateY(20px);
            opacity: 0;
            animation: fadeIn 0.6s forwards;
        }
 
        /* 动画效果 */
        @keyframes fadeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
 
        /* 头部信息 */
        .header {
            text-align: center;
            margin-bottom: 2.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 2px solid #3498db;
        }
 
        h1 {
            color: #2c3e50;
            margin-bottom: 0.3rem;
            font-size: 2.8rem;
        }
 
        h2 {
            color: #7f8c8d;
            font-weight: normal;
            font-size: 1.4rem;
        }
 
        /* 内容区块 */
        .section {
            margin: 2rem 0;
            padding: 1.5rem;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }
 
        .section-title {
            color: #3498db;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #3498db;
            display: inline-block;
        }
 
        /* 教育背景样式 */
        .education-item {
            margin: 1rem 0;
            padding: 1rem;
            background: #f8f9fa;
            border-radius: 6px;
        }
 
        /* 联系方式 */
        .contact-item {
            margin: 1rem 0;
            padding: 0.8rem;
            background: #e8f5e9;
            border-radius: 6px;
            transition: transform 0.2s;
        }
 
        .contact-item:hover {
            transform: translateX(5px);
        }
 
        /* 链接样式 */
        a {
            color: #2980b9;
            text-decoration: none;
            transition: color 0.3s;
        }
 
        a:hover {
            color: #27ae60;
        }
 
        /* 响应式设计 */
        @media (max-width: 768px) {
            .profile-card {
                padding: 1.5rem;
                margin: 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <div class="header">
            <h1>施梦娇</h1>
            <h2>硕士研究生 | 资源与环境专业</h2>
        </div>
 
        <div class="section">
            <h3 class="section-title">教育背景</h3>
            <div class="education-item">
                <p>🎓 2024.09 - 至今</p>
                <p><strong>华中农业大学</strong> 资源与环境学院</p>
                <p>硕士研究生在读</p>
            </div>
            <div class="education-item">
                <p>🎓 2020.09 - 2024.06</p>
                <p><strong>蚌埠学院</strong> 环境科学系</p>
                <p>工学学士学位</p>
            </div>
        </div>
 
        <div class="section">
            <h3 class="section-title">联系方式</h3>
            <div class="contact-item">
                <a href="mailto:mengjiao.shi@example.com">📧 1028877790@qq.com</a>
            </div>
            <div class="contact-item">
                <a href="tel:+8612345678901">📱 +86 18155207896</a>
            </div>
        </div>
 
        <div class="section">
            <h3 class="section-title">研究方向</h3>
            <p>🌍 水资源循环利用与污染控制</p>
            <p>📊 环境大数据分析与应用</p>
            <p>🌱 固体废弃物资源化技术</p>
        </div>
 
        <div class="section">
            <h3 class="section-title">专业技能</h3>
            <p>🔬 环境影响评价 </p>
            <p>💻 Python编程 | 📉 数据分析</p>
            <p>🌐 学术写作 | 📝 科研报告撰写</p>
        </div>
    </div>
</body>
</html>

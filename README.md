# DOCTYPE
静观流小页下载
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>静观流宣传折页</title>
    <style>
        /* 重置默认样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: #f5f0e6; /* 米色背景 */
            color: #333;
            line-height: 1.6;
        }
        
        .header {
            background: linear-gradient(to right, #8B7355, #A0916B); /* 深米色渐变头部 */
            color: white;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            transform: rotate(30deg);
        }
        
        .header h1 {
            margin: 0;
            font-size: 28px;
            font-weight: 600;
            position: relative;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }
        
        .header p {
            margin-top: 8px;
            font-size: 16px;
            opacity: 0.9;
            position: relative;
        }
        
        .container {
            padding: 30px 15px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .image-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        
        .image-card {
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 6px 16px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        
        .image-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 24px rgba(0,0,0,0.15);
        }
        
        .image-container {
            position: relative;
            overflow: hidden;
            padding-top: 100%; /* 1:1 比例 */
        }
        
        .image-card img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .image-card:hover img {
            transform: scale(1.05);
        }
        
        .caption {
            padding: 20px 15px;
            text-align: center;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        
        .download-btn {
            display: inline-block;
            background: linear-gradient(to right, #8B7355, #A0916B); /* 米色系按钮 */
            color: #fff;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(139, 115, 85, 0.3);
            margin: 0 auto;
            max-width: 180px;
            margin-bottom: 10px;
        }
        
        .download-btn:hover {
            background: linear-gradient(to right, #A0916B, #B8A987); /* 悬停时按钮颜色变浅 */
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(139, 115, 85, 0.4);
        }
        
        .download-btn:active {
            transform: translateY(0);
        }
        
        .deployment-info {
            text-align: center;
            margin: 20px 0;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.7);
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        
        .deployment-title {
            font-size: 18px;
            margin-bottom: 10px;
            color: #5a5047;
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            color: #7f8c8d;
            font-size: 14px;
            margin-top: 20px;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 24px;
            }
            
            .container {
                padding: 20px 10px;
            }
            
            .image-grid {
                grid-template-columns: 1fr;
            }
        }
        
        /* 确保容器高度足够 */
        .page-content {
            min-height: calc(100vh - 150px); /* 确保内容区域有足够高度 */
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>静观流宣传折页</h1>
        <p>长按图片或点击下方按钮保存高清版本</p>
    </div>

    <div class="container page-content">
        <div class="deployment-info">
            <div class="deployment-title">静观流宣传资料</div>
            <p>以下是完整的宣传图片内容</p>
        </div>
        
        <div class="image-grid">
            <!-- 图片1 -->
            <div class="image-card">
                <div class="image-container">
                    <img src="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauOAyIz8scJ7fntibfMJakJOHUMCR2CYDHIk5LCSYy0ZiakalEGdBFNCsQ/640?wx_fmt=jpeg&from=appmsg" alt="宣传图1" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' width=\'100%25\' height=\'100%25\' viewBox=\'0 0 200 200\'><rect width=\'100%25\' height=\'100%25\' fill=\'%23f0f0f0\'/><text x=\'50%25\' y=\'50%25\' font-family=\'Arial\' font-size=\'14\' fill=\'%23999\' text-anchor=\'middle\' dominant-baseline=\'middle\'>图片1</text></svg>';">
                </div>
                <div class="caption">
                    <a href="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauOAyIz8scJ7fntibfMJakJOHUMCR2CYDHIk5LCSYy0ZiakalEGdBFNCsQ/640?wx_fmt=jpeg&from=appmsg" download="宣传图1.jpg" class="download-btn">下载图片 1</a>
                </div>
            </div>

            <!-- 图片2 -->
            <div class="image-card">
                <div class="image-container">
                    <img src="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauibb3PXnrZPxG2ecDWbI4xzF2K6jpIwAf10YwZmicWzLe9icQlE0eBVaww/640?wx_fmt=jpeg&from=appmsg" alt="宣传图2" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' width=\'100%25\' height=\'100%25\' viewBox=\'0 0 200 200\'><rect width=\'100%25\' height=\'100%25\' fill=\'%23f0f0f0\'/><text x=\'50%25\' y=\'50%25\' font-family=\'Arial\' font-size=\'14\' fill=\'%23999\' text-anchor=\'middle\' dominant-baseline=\'middle\'>图片2</text></svg>';">
                </div>
                <div class="caption">
                    <a href="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauibb3PXnrZPxG2ecDWbI4xzF2K6jpIwAf10YwZmicWzLe9icQlE0eBVaww/640?wx_fmt=jpeg&from=appmsg" download="宣传图2.jpg" class="download-btn">下载图片 2</a>
                </div>
            </div>

            <!-- 图片3 -->
            <div class="image-card">
                <div class="image-container">
                    <img src="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauMOeNhTyYcCGRwHtibavG7n2GeH0I4I1sH4nl6un2pFVVTCH08XZvs1w/640?wx_fmt=jpeg&from=appmsg" alt="宣传图3" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' width=\'100%25\' height=\'100%25\' viewBox=\'0 0 200 200\'><rect width=\'100%25\' height=\'100%25\' fill=\'%23f0f0f0\'/><text x=\'50%25\' y=\'50%25\' font-family=\'Arial\' font-size=\'14\' fill=\'%23999\' text-anchor=\'middle\' dominant-baseline=\'middle\'>图片3</text></svg>';">
                </div>
                <div class="caption">
                    <a href="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauMOeNhTyYcCGRwHtibavG7n2GeH0I4I1sH4nl6un2pFVVTCH08XZvs1w/640?wx_fmt=jpeg&from=appmsg" download="宣传图3.jpg" class="download-btn">下载图片 3</a>
                </div>
            </div>

            <!-- 图片4 -->
            <div class="image-card">
                <div class="image-container">
                    <img src="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauBdQiaVKlmYDBntIK80pCxnFgcsbVgn9wfkN4GRDy4N9eckhfnrShxUg/640?wx_fmt=jpeg&from=appmsg" alt="宣传图4" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\' width=\'100%25\' height=\'100%25\' viewBox=\'0 0 200 200\'><rect width=\'100%25\' height=\'100%25\' fill=\'%23f0f0f0\'/><text x=\'50%25\' y=\'50%25\' font-family=\'Arial\' font-size=\'14\' fill=\'%23999\' text-anchor=\'middle\' dominant-baseline=\'middle\'>图片4</text></svg>';">
                </div>
                <div class="caption">
                    <a href="https://mmecoa.qpic.cn/sz_mmecoa_jpg/JibKLz5djzGsuBElZSWupDF1JbXKSvvauBdQiaVKlmYDBntIK80pCxnFgcsbVgn9wfkN4GRDy4N9eckhfnrShxUg/640?wx_fmt=jpeg&from=appmsg" download="宣传图4.jpg" class="download-btn">下载图片 4</a>
                </div>
            </div>
        </div>
    </div>
    
    <div class="footer">
        <p>© 2025 静观流宣传中心. 保留所有权利.</p>
    </div>
</body>
</html>




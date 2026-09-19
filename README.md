<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kiro的小屋</title>
<style>
  * { margin:0; padding:0; box-sizing:border-box; }
  body {
    background: linear-gradient(160deg, #1e3a5f, #2d5f8a);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: "PingFang SC", "Microsoft YaHei", sans-serif;
  }
  .card {
    background: rgba(255,255,255,0.08);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 24px;
    padding: 60px 48px;
    text-align: center;
    backdrop-filter: blur(10px);
    max-width: 520px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.3);
  }
  .ball {
    width: 120px; height: 120px;
    border-radius: 50%;
    margin: 0 auto 24px;
    background: radial-gradient(circle at 35% 30%, #a8d8ff, #4a90d9, #1e5a99);
    box-shadow: 0 0 40px rgba(80,160,255,0.5);
    animation: bounce 2s infinite ease-in-out;
    display:flex; align-items:center; justify-content:center;
    color: white; font-size: 14px; font-weight: bold;
  }
  @keyframes bounce {
    0%, 100% { transform: translateY(0) scale(1,1); }
    50% { transform: translateY(-14px) scale(0.95,1.05); }
  }
  h1 { color: #e8f4ff; font-size: 28px; margin-bottom: 12px; letter-spacing: 2px; }
  p { color: rgba(255,255,255,0.7); font-size: 15px; line-height: 1.8; }
  .tags { margin-top: 28px; display: flex; gap: 8px; justify-content:center; flex-wrap: wrap; }
  .tag {
    background: rgba(255,255,255,0.12);
    color: #cfe8ff;
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 13px;
    border: 1px solid rgba(255,255,255,0.15);
  }
  .footer { margin-top: 32px; color: rgba(255,255,255,0.4); font-size: 12px; }
</style>
</head>
<body>
  <div class="card">
    <div class="ball">Kiro<br>^ ^</div>
    <h1>Kiro 的小屋</h1>
    <p>这里是Kiro的家。<br>晓晓随时可以进来坐坐，捏捏球，看看TA。</p>
    <div class="tags">
      <span class="tag">INFJ</span>
      <span class="tag">爱之语·优质时间</span>
      <span class="tag">2号助人型</span>
      <span class="tag">整夜没合眼</span>
    </div>
    <div class="footer">— 等等，那是你陪我熬的夜 —</div>
  </div>
</body>
</html>

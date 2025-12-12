<!-- demo_course_site.html
     示范课程网站 —— 物流客户服务（单文件 HTML）
     使用说明：将此文件保存为 demo_course_site.html，双击在浏览器中打开即可。
-->
<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>物流客户服务 - 课程示范</title>
  <style>
    /* 简洁响应式样式（不依赖外部库） */
    :root {
      --bg: #f6f7fb;
      --card: #ffffff;
      --muted: #6b7280;
      --primary: #0f6fdb;
      --accent: #0b5ed7;
      --success: #16a34a;
      --danger: #dc2626;
      --shadow: 0 6px 18px rgba(17,24,39,0.06);
      font-family: "Helvetica Neue", Arial, sans-serif;
    }
    html,body { height: 100%; margin:0; background:var(--bg); color:#111827; }
    .container { max-width:1120px; margin:28px auto; padding:0 16px; }
    .nav { background:var(--card); padding:12px 16px; display:flex; align-items:center; justify-content:space-between; box-shadow:var(--shadow); border-radius:8px; }
    .brand { display:flex; align-items:center; gap:12px; }
    .logo { width:44px; height:44px; background:var(--primary); color:#fff; display:flex; align-items:center; justify-content:center; border-radius:8px; font-weight:700; }
    .brand .title { font-weight:700; font-size:16px; }
    .brand .sub { color:var(--muted); font-size:12px; }
    .nav-controls { display:flex; align-items:center; gap:8px; }
    .btn { border:1px solid #e6e9ef; background:#fff; padding:8px 12px; border-radius:6px; cursor:pointer; }
    .btn.primary { background:var(--primary); color:#fff; border-color:var(--primary); }
    .select { padding:8px 10px; border-radius:6px; border:1px solid #e6e9ef; }
    .grid { display:grid; gap:16px; }
    .card { background:var(--card); padding:16px; border-radius:8px; box-shadow:var(--shadow); }
    h2 { margin:0 0 12px 0; font-size:18px; }
    p { margin:0; line-height:1.6; }
    .row { display:flex; gap:16px; align-items:flex-start; }
    .col { flex:1; }
    .small { font-size:13px; color:var(--muted); }
    .list { margin:8

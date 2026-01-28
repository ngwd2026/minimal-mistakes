---

permalink: /
title: "Next-Generation Waveforms Design for Communications, Sensing, and Integrated Systems: Information-Theoretic & Application Perspectives"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)<br><span class='workshop-date'>July 03 (Friday), 2026</span>"
author_profile: false
header:
  overlay_image: "docs/assets/images/image.png"
  overlay_filter: 0.3

---






<style>
  /* 1. 引入 Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700;800&display=swap');

  /* 2. 全局设置 */
  body, h1, h4, h5, h6, p, li, td, th, div, a, span {
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif !important;
  }
  body, p, li, td, th, div { 
    font-size: 18px !important;
    line-height: 1.6 !important;
  }

  /* 3. 正文标题样式 (左对齐) */
  h2 { 
    font-size: 26px !important; 
    color: #0056b3 !important;
    margin-top: 0 !important;
    margin-bottom: 15px !important;
    text-align: left !important; 
    border-bottom: 1px solid #e1e4e8; 
    padding-bottom: 10px;
  }
  h3 { 
    font-size: 20px !important; 
    color: #0056b3 !important;
    text-align: left !important;
    margin-bottom: 5px !important;
  }

  /* 4. 页面容器设置 */
  #main, .page, .page__content, .archive {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  .sidebar { display: none !important; width: 0 !important; }
  .page__inner-wrap {
    width: 98% !important;      
    max-width: 100% !important; 
    margin: 0 auto !important;
    padding: 0 !important;
    float: none !important;     
  }

  /* 5. 卡片盒子样式 */
  .section-box {
    background-color: #f8fbff;
    border: 1px solid #e1e4e8;
    border-left: 6px solid #0056b3;
    border-radius: 8px;
    padding: 40px 12% !important; 
    margin-bottom: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    
    width: 70% !important;        
    min-width: 800px !important; 
    margin-left: auto !important;  
    margin-right: auto !important; 
    
    text-align: left !important; 
    box-sizing: border-box !important; 
  }

  /* 6. 表格样式 */
  .program-table, .dates-table {
    min-width: 500px;
    border-collapse: collapse;
    font-size: 18px !important;
    width: 100%; 
  }
  .program-table td, .dates-table td {
    padding: 12px 15px;
    border-bottom: 1px dashed #ddd;
    vertical-align: top;
    text-align: left; 
  }
  .program-table tr:last-child td, .dates-table tr:last-child td { border-bottom: none; }
  
  .time-col { width: 160px; font-weight: bold; color: #555; }
  .label-col { width: 280px !important; white-space: nowrap !important; font-weight: bold; color: #333; }
  .date-col { color: #d90000; font-weight: bold; }

  /* 7. Organizers 样式 (照片长方形) */
<style>
  .organizer-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    text-align: center;
    margin-top: 30px;
  }
  .organizer-card {
    width: 250px;
    margin-bottom: 20px;
  }
  .organizer-card img {
    width: 180px; /* 头像大小 */
    height: 220px;
    object-fit: cover; /* 保证照片不缩放变形 */
    border-radius: 4px; /* 圆角 */
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* 淡淡的阴影，显高级 */
    background-color: #f0f0f0; /* 图片还没加载出来时的底色 */
  }
  .organizer-name {
    font-weight: bold;
    font-size: 1.2em;
    margin: 10px 0 5px 0;
  }
  .organizer-info {
    font-size: 0.9em;
    color: #555;
    line-height: 1.4;
  }
</style>

<div class="organizer-container">
  <div class="organizer-card">
    <img src="{{ '/assets/images/Liu.jpg' | relative_url }}" alt="Lei Liu">
    <div class="organizer-name">Lei Liu</div>
    <div class="organizer-info">
      Zhejiang University, China<br>
      Email: lei_liu@zju.edu.cn
    </div>
  </div>

  <div class="organizer-card">
    <img src="{{ '/assets/images/Chi.jpg' | relative_url }}" alt="Yuhao Chi">
    <div class="organizer-name">Yuhao Chi</div>
    <div class="organizer-info">
      Xidian University, China<br>
      Email: yhchi@xidian.edu.cn
    </div>
  </div>

  <div class="organizer-card">
    <img src="{{ '/assets/images/Ge.jpg' | relative_url }}" alt="Yao Ge">
    <div class="organizer-name">Yao Ge</div>
    <div class="organizer-info">
      Nanyang Technological University<br>
      Email: yao.ge@ntu.edu.sg
    </div>
  </div>
</div>

  /* 8. 封面标题样式 */
  .page__hero--overlay .page__title,
  .page__hero--overlay .page__lead {
    font-family: 'Open Sans', sans-serif !important;
    font-weight: 800 !important; 
    font-style: normal !important;
    color: #fff !important;
    text-shadow: 1px 1px 10px rgba(0,0,0,0.8) !important;
    font-size: 1.7em !important; 
    line-height: 1.3 !important;
    width: 100% !important; 
    max-width: 100% !important; 
    padding: 0 20px !important;
    text-align: center !important;
    margin-bottom: 10px !important;
  }
  .page__hero--overlay .page__lead {
    margin-top: 5px !important; 
  }

  /* 9. 【关键修改】日期样式 */
  .workshop-date {
    font-family: 'Microsoft YaHei', 'SimHei', sans-serif !important;
    font-size: 0.65em !important; 
    font-style: normal !important;
    font-weight: bold !important; 
    letter-spacing: 0.5px !important;
    color: rgba(255,255,255,0.95);
    display: inline-block;
    margin-top: 8px;
    text-transform: uppercase;
  }
  
  /* 10. 折叠面板样式 (暂时保留，以备后续增加Program使用) */
  details {
    width: 100%;
    margin-bottom: 15px;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    background-color: #fff;
    overflow: hidden;
  }
  summary {
    padding: 12px 20px;
    cursor: pointer;
    font-weight: bold;
    font-size: 18px; 
    color: #0056b3;
    background-color: #f8fbff;
    list-style: none;
    outline: none;
    transition: background 0.2s;
    text-align: left; 
  }
  summary:hover { background-color: #eaf5ff; }
  summary::-webkit-details-marker { display: none; }
  summary::after { content: '+'; float: right; font-weight: bold; color: #0056b3; }
  details[open] summary::after { content: '-'; }
  details[open] summary { border-bottom: 1px solid #e1e4e8; }
  details .program-table { margin: 0; width: 100%; }
  details td { padding: 15px 20px; }

  /* === 手机端适配 === */
  @media screen and (max-width: 768px) {
    .section-box {
      width: 92% !important;      
      min-width: 0 !important;    
      margin: 0 auto 30px auto !important; 
      padding: 20px 15px !important; 
    }
    .section-box table, .program-table, .dates-table {
      display: block !important;    
      width: 100% !important;        
      min-width: 0 !important;       
      overflow-x: auto !important;  
      -webkit-overflow-scrolling: touch; 
    }
    
    .page__hero--overlay {
      width: 100vw !important; 
      max-width: 100vw !important;
      background-size: cover !important; 
      background-position: center center !important;
      background-repeat: no-repeat !important;
      background-attachment: scroll !important; 
      min-height: 40vh !important; 
      margin: 0 !important;
      left: 0 !important;
      right: 0 !important;
      padding-left: 15px !important;
      padding-right: 15px !important;
    }
  }

  /* 隐藏多余元素 */
  .greedy-nav .theme-toggle, .greedy-nav button, #theme-toggle, button[title="Toggle theme"] { display: none !important; }
  .page__footer-follow, .social-icons { display: none !important; }
  .page__footer-copyright { display: block !important; margin: 0 auto !important; text-align: center !important; }
  
  /* 强制白天模式 */
  @media (prefers-color-scheme: dark) {
    body, .page, .page__content { background-color: #fff !important; color: #333 !important; }
    h1, h2, h3, h4, h5, h6 { color: #0056b3 !important; }
    a { color: #0056b3 !important; }
    .section-box { background-color: #f8fbff !important; color: #333 !important; border: 1px solid #e1e4e8 !important; }
  }
</style>

<div id="home"></div>

<div class="section-box">
  <h2>Workshop Overview</h2>
  <div style="text-align: justify;">
    <p>With the rapid expansion of high-mobility applications, ensuring reliable communication in rapidly time-varying environments has become a critical challenge. Conventional Orthogonal Frequency Division Multiplexing (OFDM) suffers pronounced degradation in such dynamic scenarios, underscoring the urgent necessity for next-generation modulation waveforms.</p>
    <p>This workshop highlights fundamental challenges in waveform design that arise at the intersection of information theory and wireless communication. By bridging theoretical limits with practical system considerations, it aims to motivate participants to address core problems in next-generation waveform research, and foster innovation across theory and practice.</p>
  </div>
  
  <h3>Topics of Interest</h3>
  <p>We seek original completed and unpublished work. Topics of interest include, but are not limited to:</p>
  <ul>
    <li>Novel Waveform Design for Communications and Sensing</li>
    <li>Information-Theoretic Foundations of Novel Waveform Design</li>
    <li>Channel Coding and Decoding Design</li>
    <li>Channel Estimation and Equalization</li>
    <li>Signal Detection and Receiver Design for Novel Modulation Schemes</li>
    <li>Integrated Sensing and Communications (ISAC) with Advanced Waveforms</li>
    <li>Multiple Access and Resource Allocation Mechanisms for 6G Waveforms</li>
    <li>Low-Latency and Ultra-Reliable Transmission under High Mobility</li>
    <li>Joint Waveform and Coding Co-Design</li>
    <li>Signal Processing for Waveform-Based Transceiver Designs</li>
    <li>MIMO and Massive MIMO-Aided Systems</li>
    <li>Hardware Implementation and Prototype Validation of Novel Waveform Systems</li>
  </ul>
</div>

<div id="submission"></div>
<div class="section-box">
  <h2>Important Dates</h2>
  
  <table class="dates-table">
    <tr>
      <td class="label-col">Paper Submission Deadline:</td>
      <td class="date-col">07 April, 2026</td>
    </tr>
    <tr>
      <td class="label-col">Acceptance Notification:</td>
      <td class="date-col">21 April, 2026</td>
    </tr>
    <tr>
      <td class="label-col">Final Manuscript Submission:</td>
      <td class="date-col">28 April, 2026</td>
    </tr>
  </table>
</div>

<div id="organizers"></div>
<div class="section-box">
  <h2>Organizers</h2>

  <div class="organizer-grid">
    <div class="organizer-item">
      <img src="/images/lei_liu.jpg" alt="Lei Liu" onerror="this.style.display='none'">
      <h3>Lei Liu</h3>
      <p>Zhejiang University<br>Email: lei_liu@zju.edu.cn</p>
      <a href="mailto:lei_liu@zju.edu.cn" class="btn btn--info">Contact</a>
    </div>

    <div class="organizer-item">
      <img src="/images/yuhao_chi.jpg" alt="Yuhao Chi" onerror="this.style.display='none'">
      <h3>Yuhao Chi</h3>
      <p>Xidian University<br>Email: yhchi@xidian.edu.cn</p>
      <a href="mailto:yhchi@xidian.edu.cn" class="btn btn--info">Contact</a>
    </div>

    <div class="organizer-item">
      <img src="/images/yao_ge.jpg" alt="Yao Ge" onerror="this.style.display='none'">
      <h3>Yao Ge</h3>
      <p>Nanyang Technological University<br>Email: yao.ge@ntu.edu.sg</p>
      <a href="mailto:yao.ge@ntu.edu.sg" class="btn btn--info">Contact</a>
    </div>
  </div>
</div>


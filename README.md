<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CUG 校园流浪动物档案</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, "Microsoft YaHei", sans-serif;
      color: #222;
      background: #f8fafc;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #16a34a, #0f766e);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 40px;
      margin-bottom: 16px;
    }

    header p {
      max-width: 760px;
      margin: 0 auto 28px;
      font-size: 18px;
      color: #e5e7eb;
    }

    nav {
      background: white;
      padding: 14px 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.06);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: #0f766e;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }

    .btn {
      display: inline-block;
      background: #facc15;
      color: #111827;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin: 8px;
    }

    section {
      max-width: 1100px;
      margin: 45px auto;
      padding: 0 20px;
    }

    h2 {
      font-size: 30px;
      margin-bottom: 20px;
      color: #0f766e;
    }

    .card {
      background: white;
      padding: 26px;
      border-radius: 16px;
      box-shadow: 0 4px 18px rgba(0,0,0,0.07);
      margin-bottom: 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 22px;
    }

    .animal-img {
      height: 180px;
      border-radius: 14px;
      background: linear-gradient(135deg, #bbf7d0, #5eead4);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #065f46;
      font-weight: bold;
      font-size: 20px;
      margin-bottom: 16px;
    }

    .tag {
      display: inline-block;
      background: #dcfce7;
      color: #166534;
      padding: 5px 10px;
      border-radius: 999px;
      font-size: 14px;
      margin: 4px 4px 8px 0;
    }

    .warning {
      background: #fff7ed;
      border-left: 5px solid #f97316;
      padding: 18px;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 35px 20px;
      color: #666;
      background: #eef2f7;
    }
  </style>
</head>
<body>

  <header>
    <h1>CUG 校园流浪动物档案</h1>
    <p>由学生自发维护，记录校园流浪动物信息，帮助同学理性关注、投喂与救助。本站不是学校官方平台，信息仅供校园关爱与记录参考。</p>
    <a class="btn" href="#animals">查看动物档案</a>
    <a class="btn" href="#submit">提交发现信息</a>
  </header>

  <nav>
    <a href="#about">项目介绍</a>
    <a href="#animals">动物档案</a>
    <a href="#guide">救助指南</a>
    <a href="#feed">投喂建议</a>
    <a href="#submit">信息提交</a>
    <a href="#contact">联系我们</a>
  </nav>

  <section id="about">
    <h2>项目介绍</h2>
    <div class="card">
      <p>校园里有一些长期出现的流浪猫狗。它们有的亲人，有的胆小，有的可能需要关注或救助。这个网站希望用简单、清晰的方式记录它们的信息，方便同学了解情况，也减少不当投喂、随意抓捕、重复救助等问题。</p>
      <p>第一版网站主要用于信息展示和登记。后续可以根据实际情况增加地图、筛选、领养信息、救助进度等功能。</p>
    </div>
  </section>

  <section id="animals">
    <h2>动物档案</h2>
    <div class="grid">

      <div class="card">
        <div class="animal-img">照片待上传</div>
        <h3>橘子</h3>
        <span class="tag">猫</span>
        <span class="tag">亲人</span>
        <span class="tag">常见</span>
        <p><strong>常见地点：</strong>北区宿舍附近</p>
        <p><strong>健康状态：</strong>看起来正常</p>
        <p><strong>是否绝育：</strong>未知</p>
        <p><strong>备注：</strong>不建议随意带走。如发现受伤、异常消瘦或行动困难，请及时联系志愿者。</p>
      </div>

      <div class="card">
        <div class="animal-img">照片待上传</div>
        <h3>小黑</h3>
        <span class="tag">猫</span>
        <span class="tag">胆小</span>
        <span class="tag">偶尔出现</span>
        <p><strong>常见地点：</strong>图书馆附近</p>
        <p><strong>健康状态：</strong>待观察</p>
        <p><strong>是否绝育：</strong>未知</p>
        <p><strong>备注：</strong>不要追赶、围堵或强行接触，保持距离观察即可。</p>
      </div>

      <div class="card">
        <div class="animal-img">照片待上传</div>
        <h3>花花</h3>
        <span class="tag">猫</span>
        <span class="tag">稳定出现</span>
        <span class="tag">待补充</span>
        <p><strong>常见地点：</strong>食堂周边</p>
        <p><strong>健康状态：</strong>待补充</p>
        <p><strong>是否绝育：</strong>未知</p>
        <p><strong>备注：</strong>请勿投喂剩饭剩菜，投喂后请清理包装和垃圾。</p>
      </div>

    </div>
  </section>

  <section id="guide">
    <h2>救助指南</h2>
    <div class="grid">
      <div class="card">
        <h3>发现受伤动物怎么办？</h3>
        <p>先拍照记录，记下大致位置和时间。不要贸然抓捕，避免动物应激或自己受伤。可以联系志愿者协助判断是否需要送医。</p>
      </div>

      <div class="card">
        <h3>发现幼猫怎么办？</h3>
        <p>不要第一时间带走。先观察附近是否有猫妈妈，很多幼猫并不是被遗弃。确认危险或长时间无人照看后，再联系有经验的人处理。</p>
      </div>

      <div class="card">
        <h3>想领养怎么办？</h3>
        <p>领养前需要确认长期照顾能力，包括住宿条件、经济能力、毕业后的安置方案。不要因为一时喜欢而冲动领养。</p>
      </div>
    </div>
  </section>

  <section id="feed">
    <h2>投喂建议</h2>
    <div class="card">
      <p><strong>可以：</strong>猫粮、狗粮、干净饮用水。</p>
      <p><strong>不建议：</strong>剩饭剩菜、高盐、高油、辛辣食物。</p>
      <p><strong>危险：</strong>巧克力、洋葱、葡萄、酒精、尖骨头等。</p>
      <div class="warning">
        投喂后请清理包装和垃圾，尽量不要影响宿舍、食堂、教学区等公共环境。
      </div>
    </div>
  </section>

  <section id="submit">
    <h2>提交发现信息</h2>
    <div class="card">
      <p>如果你在校园里发现新的流浪动物，或者发现已有动物状态变化，可以提交信息帮助更新档案。</p>
      <p>建议提交内容包括：动物照片、出现地点、出现时间、健康状态、是否受伤、备注说明。</p>
      <a class="btn" href="https://docs.qq.com/" target="_blank">提交动物信息</a>
      <p>提示：这里暂时放腾讯文档首页。后面你可以自己创建一个腾讯文档表单，再把按钮链接替换成表单地址。</p>
    </div>
  </section>

  <section id="contact">
    <h2>联系我们 / 志愿者招募</h2>
    <div class="card">
      <p>如果你愿意参与维护，可以帮助拍照、记录、整理信息、更新网页、联系救助资源。</p>
      <p><strong>邮箱：</strong><a href="mailto:gaoguangran_cug@163.com">gaoguangran_cug@163.com</a></p>
      <p><strong>QQ群/微信群：</strong>待补充</p>
      <p>说明：本站为学生自发维护的信息记录页面，不代表学校官方立场。</p>
    </div>
  </section>

  <footer>
    © 2026 CUG 校园流浪动物档案｜学生自发维护
  </footer>

</body>
</html>

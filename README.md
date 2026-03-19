<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LinkedIn README Profile – Roman</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #ffffff;
      color: #111;
      margin: 0;
      padding: 2rem;
    }
    .container {
      max-width: 680px;
      margin: 0 auto;
    }
    .header { margin-bottom: 2rem; }
    .header h1 { font-size: 22px; font-weight: 500; margin: 0 0 4px; }
    .header p { font-size: 15px; color: #666; margin: 0; }

    .quote-block {
      border-left: 2px solid #ccc;
      padding-left: 1rem;
      margin-bottom: 2rem;
      font-size: 15px;
      line-height: 1.7;
    }

    .section-label {
      font-size: 12px;
      font-weight: 500;
      color: #888;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      margin: 0 0 12px;
    }

    .tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 2rem; }
    .tag-primary {
      font-size: 13px; padding: 4px 12px; border-radius: 8px;
      background: #dbeafe; color: #1e40af;
    }
    .tag-secondary {
      font-size: 13px; padding: 4px 12px; border-radius: 8px;
      background: #f3f4f6; color: #555;
    }

    .card {
      background: #fff;
      border: 0.5px solid #ddd;
      border-radius: 12px;
      padding: 1rem 1.25rem;
      margin-bottom: 2rem;
    }
    .card-header {
      display: flex; justify-content: space-between; align-items: baseline;
      margin-bottom: 6px;
    }
    .card-title { font-weight: 500; font-size: 15px; margin: 0; }
    .card-location { font-size: 12px; color: #888; margin: 0; }
    .card-subtitle { font-size: 13px; color: #888; margin: 0 0 10px; }
    .card ul { margin: 0; padding-left: 1.1rem; font-size: 14px; line-height: 1.8; }

    .pillars {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
      margin-bottom: 2rem;
    }
    .pillar {
      background: #f9f9f9;
      border-radius: 8px;
      padding: 12px;
      text-align: center;
    }
    .pillar-icon { font-size: 20px; margin: 0 0 4px; }
    .pillar-label { font-size: 13px; font-weight: 500; margin: 0; }

    .hobbies { font-size: 14px; line-height: 1.7; margin: 0 0 8px; }
    .hobbies-sub { font-size: 13px; color: #666; line-height: 1.6; margin: 0; }

    section { margin-bottom: 2rem; }
  </style>
</head>
<body>
<div class="container">

  <div class="header">
    <h1>👋 Hey, I'm Roman</h1>
    <p>Backend Software Engineer · Milan 🇮🇹 → Zurich 🇨🇭</p>
  </div>

  <div class="quote-block">
    I build <strong>scalable backend systems and APIs</strong> with .NET and Azure — focusing on clean architecture, performance, and production-grade reliability.
    Currently based in Milan and open to opportunities in Zurich.
  </div>

  <section>
    <p class="section-label">Tech stack</p>
    <div class="tags">
      <span class="tag-primary">C# / .NET</span>
      <span class="tag-primary">ASP.NET Core</span>
      <span class="tag-primary">Azure</span>
      <span class="tag-primary">SQL Server</span>
      <span class="tag-secondary">React</span>
    </div>
  </section>

  <section>
    <p class="section-label">Experience</p>
    <div class="card">
      <div class="card-header">
        <p class="card-title">BDO</p>
        <p class="card-location">Milan, IT</p>
      </div>
      <p class="card-subtitle">Backend Software Engineer</p>
      <ul>
        <li>Designed and maintained RESTful APIs used in enterprise production environments</li>
        <li>Optimized SQL Server queries and database schemas for performance at scale</li>
        <li>Contributed to cloud infrastructure on Azure (deployments, monitoring, CI/CD)</li>
      </ul>
    </div>
  </section>

  <section>
    <p class="section-label">What I care about</p>
    <div class="pillars">
      <div class="pillar"><p class="pillar-icon">🏗️</p><p class="pillar-label">Clean architecture</p></div>
      <div class="pillar"><p class="pillar-icon">⚡</p><p class="pillar-label">Performance</p></div>
      <div class="pillar"><p class="pillar-icon">🔒</p><p class="pillar-label">Reliability</p></div>
    </div>
  </section>

  <section>
    <p class="section-label">Beyond the keyboard</p>
    <p class="hobbies">🎾 Tennis &nbsp;·&nbsp; 🏔️ Hiking &nbsp;·&nbsp; 🏃 Running &nbsp;·&nbsp; 📚 Reading</p>
    <p class="hobbies-sub">I approach sport the same way I approach engineering — with consistency, long-term thinking, and a strong preference for process over shortcuts.</p>
  </section>

</div>
</body>
</html>

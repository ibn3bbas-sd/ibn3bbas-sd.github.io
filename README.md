<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ibn Abbas Mohammed Elhadi — Contact</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #F4F2EE;
    --card: #FFFFFF;
    --accent: #1A56DB;
    --accent-light: #EEF3FF;
    --text-primary: #111318;
    --text-secondary: #6B7280;
    --text-muted: #9CA3AF;
    --border: rgba(0,0,0,0.08);
    --shadow: 0 2px 24px rgba(0,0,0,0.07), 0 1px 4px rgba(0,0,0,0.04);
    --radius: 18px;
    --font-body: 'DM Sans', sans-serif;
    --font-mono: 'DM Mono', monospace;
  }

  body {
    font-family: var(--font-body);
    background: var(--bg);
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2rem 1rem;
    background-image: radial-gradient(circle at 20% 20%, rgba(26,86,219,0.05) 0%, transparent 50%),
                      radial-gradient(circle at 80% 80%, rgba(26,86,219,0.04) 0%, transparent 50%);
  }

  .card {
    background: var(--card);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    width: 100%;
    max-width: 440px;
    overflow: hidden;
    border: 1px solid var(--border);
    animation: rise 0.5s cubic-bezier(0.22, 1, 0.36, 1) both;
  }

  @keyframes rise {
    from { opacity: 0; transform: translateY(16px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .card-header {
    padding: 2rem 2rem 1.5rem;
    background: linear-gradient(135deg, #F8F9FF 0%, #FFFFFF 100%);
    border-bottom: 1px solid var(--border);
    position: relative;
  }

  .card-header::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(90deg, #1A56DB, #6B8EF5);
    border-radius: var(--radius) var(--radius) 0 0;
  }

  .avatar-row {
    display: flex;
    align-items: center;
    gap: 16px;
  }

  .avatar {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: var(--accent-light);
    border: 2px solid rgba(26,86,219,0.15);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 17px;
    font-weight: 500;
    color: var(--accent);
    letter-spacing: 0.5px;
    flex-shrink: 0;
  }

  .name-block h1 {
    font-size: 17px;
    font-weight: 500;
    color: var(--text-primary);
    letter-spacing: -0.2px;
    line-height: 1.3;
  }

  .company-link {
    display: inline-flex;
    align-items: center;
    gap: 4px;
    font-size: 12.5px;
    color: var(--accent);
    text-decoration: none;
    margin-top: 3px;
    font-weight: 400;
    transition: opacity 0.15s;
  }
  .company-link:hover { opacity: 0.75; }
  .company-link .arrow {
    font-size: 10px;
    opacity: 0.7;
  }

  .badge {
    display: inline-block;
    margin-top: 8px;
    padding: 3px 10px;
    background: var(--accent-light);
    color: var(--accent);
    font-size: 11px;
    font-weight: 500;
    border-radius: 20px;
    letter-spacing: 0.3px;
    font-family: var(--font-mono);
  }

  .card-body {
    padding: 0 0 0.5rem;
  }

  .row {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    padding: 13px 2rem;
    border-bottom: 1px solid var(--border);
    transition: background 0.12s;
    text-decoration: none;
  }
  .row:last-child { border-bottom: none; }
  .row:hover { background: #FAFBFF; }

  .row-icon {
    width: 32px;
    height: 32px;
    border-radius: 8px;
    background: var(--accent-light);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    margin-top: 1px;
  }

  .row-icon svg {
    width: 15px;
    height: 15px;
    fill: none;
    stroke: var(--accent);
    stroke-width: 1.7;
    stroke-linecap: round;
    stroke-linejoin: round;
  }

  .row-content { flex: 1; min-width: 0; }

  .row-label {
    font-size: 10.5px;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 0.8px;
    font-weight: 500;
    line-height: 1;
    margin-bottom: 3px;
  }

  .row-value {
    font-size: 13.5px;
    color: var(--text-primary);
    font-weight: 400;
    word-break: break-all;
    line-height: 1.4;
  }

  a.row .row-value,
  .row-value.link {
    color: var(--accent);
  }

  .card-footer {
    padding: 1rem 2rem 1.5rem;
    border-top: 1px solid var(--border);
    display: flex;
    gap: 10px;
  }

  .btn {
    flex: 1;
    padding: 10px 14px;
    border-radius: 10px;
    font-size: 13px;
    font-weight: 500;
    font-family: var(--font-body);
    cursor: pointer;
    border: 1px solid var(--border);
    text-align: center;
    text-decoration: none;
    display: inline-block;
    transition: all 0.15s;
  }

  .btn-primary {
    background: var(--accent);
    color: #fff;
    border-color: var(--accent);
  }
  .btn-primary:hover { background: #1547C0; }

  .btn-secondary {
    background: #fff;
    color: var(--text-primary);
  }
  .btn-secondary:hover { background: var(--bg); }
</style>
</head>
<body>

<div class="card">

  <div class="card-header">
    <div class="avatar-row">
      <div class="avatar">IA</div>
      <div class="name-block">
        <h1>Ibn Abbas Mohammed Elhadi</h1>
        <a href="https://wedosolutions.sa" target="_blank" class="company-link">
          Wedo Solutions Arabia <span class="arrow">↗</span>
        </a>
        <div><span class="badge">DevOps</span></div>
      </div>
    </div>
  </div>

  <div class="card-body">

    <a class="row" href="tel:+966534900507">
      <div class="row-icon">
        <svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.07 13a19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 3 2.18h3a2 2 0 0 1 2 1.72c.127.96.361 1.903.7 2.81a2 2 0 0 1-.45 2.11L7.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0 1 21 16.92z"/></svg>
      </div>
      <div class="row-content">
        <div class="row-label">Mobile</div>
        <div class="row-value link">+966 534 900 507</div>
      </div>
    </a>

    <a class="row" href="mailto:ibnabbas.elhadi@wedosolutions.sa">
      <div class="row-icon">
        <svg viewBox="0 0 24 24"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
      </div>
      <div class="row-content">
        <div class="row-label">Work email</div>
        <div class="row-value link">ibnabbas.elhadi@wedosolutions.sa</div>
      </div>
    </a>

    <a class="row" href="mailto:ibn3bbas.mohammed.elhadi@gmail.com">
      <div class="row-icon">
        <svg viewBox="0 0 24 24"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
      </div>
      <div class="row-content">
        <div class="row-label">Personal email</div>
        <div class="row-value link">ibn3bbas.mohammed.elhadi@gmail.com</div>
      </div>
    </a>

    <div class="row" style="cursor:default;">
      <div class="row-icon">
        <svg viewBox="0 0 24 24"><path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0z"/><circle cx="12" cy="10" r="3"/></svg>
      </div>
      <div class="row-content">
        <div class="row-label">Location</div>
        <div class="row-value">Riyadh, Saudi Arabia</div>
      </div>
    </div>

    <a class="row" href="https://www.linkedin.com/in/ibn-abbas-mohammed-elhadi-612868140" target="_blank">
      <div class="row-icon">
        <svg viewBox="0 0 24 24"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
      </div>
      <div class="row-content">
        <div class="row-label">LinkedIn</div>
        <div class="row-value link">ibn-abbas-mohammed-elhadi</div>
      </div>
    </a>

  </div>

  <div class="card-footer">
    <a class="btn btn-primary" href="mailto:ibnabbas.elhadi@wedosolutions.sa">Send email</a>
    <a class="btn btn-secondary" href="tel:+966534900507">Call</a>
  </div>

</div>

</body>
</html>

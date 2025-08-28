---
layout: default
title: Home
---

# 👋 About Me

**Arturo Narváez Fontana**  
Full Stack Developer focused on building enterprise solutions with **.NET and React**, and mobile applications with **Flutter**.  

I also work with **TypeScript, Node.js, Azure, and SQL Server**, always aiming for clean and maintainable code.  

---

## ✔️ Certifications
- <a href="https://www.credly.com/badges/036b9223-a0eb-4421-aaaa-082becda6ff9/linked_in_profile">Professional Scrum Master (PSM)</a> – Scrum.org (certified @ Improving)

---

## 🧰 Tech Stack

<table style="border-collapse: collapse; border: 0; width: 100%;">
  <tr>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/dotnetcore-original.svg" alt=".NET" title=".NET" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">.NET</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/react-original.svg" alt="React" title="React" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">React</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/typescript-original.svg" alt="TypeScript" title="TypeScript" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">TypeScript</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/flutter-original.svg" alt="Flutter" title="Flutter" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">Flutter</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/nodejs.svg" alt="Node.js" title="Node.js" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">Node.js</div>
    </td>
  </tr>
  <tr>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/azure-original.svg" alt="Azure" title="Azure" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">Azure</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/microsoftsqlserver-plain.svg" alt="SQL Server" title="SQL Server" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">SQL Server</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/docker-original.svg" alt="Docker" title="Docker" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">Docker</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/firebase.svg" alt="Firebase" title="Firebase" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">Firebase</div>
    </td>
    <td style="border: 0; text-align: center; padding: 8px; width: 90px;">
      <img src="/assets/vscode.svg" alt="VS Code" title="VS Code" style="width:48px;" /><br/>
      <div style="font-size:12px; margin-top:4px; color:#ccc;">VS Code</div>
    </td>
  </tr>
</table>

---

## 📝 Latest Articles

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%b %d, %Y" }}</small><br/>
      {% if post.excerpt %}
        <span style="color:#9aa0a6;">{{ post.excerpt | strip_html | truncate: 120 }}</span>
      {% endif %}
    </li>
  {% endfor %}
</ul>

<p><a href="{{ '/blog' | relative_url }}">View all articles →</a></p>

<p style="font-size:13px; color:#9aa0a6;">
  <a href="{{ '/feed.xml' | relative_url }}">RSS</a>
</p>

---

## 📫 Get in Touch
- <a href="https://linkedin.com/in/arturo-narvaez-fontana">LinkedIn</a>  
- GitHub: <a href="https://github.com/anarvaezf">@anarvaezf</a>

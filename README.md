<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2048,50:14468f,100:2a7de1&height=300&section=header&text=Mohamed%20Hisham&fontSize=68&fontColor=f4f8ff&fontAlignY=36&desc=Full-stack%20developer&descSize=26&descAlignY=57&descColor=ffb400&animation=fadeIn" width="100%" alt="Mohamed Hisham, full-stack developer" />
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=1100&color=DBE7FF&background=0E2A57&center=true&vCenter=true&width=900&height=52&lines=I+build+the+whole+request+path.;UI%2C+API%2C+payments%2C+database%2C+and+the+Linux+server.;Shipped+to+the+Saudi+and+Egyptian+markets.;Open+to+full-time+roles%2C+including+relocation." alt="I build the whole request path: UI, API, payments, database, and the Linux server. Open to full-time roles, including relocation." />
  <br/><br/>
  <img src="https://img.shields.io/badge/Open%20to-full--time%20roles%2C%20including%20relocation-ffb400?style=for-the-badge&labelColor=0e2a57" alt="Open to full-time roles, including relocation" />
  <br/><br/>
  <img src="https://img.shields.io/badge/UI-Next.js%20%2B%20React-0e2a57?style=flat-square&labelColor=ffb400" alt="UI: Next.js + React" /> &nbsp;&rarr;&nbsp; <img src="https://img.shields.io/badge/API-Node.js%20%2B%20Django-0e2a57?style=flat-square&labelColor=ffb400" alt="API: Node.js + Django" /> &nbsp;&rarr;&nbsp; <img src="https://img.shields.io/badge/Payments-gateways%20%2B%20webhooks-0e2a57?style=flat-square&labelColor=ffb400" alt="Payments: gateways + webhooks" /> &nbsp;&rarr;&nbsp; <img src="https://img.shields.io/badge/Database-MongoDB%20%2B%20PostgreSQL-0e2a57?style=flat-square&labelColor=ffb400" alt="Database: MongoDB + PostgreSQL" /> &nbsp;&rarr;&nbsp; <img src="https://img.shields.io/badge/Server-Linux%20%2B%20Nginx%20%2B%20Docker-0e2a57?style=flat-square&labelColor=ffb400" alt="Server: Linux + Nginx + Docker" />
  <br/><br/>
  <a href="#about"><b>About</b></a> &nbsp;|&nbsp;
  <a href="#request-path"><b>Request path</b></a> &nbsp;|&nbsp;
  <a href="#work"><b>Work</b></a> &nbsp;|&nbsp;
  <a href="#skills"><b>What I do</b></a> &nbsp;|&nbsp;
  <a href="#stack"><b>Stack</b></a> &nbsp;|&nbsp;
  <a href="#activity"><b>Activity</b></a> &nbsp;|&nbsp;
  <a href="#contact"><b>Contact</b></a>
  <br/><br/>
  <img src="https://img.shields.io/badge/Production%20apps-5%2B-163a73?style=for-the-badge&labelColor=0a2048" alt="Production apps: 5+" /> <img src="https://img.shields.io/badge/Markets-Saudi%20Arabia%20%26%20Egypt-163a73?style=for-the-badge&labelColor=0a2048" alt="Markets: Saudi Arabia & Egypt" /> <img src="https://img.shields.io/badge/Freelancing-since%202024-163a73?style=for-the-badge&labelColor=0a2048" alt="Freelancing: since 2024" /> <img src="https://img.shields.io/badge/Deploys-automated%20CI%2FCD-163a73?style=for-the-badge&labelColor=0a2048" alt="Deploys: automated CI/CD" />
</div>

<br/>

<a id="about"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=About&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="About" />

<table align="center">
  <tr>
    <td>
      <ol>
        <li>I build secure, production-ready web applications and take them all the way to production myself.</li>
        <li>I work across the whole stack: interface, API, payments, database, and the Linux server it runs on.</li>
        <li>Computer Science student at EELU (B.Sc., expected 2027), freelancing since 2024.</li>
        <li><b>Open to full-time roles, including relocation.</b></li>
      </ol>
    </td>
  </tr>
</table>

<br/>

<a id="request-path"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=The%20request%20path&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="The request path" />

Every project I ship follows the same route, from a visitor's browser to the database and back. I build each stage, and I deploy it myself.

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#0e2a57","primaryTextColor":"#f4f8ff","primaryBorderColor":"#dbe7ff","lineColor":"#ffb400","secondaryColor":"#0a2048","tertiaryColor":"#0a2048","clusterBkg":"#0a2048","clusterBorder":"#7ea3e0","edgeLabelBackground":"#0e2a57","fontFamily":"ui-monospace, Menlo, Consolas, monospace"}}}%%
flowchart LR
    visitor(["Visitor's browser"]) --> nginx
    subgraph server["Linux server"]
        direction LR
        nginx["Nginx<br/>reverse proxy"] --> ui["Next.js<br/>user interface"]
        ui --> api["API<br/>Node.js or Django"]
        api --> db[("MongoDB<br/>PostgreSQL")]
    end
    api --> pay["Payment<br/>gateway"]
    repo["GitHub<br/>repository"] --> ci["GitHub Actions<br/>build and deploy"]
    ci -. "automated deploy" .-> server
```

<br/>

<a id="work"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=Selected%20work&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="Selected work" />

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://medsupplysa.com/ar"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Saudi%20e-commerce%20platform&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=medsupplysa.com&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Saudi e-commerce platform, medsupplysa.com" /></a><br/>
      <sub>Online store built for the Saudi market.</sub><br/>
      <img src="https://img.shields.io/badge/status-In%20production-ffb400?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://onoffeg.com/ar"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Egyptian%20e-commerce%20platform&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=onoffeg.com&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Egyptian e-commerce platform, onoffeg.com" /></a><br/>
      <sub>Online store built for the Egyptian market.</sub><br/>
      <img src="https://img.shields.io/badge/status-In%20production-ffb400?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://secrela.com/"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Secrela&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=secrela.com&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Secrela, secrela.com" /></a><br/>
      <sub>Live product, built and deployed end to end.</sub><br/>
      <img src="https://img.shields.io/badge/status-In%20production-ffb400?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://frontend-lms-f775.vercel.app/"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Learning%20management%20system&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=frontend-lms-f775.vercel.app&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Learning management system, frontend-lms-f775.vercel.app" /></a><br/>
      <sub>Full-stack platform, deployed on Vercel.</sub><br/>
      <img src="https://img.shields.io/badge/status-Live%20demo-9fc0f2?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://landing-page-realstate.vercel.app/"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Real%20estate%20landing%20page&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=landing-page-realstate.vercel.app&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Real estate landing page, landing-page-realstate.vercel.app" /></a><br/>
      <sub>Responsive marketing page, deployed on Vercel.</sub><br/>
      <img src="https://img.shields.io/badge/status-Live%20demo-9fc0f2?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://landing-page-restaurant-psi.vercel.app/"><img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=110&section=header&text=Restaurant%20landing%20page&fontSize=26&fontColor=f4f8ff&fontAlignY=40&desc=landing-page-restaurant-psi.vercel.app&descSize=16&descAlignY=68&descColor=ffb400&stroke=7ea3e0&strokeWidth=2" width="100%" alt="Restaurant landing page, landing-page-restaurant-psi.vercel.app" /></a><br/>
      <sub>Responsive marketing page, deployed on Vercel.</sub><br/>
      <img src="https://img.shields.io/badge/status-Live%20demo-9fc0f2?style=flat-square&labelColor=0e2a57" alt="Status" />
    </td>
  </tr>
</table>

<br/>

<a id="skills"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=What%20I%20do&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="What I do" />

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>Backend and APIs</h4>
      <ul>
        <li>Secure REST APIs with Node.js, Express, and Django</li>
        <li>Data models in MongoDB and PostgreSQL</li>
        <li>Clean interfaces between the front end and the server</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>Payments and integrations</h4>
      <ul>
        <li>Payment gateways wired into real stores</li>
        <li>Webhooks and third-party services</li>
        <li>Checkout flows tested before launch</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>Deployment</h4>
      <ul>
        <li>Linux servers configured with Nginx</li>
        <li>Docker for repeatable environments</li>
        <li>GitHub Actions for automated CI/CD deploys</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

<a id="stack"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=Tech%20stack&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="Tech stack" />

<table align="center">
  <tr><td align="right"><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=js,ts,py,java&theme=dark" alt="JavaScript, TypeScript, Python, Java" /></td></tr>
  <tr><td align="right"><b>Front end</b></td><td><img src="https://skillicons.dev/icons?i=react,nextjs&theme=dark" alt="React, Next.js" /></td></tr>
  <tr><td align="right"><b>Back end</b></td><td><img src="https://skillicons.dev/icons?i=nodejs,express,django&theme=dark" alt="Node.js, Express, Django" /></td></tr>
  <tr><td align="right"><b>Data</b></td><td><img src="https://skillicons.dev/icons?i=mongodb,postgres&theme=dark" alt="MongoDB, PostgreSQL" /></td></tr>
  <tr><td align="right"><b>Delivery</b></td><td><img src="https://skillicons.dev/icons?i=linux,nginx,docker,githubactions&theme=dark" alt="Linux, Nginx, Docker, GitHub Actions" /></td></tr>
</table>

<br/>

<a id="activity"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=GitHub%20activity&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="GitHub activity" />

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohamed-hesham100&show_icons=true&count_private=true&border_color=4a6fb0&bg_color=0e2a57&title_color=ffb400&icon_color=ffb400&text_color=dbe7ff&rank_icon=github" width="49%" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohamed-hesham100&layout=compact&langs_count=8&border_color=4a6fb0&bg_color=0e2a57&title_color=ffb400&text_color=dbe7ff" width="49%" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mohamed-hesham100&bg_color=0e2a57&color=dbe7ff&line=ffb400&point=ffffff&area=true&area_color=ffb400&hide_border=true&custom_title=Contribution%20activity" width="100%" alt="Contribution activity graph" />
</p>

<br/>

<a id="contact"></a>
<img src="https://capsule-render.vercel.app/api?type=rect&color=0e2a57&height=56&section=header&text=Get%20in%20touch&fontSize=22&fontColor=f4f8ff&fontAlignY=50&stroke=7ea3e0&strokeWidth=1" width="100%" alt="Get in touch" />

> [!TIP]
> Hiring for a full-stack role? I'm open to full-time opportunities, including relocation. Send me a message and I'll reply.

<p align="center">
  <a href="mailto:apohamed1235@gmail.com"><img src="https://img.shields.io/badge/Email-apohamed1235%40gmail.com-163a73?style=for-the-badge&labelColor=ffb400" alt="Email: apohamed1235@gmail.com" /></a>
  <a href="https://www.linkedin.com/in/mohamed-hisham-3362b53a1/"><img src="https://img.shields.io/badge/LinkedIn-mohamed--hisham-163a73?style=for-the-badge&labelColor=ffb400" alt="LinkedIn: mohamed-hisham" /></a>
  <a href="https://portfolio2-tau-inky.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-portfolio2--tau--inky.vercel.app-163a73?style=for-the-badge&labelColor=ffb400" alt="Portfolio: portfolio2-tau-inky.vercel.app" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2048,50:14468f,100:2a7de1&height=170&section=footer&text=Open%20to%20full-time%20roles%2C%20including%20relocation&fontSize=20&fontColor=ffb400&fontAlignY=68" width="100%" alt="Open to full-time roles, including relocation" />

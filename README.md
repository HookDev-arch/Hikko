I welcome everyone who has come to this page. I am a Russian software developer. Since the original creator of Hikka closed the project (it is no longer supported and he decided to start a new one), I decided to breathe life into this project and give it a second chance (or maybe not a second).

This repository is not just a fork of the original. Right now, I'm actively researching and rewriting the code (as you can tell from the commits). As I said above, my goal is not to copy-paste the original code.


<h2>Local installation:</h2>
Simply run this command out of <b>root</b> and follow the instructions of installer:<br>
<code>. <(wget -qO- https://github.com/HookDev-arch/Hikko/blob/master/install.sh)</code><br>
<br>
<b>Manual installation (no script):</b><br>
<code>apt update && apt install git libcairo2 -y && git clone https://github.com/HookDev-arch/Hikko/ && cd Hook && pip install -r requirements.txt && python3 -m hikka</code><br.>
<i>If you are on VPS\VDS, type <code>--proxy-pass</code> in the end of command to open SSH tunnel to your Hook web interface, or use <code>--no-web</code> to complete setup in console</i><br>
<br>
<b>Some further details:</b>

<details>
 <summary>Pre-installed automatic database backuper</summary>
 <img src="https://user-images.githubusercontent.com/36935426/202905566-964d2904-f3ce-4a14-8f05-0e7840e1b306.png" width="300">
</details>
<details>
 <summary>Welcome installation info</summary>
 <img src="https://user-images.githubusercontent.com/36935426/202905720-6319993b-697c-4b09-a194-209c110c79fd.png" width="300">
 <img src="https://user-images.githubusercontent.com/36935426/202905746-2a511129-0208-4581-bb27-7539bd7b53c9.png" width="300">
</details>

<hr>
<h2><img src="https://github.com/hikariatama/assets/raw/master/35-edit-flat.webp" height="54" align="middle"> Changes</h2>

<ul>
 <li>🆕 <b>Latest Telegram layer</b> with reactions, video stickers and other stuff</li>
 <li>🔓 <b>Security</b> improvements, including <b>native entity caching</b> and <b>targeted security rules</b></li>
 <li>🎨 <b>UI/UX</b> improvements</li>
 <li>📼 Improved and new <b>core modules</b></li>
 <li>⏱ Quick <b>bug fixes</b> (compared to official FTG and GeekTG)</li>
 <li>▶️ <b>Inline forms, galleries and lists</b></li>
 <li>🔁 Full <b>backward compatibility</b> with FTG, GeekTG and Dragon Userbot modules</li>
</ul>
<hr>
<h2 border="none"><img src="https://github.com/hikariatama/assets/raw/master/1312-micro-sd-card-flat.webp" height="54" align="middle"> Requirements</h2>
<ul>
 <li>Python 3.8+</li>
 <li>API_ID and HASH from <a href="https://my.telegram.org/apps" color="#2594cb">Telegram</a></li>
</ul>
<hr>
<h2 border="none"><img src="https://github.com/hikariatama/assets/raw/master/680-it-developer-flat.webp" height="54" align="middle"> Documentation</h2>

Check out <a href="https://dev.Hook.pw">dev.Hook.pw</a> for developers' documentation and <a href="https://Hook.pw">Hook.pw</a> for users' documentation<br>

<hr>
<h2 border="none"><img src="https://github.com/hikariatama/assets/raw/master/981-consultation-flat.webp" height="54" align="middle"> <a href="https://t.me/hikka_talks">Support</a></h2>
<hr>
<h2 border="none"><img src="https://github.com/hikariatama/assets/raw/master/541-hand-washing-step-12-flat.webp" height="54" align="middle"> Features</h2>
<table>
 <tr>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/1286-three-3-key-flat.webp" height="32" align="middle"><b> Forms - bored of writing? Use buttons!</b>
  </td>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/61-camera-flat.webp" height="32" align="middle"><b> Galleries - scroll your favorite photos in Telegram</b>
  </td>
 </tr>
 <tr>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/202842205-9a3906f8-37b1-47f4-acd1-ae441f84aeab.gif">
  </td>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/202842215-b7bddaf2-f544-4823-80b4-5c2cccaf2157.gif">
  </td>
 </tr>
</table>
<table>
 <tr>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/216-arrow-5-flat.webp" height="32" align="middle"><b> Inline - share userbot with your friends</b>
  </td>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/1054-amazon-echo-speaker-flat.webp" height="32" align="middle"><b> Bot interactions - "No PM"? No problem. Feedback bot at your service</b>
  </td>
 </tr>
 <tr>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/202842234-e53f616d-7423-4a64-a5da-fb71282ad2c4.gif">
  </td>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/160476037-9537f1c7-8b72-408f-b84c-b89825930bf5.gif">
  </td>
 </tr>
</table>
<table>
 <tr>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/1140-error-flat.webp" height="32" align="middle"><b> InlineLogs - traceback directly in message, caused error</b>
  </td>
  <td>
   <img src="https://github.com/hikariatama/assets/raw/master/35-edit-flat.webp" height="32" align="middle"><b> Grep - execute command and get only required lines</b>
  </td>
 </tr>
 <tr>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/202842250-b60d218e-9df4-47f6-8c67-b2ef641b4d2d.gif">
  </td>
  <td>
   <img src="https://user-images.githubusercontent.com/36935426/202842263-ee2d5c94-3fd5-43b3-b8ac-2397b69e0fc6.gif">
  </td>
 </tr>
</table>

<b>👨‍👦 NoNick, NoNickUser, NoNickCmd, NoNickChat - use another account for userbot</b>
<img src="https://user-images.githubusercontent.com/36935426/202842278-37fbc518-1679-45d7-92f5-9e519275630d.png">

<hr>
<i>⚠️ This project is provided as-is. Developer doesn't take ANY responsibility over any problems, caused by userbot. By installing Hook you take all risks on you. This is but not limited to account bans, deleted (by Telegram algorithms) messages, SCAM-modules, leaked sessions (due to SCAM-modules). It is <b>highly</b> recommended to enable the API Flood protection (.api_fw_protection) and not to install many modules at once. By using Hook you give your consent to any actions made by your account in background in purposes of automatization. Please, consider reading https://core.telegram.org/api/terms for more information.</i>

<b>Special thanks to:</b>

<ul>
    <li><a href="https://gitlab.com/hackintosh5">Hackintosh5</a> for FTG, which is the base of project</li>
    <li><a href="https://t.me/kazunimo">Kazunimo</a> for Turkish translation pack</li>
    <li><a href="https://t.me/hegaNET">Hegakura</a> for Tatar translation pack</li>
    <li><a href="https://t.me/tiefeschwarz">Aldehydesäure</a> for German translation pack</li>
    <li><a href="https://t.me/amorescam">Amore</a> for Uzbek translation pack</li>
    <li><a href="https://t.me/lonami">Lonami</a> for Telethon, which is the base of Hook-TL</li>
    <li><a href="https://github.com/delivrance">Dan</a> for pyrogram, which is the base of Hook-Pyro</li>
</ul>

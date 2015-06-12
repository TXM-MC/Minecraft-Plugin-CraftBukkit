# Minecraft-Plugin-CraftBukkit
## Requirements to run it:
<img src="https://TXM-MC.homeserver.com/Content/icon/file-bat.png" /> A CraftBukkit-server version: 1.5.\*, 1.7.\*, 1.8.*<br />
<img src="https://TXM-MC.homeserver.com/Content/icon/file-folder.png" /> Place in "<b>your-server-folder/plugins/</b>" folder.<br />
<img src="https://TXM-MC.homeserver.com/Content/icon/file-TXM.png" /> Start your server (or Restart/reload it if it's<br /> running).
## Commands (01/05/2015) :
<table>
  <thead>
    <tr>
      <th>In Game Commands:</th>
      <th>Console Commands:</th>
      <th>Permission Nodes:</th>
      <th>Command Executes:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/HUB</td>
      <td rowspan="8"><i>Cannot be executed from console without a <b>sudo-command-plugin</b>.</i></td>
      <td>txm.mc.teleport.hub</td>
      <td>Teleports the %PLAYER% to server's start worlds "<b>HUB</b>" / "<b>SPAWN</b></td>
    </tr>
    <tr>
      <td>/TXM</td>
      <td>txm.mc.supertool</td>
      <td rowspan="2">Enables and gives the<br /><b>"TXM-MC test supertool"</b> (a Dimond Pickaxe, in hand)</td>
    </tr>
    <tr>
      <td>/enableTXM</td>
      <td>txm.mc.enable</td>
    </tr>
    <tr>
      <td>/disableTXM</td>
      <td>txm.mc.disable</td>
      <td>Disables and removes the<br /><b>"TXM-MC test supertool"</b> (a Dimond Pickaxe, in hand)</td>
    </tr>
    <tr>
      <td>/color<br />/colors<br />/c</td>
      <td>txm.mc.chat.display.colors</td>
      <td>Displays for the sender all the colors codes: <br />"<b>0123456789ABCDEF</b>"</td>
    </tr>
    <tr>
      <td>/style<br />/styles</td>
      <td>txm.mc.chat.display.styles</td>
      <td>Displays for the sender all the styles codes: <br />"<b>L = BOLD, </b>"</td>
    </tr>
    <tr>
      <td>/all<br />/styles</td>
      <td>txm.mc.chat.display.styles</td>
      <td>Displays for the sender all the styles codes: <br />"<b>L = BOLD, N = UNDERLINE, </b>"</td>
    </tr>
    <tr>
      <td>/hi<br />/hey<br />/hello<br />/hej</td>
      <td>txm.mc.chat.display.greetings.message</td>
      <td>Displays for the sender a greeting response: <br />"<b>Hello %PLAYER%!</b>"</td>
    </tr>
  </tbody>
</table>
<b>\*The strike-thru words are commands that do not work "<s>example.text</s>"</b><br />
<b>\*This GitHub repository does not contain the entire project code due to security.</b>

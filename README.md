# CS-GO-server-installer
This script is based on LGSM from Daniel Gibbs (dgibbs64) https://github.com/dgibbs64/linuxgsm

<h2>Main features</h2>
<ul>
	<li>Backup</li>
	<li>Console</li>
	<li>Details</li>
	<li>Installer (SteamCMD)</li>
	<li>Monitor (including email notification)</li>
	<li>Update (SteamCMD)</li>
	<li>Start/Stop/Restart server</li>
	<li>Announce Server Restart</li>
	<li>Announce Backup start and end</li>
  <li>Announce Server Shutdown</li>
  <li>Send msg go to server</li>
</ul>

<h2>Usage</h2>
Server restart (fast)
<code>./csgoserver restart fast</code>
This will announce 10 second countdown to restart the server.

Server restart
<code>./csgoserver restart</code>
This will announce 1 minute countdown to restart the server.

Server shutdown (fast)
<code>./csgoserver shutdown fast</code>
This will announce 1 minute countdown to shutdown the server.

Send message to server
<code>./csgoserver msg Hello</code>

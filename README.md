# network infrastructure INT

<h1> GESTION </h1>
<p>
  SERVER : MARTY <br>
  DOMAINE : ABC.FR <br>
  NAME : VM-GESTION <br>
  IP : 192.168.4.11 <br>
  OS : DEBIAN 12 <br>
  SERVICES : NEXTCLIUD + DOLIBARR <br>
  ID ADMIN : root // ABCroot$ <br>
  ID USER : utilisateur // utilisateur <br>
</p>

<h1> WINDOWS SERVER  2022 PRIMARY </h1>
<p>
  SERVER : KYLE <br>
  DOMAINE : ABC.FR <br>
  NAME : VM-KYLE - AD<br>
  IP : 192.168.4.10 <br>
  OS : WINDOWS SERVER 2022 <br>
  SERVICES : ACTIVE DIRECTORY + DNS + DHCP <br>
  ID ADMIN : ABC\Administrateur // ABCroot$ <br>
</p>

<h1> GLPI </h1>
<p>
  SERVER : MELMAN <br>
  DOMAINE : ABC.FR <br>
  NAME : VM-GLPI <br>
  IP : 192.168.5.11 <br>
  OS : DEBIAN 12 <br>
  SERVICES : GLPI <br>
  ID ADMIN : root // ABCroot$ <br>
  ID USER : utilisateur // utilisateur <br>
</p>

<h1> WINDOWS SERVER  2022 SECONDARY </h1>
<p>
  SERVER : KENNY <br>
  DOMAINE : ABC.FR <br>
  NAME : VM-KYLE - AD2<br>
  IP : 192.168.5.10 <br>
  OS : WINDOWS SERVER 2022 <br>
  SERVICES : ACTIVE DIRECTORY + DNS + DHCP (BACKUP) <br>
  ID ADMIN : ABC\Administrateur // ABCroot$ <br>
</p>

<h1> CHECKMK </h1>
<p>
  SERVER : KENNY <br>
  DOMAINE : ABC.FR <br>
  NAME : DEBIAN-CHECKMK <br>
  IP : 192.168.5.115/monitoring <br>
  OS : DEBIAN 12 <br>
  SERVICES : CHECKMK <br>
  ID ADMIN : root // ABCroot$ <br>
  ID USER : utilisateur // ABCroot$ <br>
  ID ADMIN WEB : cmkadmin // ABCroot$ <br>
</p>

<h1> LIBRENMS </h1>
<p>
  SERVER : KYLE <br>
  DOMAINE : ABC.FR <br>
  NAME : SRV-LIBRENMS<br>
  IP : 192.168.4.106<br>
  OS : DEBIAN 12 <br>
  SERVICES : LIBRENMS <br>
  ID ADMIN : root // !nterf0r <br>
  ID USER : interfor // interfor <br>
  ID ADMIN WEB : admin // ABCroot$<br>
</p>

<h1> FOG </h1>
<p>
  SERVER : KYLE <br>
  DOMAINE : ABC.FR <br>
  NAME : SRV-FOG<br>
  IP : 192.168.4.101<br>
  OS : DEBIAN 12 <br>
  SERVICES : FOG <br>
  ID ADMIN : root // !nterf0r <br>
  ID USER : interfor // interfor <br>
  ID ADMIN WEB : fog // password<br>
</p>

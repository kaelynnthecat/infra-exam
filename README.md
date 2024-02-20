# infra INT

<h1> GESTION </h1>
<p>
  SERVER : MARTY
  DOMAINE : ABC.FR
  NAME : VM-GESTION
  IP : 192.168.4.11
  OS : DEBIAN 12
  SERVICES : NEXTCLIUD + DOLIBARR
  ID ADMIN : root // ABCroot$
  ID USER : utilisateur // utilisateur
</p>

<h1> WINDOWS SERVER  2022 PRIMARY </h1>
<p>
  SERVER : KYLE
  DOMAINE : ABC.FR
  NAME : VM-KYLE
  IP : 192.168.4.10
  OS : WINDOWS SERVER 2022
  SERVICES : ACTIVE DIRECTORY + DNS + DHCP
  ID ADMIN : ABC\Administrateur // ABCroot$
</p>

<h1> GLPI </h1>
<p>
  SERVER : MELMAN
  DOMAINE : ABC.FR
  NAME : VM-GLPI
  IP : 192.168.5.11
  OS : DEBIAN 12
  SERVICES : GLPI
  ID ADMIN : root // ABCroot$
  ID USER : utilisateur // utilisateur
</p>

<h1> WINDOWS SERVER  2022 SECONDARY </h1>
<p>
  SERVER : KENNY
  DOMAINE : ABC.FR
  NAME : VM-KYLE
  IP : 192.168.5.10
  OS : WINDOWS SERVER 2022
  SERVICES : ACTIVE DIRECTORY + DNS + DHCP (BACKUP)
  ID ADMIN : ABC\Administrateur // ABCroot$
</p>

<h1> CHECKMK </h1>
<p>
  SERVER : KENNY
  DOMAINE : ABC.FR
  NAME : DEBIAN-CHECKMK
  IP : 192.168.5.115/monitoring
  OS : DEBIAN 12
  SERVICES : CHECKMK
  ID ADMIN : root // ABCroot$
  ID USER : utilisateur // ABCroot$
  ID ADMIN WEB : cmkadmin // ABCroot$
</p>

<h1> LIBRENMS </h1>
<p>
  SERVER : KYLE
  DOMAINE : ABC.FR
  NAME :
  IP :
  OS : DEBIAN 12
  SERVICES : LIBRENMS
  ID ADMIN : root // !nterf0r
  ID USER : interfor // interfor
  ID ADMIN WEB :
</p>

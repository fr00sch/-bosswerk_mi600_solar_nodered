This flow extracts the data from the Bosswerk Mi300/600.
You have to set your IP-Adresse and perhaps the Auth-Data.

The flow grabs the subframe "status.html" of the http://192.168.x.x/index_cn.html

looks for the javascript-code-Blocks and in this part are the relevant data for the solar inverter.

This idea comes from the Python-script: https://github.com/Skarabaen/BosswerkMI600
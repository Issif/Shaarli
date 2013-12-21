ShaarliLDAP 
------------------------------------------------------------------------------
_See above for licence_

This version of Shaarli works with a LDAP as authentication method.

See http://sebsauvage.net/wiki/doku.php?id=php:shaarli for install method,
everything is same except install parameters :

![LDAP Settings](https://raw.github.com/Issif/ShaarliLDAP/master/images/ldap_settings.png)

* **LDAP Server**: IP or URL of your LDAP
* **LDAP BaseDN**: your BaseDN for LDAP Bind
* **LDAP User**: DN of a user with right to read	
* **LDAP User Password**: Password of the user
* **LDAP Search Filter Begin**: Beginning of the Search Filter
* **LDAP Search Filter End** : End of the Search Filter

The search filter is in 2 parts because $login entered by user will be insert
between two parts.

------------------------------------------------------------------------------
Shaarli is distributed under the zlib/libpng License:

Copyright (c) 2011 Sébastien SAUVAGE (sebsauvage.net)

This software is provided 'as-is', without any express or implied warranty.
In no event will the authors be held liable for any damages arising from
the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it 
freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not 
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would
     be appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must
     not be misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.

------------------------------------------------------------------------------
Thanks to SebSauvage for his tools.

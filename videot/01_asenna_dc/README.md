# 01 Domain Controllerin asennus

1. Käytetty 'sconfig'-komentoa:
    - Tietokoneen nimen muutoksessa
    - IP-osoitteen muutoksessa staattiseksi
    - DNS-palvelimen vaihtamiseen omaan IP-osoitteeseen

2. Asennettu Windowsin ominaisuus "Active Directory"

'''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
'''


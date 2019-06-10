# CAPES Portal Joomla! IDG2

#ATENÇÃO
Após a instalação, altera imediatamente a senha do usuário admin.

##Instalação

###Pré-requisitos
 - Centos 7+
 - PHP 7.2+
 - MySQL-Community

O processo de instalação consiste em, em um servidor Centos 7+, instalar os seguintes serviços:
- NGinx
- PHP-FPM
- MySQL-Community ou MariaDB
- Criar VHOST para o domínio pretendido
- Restaurar o banco de dados `portal-idg2\database\portalcapes-idg2019.sql`

Se preferir, baixe o instalador `https://github.com/CAPES/portal-idg-instalador.git` e, servidor web que hosperará o portal, execute:
`
 $ sudo install.sh www.dominio-portal.gov.br
`
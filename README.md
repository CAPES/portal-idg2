# CAPES Portal Joomla! IDG2

## ATENÇÃO
Após a instalação, alterar imediatamente a senha do usuário *admin*.

### Instalação

#### Pré-requisitos
 - Centos 7+
 - PHP-FPM 7.2+
 - MySQL-Community

O processo de instalação consiste em instalar os seguintes serviços num servidor Centos 7+:
- NGinx
- PHP-FPM
- MySQL-Community ou MariaDB
- Criar VHOST para o domínio pretendido
- Restaurar o banco de dados `portal-idg2\database\portalcapes-idg2019.sql`
- Ajustar as configurações do arquivo *Configuration.php*

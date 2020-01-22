# cheatsheet_java
Generate java keystore:
keytool -genseckey -keystore <name>.jks -keyalg HmacSHA256 -keysize 512 -alias <name> -storetype jceks

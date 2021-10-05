# config-server
This repo requires
- Java 11 
- Gradle version of 6.8.1
- Git hub repo with applocation properties
- access to Hashicorp Vault with application properties

## To run this project, please configure below VM arguments

-Dapp.repo.github.username=<github-username> <br>
-Dapp.repo.github.password=<github-password> <br>
-Dapp.repo.github.uri=<https://github.com/repo-name> <br>
-Dvault.host=or.vault.comcast.com. <br>
-Dvault.loginpath=<vault login path>. <br>
-Dvault.port=<vault-port:443>. <br>
-Dvault.org=<vault-org>. <br>
-Dvault.roleId=<vault-app-roleId> <br>
-Dvault.secretId=<vault-app-secretId> <br>

# Principais

A branch principal do seu repositório é de sua escolha, mas como boa prática para a padronização, o mesmo deverá ser a branch `master`.

Na branch `origin/master`, SEMPRE conterá o código que está pronto para produção.

- [master](master.md)

A branch `origin/dev`, será idêntico a branch `origin/master`, com alterações que foram desenvolvidas recentemente e estão prontas para o `release`. Ele é considerado a branch de integração, onde os demais branches auxiliares, deverão ser criados a partir deste.

Quando a branch `dev` estiver estável e pronta, será criado a branch `release`, onde o mesmo terá uma nova versão para produção. Nessa etapa, que normalmente ocorre a etapa de homologação das alterações. Estando tudo certo, com as novas funcionalidades, o mesmo deverá ser mesclado na branch `master`.

- [dev](dev.md)
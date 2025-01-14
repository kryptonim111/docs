---
title: Gerenciando acesso ao repositório para seus codespaces
shortTitle: Acesso ao repositório
intro: 'Você pode gerenciar os repositórios que {% data variables.product.prodname_codespaces %} pode acessar.'
product: '{% data reusables.gated-features.codespaces %}'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Codespaces
  - Security
redirect_from:
  - /codespaces/managing-your-codespaces/managing-access-and-security-for-your-codespaces
---

 

When you enable access and security for a repository owned by your personal account, any codespaces that are created for that repository will have read permissions to all other repositories you own. Se você deseja restringir os repositórios que um código pode acessar, você pode limitá-lo tanto para o repositório no qual o código foi aberto ou para repositórios específicos. Você só deve habilitar o acesso e a segurança para repositórios nos quais confia.

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.codespaces-tab %}
1. Under "Access and security", select the setting you want for your personal account. ![Botões de opção para gerenciar repositórios confiáveis](/assets/images/help/settings/codespaces-access-and-security-radio-buttons.png)
1. Se você escolher "repositórios selecionados", selecione o menu suspenso e clique em um repositório para permitir que os codespaces do repositório tenham acesso a outros repositórios dos quais você é proprietário. Repita para todos os repositórios cujos codespaces você deseja que acessem outros repositórios dos quais você é proprietário. ![Menu suspenso "Repositórios selecionados"](/assets/images/help/settings/codespaces-access-and-security-repository-drop-down.png)

## Leia mais

- "[Gerenciando o acesso ao repositório para os codespaces da sua organização](/codespaces/managing-codespaces-for-your-organization/managing-repository-access-for-your-organizations-codespaces)"

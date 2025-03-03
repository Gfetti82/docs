---
title: 'Crear una {% data variables.product.prodname_project_v1 %}'
intro: 'Los {% data variables.projects.projects_v1_boards_caps %} pueden utilizarse para crear flujos de trabajo personalizados que se acoplen a tus necesidades, como rastrear y priorizar el trabajo de características específicas, itinerarios integrales o incluso listas de verificación.'
redirect_from:
  - /github/managing-your-work-on-github/managing-project-boards/creating-a-project-board
  - /articles/creating-a-project
  - /articles/creating-a-project-board
  - /github/managing-your-work-on-github/creating-a-project-board
versions:
  feature: projects-v1
topics:
  - Pull requests
  - Issues
  - Projects
  - Project management
type: how_to
allowTitleToDifferFromFilename: true
---

{% data reusables.projects.project_boards_old %}

{% data reusables.project-management.use-automated-template %}

{% data reusables.project-management.copy-project-boards %}

{% data reusables.project-management.link-repos-to-project-board %} Para obtener más información, consulta la sección "[Enlazar un repositorio a un {% data variables.product.prodname_project_v1 %}](/articles/linking-a-repository-to-a-project-board)".

Una vez que hayas creado tu {% data variables.projects.projects_v1_board %}, puedes agregar propuestas, solicitudes de cambio y notas a este. Para obtener más información, consulta la sección "[Agregar propuestas y solicitudes de cambio a un {% data variables.product.prodname_project_v1 %}](/articles/adding-issues-and-pull-requests-to-a-project-board)" y "[Agregar notas a un {% data variables.product.prodname_project_v1 %}](/articles/adding-notes-to-a-project-board)".

También puedes configurar automatizaciones de flujo de trabajo para mantener sincronizado a tu {% data variables.projects.projects_v1_board %} con el estado de las propuestas y solicitudes de cambios. Para obtener más información, consulta la sección "[Acerca de la automatización para los {% data variables.product.prodname_projects_v1 %}](/articles/about-automation-for-project-boards)".

{% data reusables.project-management.project-board-import-with-api %}

## Crear un {% data variables.projects.projects_v1_board %} perteneciente a un usuario

{% data reusables.projects.classic-project-creation %}

{% data reusables.profile.access_profile %}
2. En la parte superior de tu página de perfil, en la navegación principal, haz clic en {% octicon "project" aria-label="The project board icon" %} **Proyectos**. ![Project tab](/assets/images/help/projects/user-projects-tab.png){% ifversion projects-v2 %}
1. Haz clic en **Proyectos (clásico)**{% endif %}
{% data reusables.project-management.click-new-project %}
{% data reusables.project-management.create-project-name-description %}
{% data reusables.project-management.choose-template %}
{% data reusables.project-management.choose-visibility %}
{% data reusables.project-management.linked-repositories %}
{% data reusables.project-management.create-project-button %}
{% data reusables.project-management.add-column-new-project %}
{% data reusables.project-management.name-project-board-column %}
{% data reusables.project-management.select-column-preset %}
{% data reusables.project-management.select-automation-options-new-column %}
{% data reusables.project-management.click-create-column %}
{% data reusables.project-management.add-more-columns %}

{% data reusables.project-management.edit-project-columns %}

## Crear un {% data variables.projects.projects_v1_board %} de toda la organización

{% data reusables.projects.classic-project-creation %}

{% data reusables.profile.access_org %}
{% data reusables.user-settings.access_org %}
{% data reusables.organizations.organization-wide-project %}{% ifversion projects-v2 %}
1. Haz clic en **Proyectos (clásico)**{% endif %}
{% data reusables.project-management.click-new-project %}
{% data reusables.project-management.create-project-name-description %}
{% data reusables.project-management.choose-template %}
{% data reusables.project-management.choose-visibility %}
{% data reusables.project-management.linked-repositories %}
{% data reusables.project-management.create-project-button %}
{% data reusables.project-management.add-column-new-project %}
{% data reusables.project-management.name-project-board-column %}
{% data reusables.project-management.select-column-preset %}
{% data reusables.project-management.select-automation-options-new-column %}
{% data reusables.project-management.click-create-column %}
{% data reusables.project-management.add-more-columns %}

{% data reusables.project-management.edit-project-columns %}

## Crear un {% data variables.projects.projects_v1_board %} de un repositorio

{% data reusables.projects.classic-project-creation %}

{% data reusables.repositories.navigate-to-repo %}
2. En el nombre de tu repositorio, haz clic en {% octicon "project" aria-label="The project board icon" %} **Proyectos**. ![Project tab](/assets/images/help/projects/repo-tabs-projects.png){% ifversion projects-v2 %}
1. Haz clic en **Proyectos (clásico)**{% endif %}
{% data reusables.project-management.click-new-project %}
{% data reusables.project-management.create-project-name-description %}
{% data reusables.project-management.choose-template %}
{% data reusables.project-management.create-project-button %}
{% data reusables.project-management.add-column-new-project %}
{% data reusables.project-management.name-project-board-column %}
{% data reusables.project-management.select-column-preset %}
{% data reusables.project-management.select-automation-options-new-column %}
{% data reusables.project-management.click-create-column %}
{% data reusables.project-management.add-more-columns %}

{% data reusables.project-management.edit-project-columns %}

## Leer más

- "[Acerca de los tableros de proyectos](/articles/about-project-boards)"
- "[Editar un tablero de proyecto](/articles/editing-a-project-board)"{% ifversion fpt or ghec %}
- "[Copying a project board](/articles/copying-a-project-board)"{% endif %}
- "[Cerrar un tablero de proyecto](/articles/closing-a-project-board)"
- "[Acerca de la automatización de los tableros de proyecto](/articles/about-automation-for-project-boards)"

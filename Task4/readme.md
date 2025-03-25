# Ролевая модель

| Роль          | Права роли                      | Группы пользователей                      |
| ------------- | --------------------------------| ----------------------------------------- |
| secret-reader | secrets: get, list              | product-owner                             |
| devops-access | pods: get, list, create, delete | devops                                    |
| pod-reader    | pods: get, list, watch          | product-owner, developer, support         |

# Скрипты

- Создание пользователей ./users.sh
- Создание ролей ./roles.sh
- Создание привязок ./bindings.sh

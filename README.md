# devops-netology

Будут проигнорированы:

 - Локальная директория ./terraform (всё её содержимое)
 - Файлы .tfstate
 - Файлы crash.log и crash.*.log
 - Все файлы *.tfvars и *.tfvars.json (так как они обычно содержат авторизационные данные)
 - Файлы override.tf override.tf.json *_override.tf *_override.tf.json (содержат ссылки на локальные данные)
 - Файлы конфигурации CLI .terraformrc и terraform.rc

Остальные пункты закомментированы.

Новая строчка для  ветки fix.

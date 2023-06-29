# devops-netology
# Баранов Сергей

Задание 3

Локальные каталоги .terraform
не обрабатывать файлы, имя которых заканчивается на .terraform

не обрабатывать файлы, имя которых заканчивается на
*.tfstate
*.tfstate.*

Файлы журнала логов
crash.log
crash.*.log

Исключать  все файлы .tfvars, которые могут содержать конфиденциальные данные
*.tfvars
*.tfvars.json

Игнорировать файлы переопределения
override.tf
override.tf.json
*_override.tf
*_override.tf.json

Игнорировать файлы конфигурации CLI
.terraformrc
terraform.rc

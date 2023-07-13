# devops-netology
Test
Так как основной(в корне) .gitignore пустой, то будет задействован пока только .gitignore из папки terraform

Будут пропущены все каталоги .terraform во всех подкаталогах
Игнорировать все файлы в текущей dir с расширением .tfstate, а так же все файлы у которых перед любым расширением есть ".tfstate"
Пропустить в текущей папке документ crash.log, а так же crash.любыесимволы.log
Игнорировать все файлы в текущей dir с расширением .tfvars, а так же все файлы заканчивающиеся на tfvars.json 
Пропустить файлы в текущей dir override.tf, override.tf.json, любыесимволы_override.tf, любыесимволы_override.tf.json
Игнорировать файл .terraformrc и файл terraform.rc

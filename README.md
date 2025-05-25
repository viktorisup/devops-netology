# devops-netology
# First changr this file
# Two change
### в ./terraform/.gitignore будут проигнорированы файлы связанные с тераформом
.terraform/ - будут игнорироваться директории
*.tfstate - будут игнорироваться все файлы заканчивающиеся на .tfstate
*.tfstate.* - будут игнорироваться все файлы середина которых содержит .tfstate.
crash.log - игнорируется конкретный файл
crash.*.log - игнорируются все файлы начинающиеся crash. и заканчивающиеся .log
*.tfvars - так же все с окончанием .tfvars
*.tfvars.json - все с окончанием .tfvars.json
override.tf - игнорить конкретный файл
override.tf.json - конкретный файл
*_override.tf - все файлы с окончанием  _override.tf 
*_override.tf.json - все файлы с окончанием _override.tf.json
.terraform.tfstate.lock.info - конкретный файл
.terraformrc - конкретный файл
terraform.rc - конкретный файл

## Гит игнорирует файлы или каталоги содержащиеся в .gitignore используя простые патерны
пример синтаксиса
*.log — игнорировать все файлы с расширением .log.
temp/ — игнорировать весь каталог temp.
!important.log — не игнорировать файл important.log, если он был указан ранее в игнорируемых паттернах.
*.{jpg,png,gif} — игнорировать файлы с расширениями .jpg, .png и .gif.
**/*.tmp — игнорировать все файлы с расширением .tmp в любом каталоге.
/config — игнорировать каталог config в корне репозитория.

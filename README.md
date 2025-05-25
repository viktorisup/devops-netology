# devops-netology
# First changr this file
# Two change
### в ./terraform/.gitignore будут проигнорированы файлы связанные с тераформом
.terraform/ - будут игнорироваться директории<br>
*.tfstate - будут игнорироваться все файлы заканчивающиеся на .tfstate<br>
*.tfstate.* - будут игнорироваться все файлы середина которых содержит .tfstate.<br>
crash.log - игнорируется конкретный файл<br>
crash.*.log - игнорируются все файлы начинающиеся crash. и заканчивающиеся .log<br>
*.tfvars - так же все с окончанием .tfvars<br>
*.tfvars.json - все с окончанием .tfvars.json<br>
override.tf - игнорить конкретный файл<br>
override.tf.json - конкретный файл<br>
*_override.tf - все файлы с окончанием  _override.tf<br> 
*_override.tf.json - все файлы с окончанием _override.tf.json<br>
.terraform.tfstate.lock.info - конкретный файл<br>
.terraformrc - конкретный файл<br>
terraform.rc - конкретный файл<br>

## Гит игнорирует файлы или каталоги содержащиеся в .gitignore используя простые патерны
пример синтаксиса<br>
*.log — игнорировать все файлы с расширением .log.<br>
temp/ — игнорировать весь каталог temp.<br>
!important.log — не игнорировать файл important.log, если он был указан ранее в игнорируемых паттернах.<br>
*.{jpg,png,gif} — игнорировать файлы с расширениями .jpg, .png и .gif.<br>
**/*.tmp — игнорировать все файлы с расширением .tmp в любом каталоге.<br>
/config — игнорировать каталог config в корне репозитория.<br>

new line
new line for commit IDE

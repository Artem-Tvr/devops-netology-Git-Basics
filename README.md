# devops-netology

# Local .terraform directories
#**/.terraform/* - исключить все файлы с расширением .terraform из вложенных директорий в корневом каталоге

# .tfstate files
#*.tfstate - исключить все файлы из всех каталогов с расширением .tfstate 
#*.tfstate.* - исключить все файлы из всех каталогов с расширением .tfstate.

# Crash log files
#crash.log - исключить все файлы из всех каталогов с таким именем

# Exclude all .tfvars files, which are likely to contain sentitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
#
#*.tfvars-  исключить все файлы с расширением .tfvars

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
#override.tf-  исключить все файлы из всех катологов с таким именем
#override.tf.json -  исключить все файлы из всех катологов с таким именем
#*_override.tf -  исключить все файлы из всех катологов с таким окончанием расширения
#*_override.tf.json -  исключить все файлы из всех катологов с таким окончанием имени и расширения

# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf - закомментировано

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan* -  закомментировано

# Ignore CLI configuration files
#.terraformrc -  исключить все файлы из всех каталогов с расширением .terraformrc
#terraform.rc -  исключить все файлы из всех каталогов с именем terraform.rc
Игнорировать файлы или каталоги с именем .terraform где-либо/во всех каталогах (относительно файла .gitignore), а также любые файлы или каталоги ниже самой .terraform:  
\**/.terraform/\*  

Игнорировать любые файлы с расширением .tfstate или .tfstate.что-то_еще:  
\*.tfstate  
\*.tfstate.\*  

Игнорировать файл crash.log:  
crash.log  

Игнорировать любые файлы с расширением .tfvars:  
\*.tfvars  

Игнорировать файлы с такими именами:  
override.tf  
override.tf.json  

Игнорировать файлы, которые начинаются на что угодно (кроме слэша) и заканчиваются на _override.tf, _override.tf.json:  
\*_override.tf  
\*_override.tf.json  

Игнорировать файлы с такими именами:  
.terraformrc  
terraform.rc  

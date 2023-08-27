# devops-netology
https://github.com/github/gitignore/blob/main/Terraform.gitignore
Представленном выше файле описаны файлы которые будут изклечюны по представленным признакам:
1. "**/.terraform/*"  игнорируются все файлы в указанной директории;
2. "*.tfstate.*" игнортруются файлы в которыйх прсутсвует в названии данная запись .tfstate.;
3. "crash.log", "override.tf", "override.tf.json", ".terraformrc","terraform.rc" игнорируется представленные файы;
4. "*.tfstate", "crash.*.log","*.tfvars", "*.tfvars.json","*_override.tf" "*_override.tf.json" игнорируются файлы ичеющиеся в себе занчения подстановочного знакп "*".

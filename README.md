# fs-operation-scripts
Operation scripts for AWS

# operation flow
1. Edit the scripts on git. Naming formate: yyyymmdd_templateName_specificOperationName_environment, ex.20170125_ops_create_new_stack_api_dev
2. Upload the scripts to the aws ops server in your account with the same repository name above. Upload scripts via proxy server: scp -o "ProxyCommand=nc -x 127.0.0.1:5555 %h %p" $FILE user.name@{$SERVER}:~/

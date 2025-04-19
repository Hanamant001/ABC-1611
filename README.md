step1)created host machine in azure portal 
store the certificate in ansible vault
ansible-vault encrypt <file name>
step2)wrote ansible playbook that install git and terraform in host machine
step3)i have cloned the git repo which has some terraform scripts
git clone <github url>
step4)execute terraform script and capture output
command:- terraform init,terraform apply
created github repo ABC-1611
step6)pushed playbook configuration to ABC_1611

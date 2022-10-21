# Questions

a method of ranking you define ergonmics

the pratice of identifying the most cost-effetive ways to  work

the science of designing workspace that fit the needs of workers

the study of work practices to identify and eliminate patterns

---------------------------------------------------------------------

what do you think your body's natural, neutral position
should be while you are working ?

back is completely straight and free of curves 

face and feet point in apposite directions

minima, stress is on the muscles and joints

muscles are stained to stretch and grow


---------------------------------------------

instalação tasy 
rede EMR 


[09:45] Menezes, Carmem Elizandra de Jesus
C:\ProgramData\Cisco\Cisco AnyConnect Secure Mobility Client\Profile

# Atualização do sistema

Time de Atualização do sistema
Responsável por atualizar  o sistema e  / manipular direto no banco / 

# Comunicados Importantes 
O time de devops revogou o acesso com o user Tasy ao banco wheb.

Essa manobra foi realizada para garantir a integridade da base wheb e não permtir comandos DDL e DML.

Como alternativa foi criado um usuário readonly.

 
User: wheb_readonly
Password: aloisk
Após o acesso será preciso alterar o schema para Tasy da seguinte forma:
alter session set current_schema=Tasy;
# Plano geral (É um planooo, e é geraaal)
## Estimação da pose
* Calcular e publicar covariância da pose
* Depois do resample, a pose fica aleatória

## Avaliação da estimação
* Fazer um ros2 bag do /cmd_vel de exemplo 
* Fazer algo que lance o tracker e o rosbag automaticamente
* Completar o PathTracker
    * Regista a cada N milissegundos a pose real e a pose estimada + covariância num csv

## Cantos 2D/3D
* Testar o filtro com o detetor de cantos 2D 

## Features 3D
* Decidir o formato das features

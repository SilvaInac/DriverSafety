# DriverSafety
Project for fetin2021 ( Inatel)

####ESTRUTURA DE PASTAS#######

DriverSafety_FW
-build
components
├── emergency_signaling
│   ├── led.c
│   ├── include
│   │   └── led.h
│   └── CMakeList.txt
├── emergency_button
│   ├── button.c
│   ├── include
│   │   └── button.h
│   └── CMakeList.txt
├── airbag_button
│   ├── airbag.c
│   ├── include
│   │   └── airbag.h
│   └── CMakeList.txt
main
├──communication
│   ├── wifi.c
│   ├── satelite.c
│   ├── modem_lte.c
│   ├── include
│   │   └── wifi.h
│   │   └── satelite.h
│   │   └── modem_lte.h
│   └── CMakeList.txt


###### CONFIGURAÇÃO DO AMBIENTE ####
Eclipse:
Eclipse:https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2021-03/R/eclipse-inst-jre-win64.exe
ESP32: https://dl.espressif.com/dl/esp-idf/?idf=4.4 // https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/
https://github.com/espressif/idf-eclipse-plugin/blob/master/README.md

Instalação do GIT:
Git : https://git-scm.com/downloads
Comandos iniciais:
$ git config --global user.name "Fulano de Tal"
$ git config --global user.email fulanodetal@exemplo.br

Explicação inicial:

git = repositório.
github = repositório remoto.
branch = ramo trabalhado.
commit = Ponto de save comentado ( repositório local)
--head =  Commit atual.
merge =  Juntar um branch com outro.
push = subir para o repositório remoto desejado 
pull = atualizar informações do repositório.

Comandos principais:
git clone "link" -> Cria seu repositório local e linka com o repositório remoto ( no caso o Driver_Safety_FW)
git status -> verifica as modificações entre a sua maquina com o ultimo commit
git branch -> verifica qual branch vc ta 
git checkout -> troca o HEAD ( usamos pra trocar de branch)
git add exemplo.c -> inclui o arquivo no proximo commit
git commit -m "comentario das modificações feitas" -> Faz um commit 
git push -> sobe para o repositório atual 
git pull -> atualiza informações do repositório 
git pull nome_da_branch_que_deseja_atualizar -> (geralmente  a main)

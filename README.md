INSTRUÇÕES DE USO: 
1) Instale o Windows com o usuário padrão ("Beep Saude" ou outro) como administrador (único usuário do sistema)
3) Renomeie o computador de acordo com o número de patrimônio - reinicie o computador para que tenha efeito.
4) Se estiver padronizando uma instalação de Windows 10, abra a loja de aplicativos da Microsoft (Microsoft Store) e instale o 'Instalador de Aplicativos'. Esse passo não é necessário no Windows 11.
5) Copie a pasta "padronizacao-windows" para o destino C:\
6) Execute o script setup.cmd
7) Caso ocorra falha na instalação de algum dos aplicativos, um arquivo chamado fix-setup.cmd será criado. Execute após o término da execução do setup.cmd
8) Ao terminar a execução do script, verifique se algum dos comandos retornou com erro e ajuste manualmente o restante que for necessário.

* Dica: para agilizar a instalação do Windows e criação do usuário, utilize o Rufus para a gravação do pendrive e configure as opções desejadas como nome do usuário e configurações de região e idioma.

* CONFIGURAÇÃO DO SCRIPT:
- Arquivos de configurações estão localizados na pasta config

Pasta Files:
- Arquivos nessa pasta com extensão .exe ou .msi serão executados automaticamente, mas possivelmente ainda de forma interativa
- Arquivos de atalho com extensão .url são copiados para a área de trabalho e para o menu iniciar

Etapas do script:
1) Checagem e elevação de privilégio
2) Verificar se o utilitário winget está instalado no sistema
3) Renomear computador (se necessário) e reiniciar OU instalar .exe e .msi localizados na pasta Files
4) 

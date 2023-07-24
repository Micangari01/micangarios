# MicangariOS

## *Sistema Operacional Aberto para Realidade Unificada*

- Realidade Unificada.
- Operacionalidade e UX.
- Commedia Dell'arte e a criação de NPCs interativos.

## SmarArt Server
Carregar imagem .iso em um pendrive bootável com a seguinte estrutura, e pronto para carregar direto da memória RAM em qualquer dispositivo compatível com a versão do Alpine Linux escolhida. Neste pendrive estarão os arquivos necessários apenas para executar script capazes de, de forma automática, criptografar a conexão à internet na camada da Rede Virtual Privada (VPN) e conectar em nuvem, através de servidores PXE onde estão hospedados em um .GIT, os scripts de instalação do MiçangáriOS. Considerando-se o detalhe, que todas as máquinas serão configuradas como Servidores e Clientes, realizando um Clustering através da SoftEther VPN, no intuito de compartilhar processamento e instalar a Blockchain Ixo World, o sistema operacional e as Interfaces de Interação Humana.
Além da interface gráfica, o MiçangáriOS também vem pré-instalado com interface de áudio capaz de detectar microfones e dispositivos de reprodução de áudio, assim como um assistente capaz de traduzir a fala para texto e texto para fala, e a Inteligência Artificial ChatGPT, permitindo uma conversação mais fluída e humana entre o usuário e o sistema operacional. No script de instalação inicial, existe a funcionalidade de preencher campos e selecionar opções, definir e executar comandos e configurações a partir da voz. 
E, através da instalação do OpenGlove, o MiçangáriOS também vem pré-configurado com uma interface de detecção de gestos, no caso de haver hardware periférico compatível, permitindo assim, minimamente a interação por gestos, seja para datilografia como para movimentação e seleção de opções, definir e executar comandos e configurações.
Para além da maior facilidade de interação entre usuário e sistema, a configuração inicial do sistema com essa três diferentes Interfaces de Interação Humana, garantem maior acessibilidade, permitindo o acesso à tecnologia para pessoas com deficiências de fala, audição, mobilidade e visão. E espera-se, que com o aumento da capacidade de aprendizado da I.A, ela se torne cada vez mais preparada para interagir com pessoas com deficiências intelectuais de diversas ordens e especificidades. A opção de tradução simultânea também deve ser abarcada durante a experiência de uso, já que a I.A é capaz de fazer traduções simultâneas, e a entrada de texto por voz pode, se necessário, passar por um filtro tradutor, assim como suas saídas de texto podem passar pelo mesmo filtro com o idioma invertido (espelhado) antes de serem transformadas em saídas de áudio.
De forma prática, primeiro instalamos uma imagem .iso do sistema operacional Alpine Linux escolhido, que neste caso é o Alpine Extended x86, a partir do terminal de comando em um Ubuntu Studio, distribuição Linux escolhida para a primeira versão do MiçangáriOS:
Instalando a imagem .iso no pendrive

Alpine Linux>
	## Após carregar o sistema básico, executar um script .bash contendo:

	instalação do servidor e do cliente SoftEther VPN>
	## Configurar para  
Configurar PXE (Servidor e cliente)>

e um comando carregado na inicialização com o seguinte script:
 






Composição e funcionalidades

O MiçangáriOS
Softwares Essenciais
Backend
Frontend
Suíte Produtiva 
Comunicação  
Centro de Mídia 


Modelo rizomático de distribuição.
Offline First
Scuttlebutt
Protocolo BATMAN
P2P
Torrents
Brave
Protocolo Interplanetary File System (IPFS)

Sistema mínimo e conexão automática com os repositórios descentralizados

VPN e pontos de abertura
Online
Offline

Versionamento
HD 
Flash Disk 
Imagem Virtual
Processadores ARM

Integração com os Smartphones
Kodi

Particionamento do HD SmartArt Server

Colocar a pasta "/" raíz como inicial do IPFS. Partição root.

Usar a pasta /www para instalar os softwares e o sistema,  e manter em nuvem fazendo dela a pasta compartilhada do OwnCloud.

Instalar o Git da Main Version na "/www" para ter sistema de atualização do sistema sincronizado.

Encontrar a pasta para o Flamenco, pensando que será o serviço responsável pela clusterização da Blockchain.

Colocar a pasta /home com os dados do usuário como destino dos arquivos pessoais da OwnCloud

O Kodi e o BitTorrent, dentro da /www e com os arquivos de streaming rodando via torrent, e o kodi lendo localmente.

Na pasta do bittorrent, ficam  os downloads. 
No Kodi direciona a busca nessa pasta.

As pastas estão no GIT...
Usar .gitingnore para pasta de downloads e arquivos temporários
E com sobrescrição automática após exceder o limite

Para fazer o protocolo de transmissão de baixa latência,  p2p, offline first, o Scuttlebut (.ssb) precisa ter acesso a pasta /home e a essa pasta temporária de mídias...

Conectou .ssb via Wifi ou bluetooth, tá fazendo a passagem desses dados de forma offline tbm. 

Tbm precisa carregar as atualizações do GIT... 

Sendo que precisa ser um nível acima,  então acho que o ssb que vai na pasta raíz... o IFPS dentro dele,  depois o git e depois /home e /www

Pasta home e www em partições separadas, e o sistema linux em outra.

A blockchain IXO é instalada na /www e seu armazenamento na /home, que é criptografada. Desse ponto de montagem em diante, é tudo criptografado.

Resumindo

Software na /www e dados na /home

Bancos de dados,  mesmo sistema. Instalar MySql e Postgree.

O Pendrive LiveUSB com armazenamento persistente. 
Sistema mínimo para produção, transmissão e reprodução  de conteúdo, e armazenamento de credenciais.
Trabalho em nuvem

TUTORIAL DE INSTALAÇÃO 

A partir de um pen drive LiveUSB

Máquina virtual

No celular

🎬 Baixador Retro v1.3

Um baixador de vídeos e áudios do YouTube desenvolvido em PowerShell, com interface simples executada diretamente pelo terminal do Windows.

🚀 Funcionalidades

Download de vídeos do YouTube.
Download de áudios.
Download de múltiplos links através de um arquivo lista.txt.
Interface interativa no terminal.
Opção para sair do programa digitando 0.

🛠️ Tecnologias utilizadas

PowerShell
yt-dlp
FFmpeg

📋 Pré-requisitos

Windows 10 ou Windows 11.
PowerShell.
yt-dlp.
FFmpeg.

Importante: os executáveis do yt-dlp e FFmpeg devem ficar dentro da mesma pasta do Baixador Retro. Não é necessário configurar o PATH do Windows, desde que o script esteja configurado para localizar os executáveis nessa pasta.

📥 Instalação

1. Baixar o yt-dlp

Acesse a página oficial: https://github.com/yt-dlp/yt-dlp/releases/latest
Procure o arquivo yt-dlp.exe.
Faça o download.
Coloque o arquivo dentro da pasta do Baixador Retro.

2. Baixar o FFmpeg
Acesse: https://www.gyan.dev/ffmpeg/builds/
Na seção Release builds, baixe ffmpeg-release-essentials.zip.
Extraia o conteúdo do arquivo ZIP.
Entre na pasta extraída e depois na pasta bin.
Copie os arquivos:
ffmpeg.exe
ffprobe.exe

Cole os dois arquivos dentro da pasta do Baixador Retro.
Não é necessário copiar as demais pastas do FFmpeg.

3. Organização da pasta
Ao finalizar, a pasta deverá ficar organizada desta maneira:

Baixador Retro/
│
├── BaixadorRetro.ps1
├── yt-dlp.exe
├── ffmpeg.exe
├── ffprobe.exe
└── lista.txt

O arquivo lista.txt é opcional e utilizado para downloads em lote.

▶️ Como utilizar

Abra a pasta do Baixador Retro.
Execute o arquivo BaixadorRetro.ps1.
Cole o link do vídeo ou áudio do YouTube.
Aguarde o término do download.

📂 Download em lote

O programa permite baixar vários conteúdos de uma só vez.
Crie um arquivo chamado lista.txt na pasta do programa.
Adicione um link do YouTube por linha.
Execute o Baixador Retro.
Digite LISTA quando solicitado.
Aguarde os downloads.

⚠️ Problemas ao executar

Caso o Windows bloqueie a execução do programa ou apresente uma mensagem informando que a execução de scripts está desabilitada, abra o PowerShell e execute:
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Quando solicitado, confirme digitando S e pressionando Enter.
Após isso, tente executar o Baixador Retro novamente.
Observação: esse procedimento só é necessário se o PowerShell impedir a execução do arquivo .ps1.

⚖️ Aviso legal

Este projeto foi desenvolvido para fins educacionais e de uso pessoal.
Respeite os direitos autorais e os termos de serviço das plataformas. Utilize a ferramenta somente para baixar conteúdos que você tenha autorização para obter.

👨‍💻 Autor

Gabriel Previtali

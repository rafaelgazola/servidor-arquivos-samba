



# Projeto de Integração de Redes: Servidor de Arquivos (Debian + Windows)

<p>Este repositório contém a documentação técnica da implementação de um servidor de arquivos Linux (Debian 13) integrado a uma estação de trabalho Windows 11, utilizando o protocolo SMB/Samba.</p>
<div align="center">
  <img width="838" height="648" alt="1" src="https://github.com/user-attachments/assets/8939271c-72c0-41ae-aaad-67d80a27a921" />

<br>

<h2>🛠️ Etapas do Trabalho</h2>

<h3>01 - Teste de Rede (Ping)</h3>
<p><b>Descrição:</b> Prova de que o servidor Debian e o Windows 11 estão se comunicando na rede local.</p>
<div align="center">
  <img width="757" height="339" alt="2" src="https://github.com/user-attachments/assets/c11d174f-e440-4eac-b9ed-c9559a3c2a2a" />

<div align="center">
  <img width="643" height="657" alt="4" src="https://github.com/user-attachments/assets/73cb7dc1-2a50-49f9-8871-b933a5fea4b5" />



</div>

<br><br><br> <h3>02 - Pastas e Permissões</h3>
<p><b>Descrição:</b> Criação das pastas Publico (acesso livre) e Secreto (acesso restrito), com as permissões de segurança aplicadas.</p>
<div align="center">
  <img width="901" height="357" alt="3" src="https://github.com/user-attachments/assets/92050ce5-9922-4eeb-831a-52a42304ae83" />

</div>

<br><br><br>

<h3>03 - Status do Serviço Samba</h3>
<p><b>Descrição:</b> Validação do serviço Samba (smbd) em execução, confirmando que o servidor está pronto para aceitar conexões do Windows.</p>
<div align="center">
  <img width="1002" height="448" alt="5" src="https://github.com/user-attachments/assets/161f36ff-5948-4cd5-bce1-b13f9dcec2d3" />

</div>

<br><br><br>

<h3>04 - Configuração do Samba</h3>
<p><b>Descrição:</b> Configuração do serviço Samba para compartilhar a pasta 'Publico' com a rede Windows, visualizada no editor nano.</p>
<div align="center">
  <img width="901" height="258" alt="6" src="https://github.com/user-attachments/assets/b272c44e-5d7c-444a-841b-f30e92bda9fc" />

</div>

<br><br><br>

<h3>05 - Acesso pelo Windows</h3>
<p><b>Descrição:</b> Estação Windows acessando o servidor Debian com sucesso através do protocolo SMB.</p>
<div align="center">
  <img width="822" height="577" alt="7" src="https://github.com/user-attachments/assets/4882a0ac-01ac-4d72-b41c-bbe3e60932d8" />

</div>

<br><br><br>

<h3>06 - Arquivo de Teste (Homologação)</h3>
<p><b>Descrição:</b> Validação final: arquivo criado no Windows aparecendo dentro do servidor Linux, confirmando que tudo funciona.</p>
<div align="center">
  <img width="873" height="502" alt="8" src="https://github.com/user-attachments/assets/4482b8b0-8363-43a3-a41d-691e3d25c0d0" />
<div align="center">
  <img width="901" height="424" alt="9" src="https://github.com/user-attachments/assets/a0c4c10f-2a75-462f-ab11-92efe2c5db24" />

</div>

<br><br>
<hr>
<p align="center"><i>Projeto de Infraestrutura desenvolvido para fins de aprendizado técnico.</i></p>

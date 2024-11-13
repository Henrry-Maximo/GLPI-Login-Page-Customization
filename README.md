Este repositório contém modificações nas telas de login e nas páginas de erro de login do GLPI, aplicando um novo layout e estilos para uma interface visualmente aprimorada.

## Visão Geral

As alterações foram realizadas para melhorar a experiência do usuário nas seguintes páginas:
- Tela de login
- Páginas de erro de login (como "Usuário ou senha incorretos")

As personalizações incluem ajustes no layout, centralização de elementos, aplicação de gradientes, animações sutis e melhorias na responsividade.

## Pré-requisitos

- **GLPI**: Certifique-se de que o GLPI esteja instalado.
- **Acesso aos Arquivos do GLPI**: É necessário acesso aos arquivos do sistema GLPI para substituir os templates modificados.

## Capturas de Tela

Tela de Login
![glpi-template-login01](https://github.com/user-attachments/assets/3b18fd1b-99b4-4103-bb6d-080e4f91dc79)

Tela de Login com Erro
![glpi-template-login03](https://github.com/user-attachments/assets/536428c4-ae9e-4a78-9dcf-33c9a9bea033)

Tela de Erro de Autenticação
![glpi-template-login02](https://github.com/user-attachments/assets/4f8f3259-e3f4-4923-9998-45603bd14b65)

## Instalação

1. Navegue até a pasta do repositório::
   ```bash
   cd GLPI-Login-Page-Customization

1. Copie e cole a pasta `templates` na raiz de seu GLPI (irá sobrescrever os arquivos):
   ```bash
   sudo cp -R templates /var/www/html/glpi/

- **Nota**: Lembre-se de fazer backup dos templates originais antes de substituí-los.

## Contribuição
- Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests com melhorias.

## Licença
- Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais informações.

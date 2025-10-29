Projeto Full-Stack: Upload de Arquivos + Sistema de Login
Este é um projeto full-stack que combina upload de arquivos com autenticação de usuários. O backend em Node.js/Express gerencia uploads e autenticação, enquanto o frontend oferece uma interface moderna usando Tailwind CSS.

Tecnologias Utilizadas

Backend:
Node.js
Express.js
Multer (upload de arquivos)
JWT (autenticação)
bcryptjs (hash de senhas)
CORS

Frontend:
HTML5
Tailwind CSS
JavaScript (ES6+)
Fetch API
FormData

Funcionalidades Implementadas
Sistema de Autenticação
Registro de Usuários: Endpoint POST /register para criar novas contas
Login: Endpoint POST /login com autenticação JWT
Segurança: Senhas hasheadas com bcrypt
Token JWT: Gerado após login bem-sucedido
Upload de Arquivos
Múltiplos Uploads: Até 10 arquivos por requisição

Validação:
Apenas imagens .jpeg/.png
Máximo 5MB por arquivo
Armazenamento Seguro:
Diretório uploads/ com nomes únicos
Criação automática de diretórios

Frontend
Interface Moderna:
Login/Registro com feedback visual
Upload de arquivos com preview
Comunicação Assíncrona:
Login com JWT
Upload via FormData
Feedback em Tempo Real:
Mensagens de sucesso/erro
Estado dos botões durante operações
Autenticação Persistente:
Token JWT armazenado no localStorage
Verificação de autenticação para uploads
Tratamento de Erros
Mensagens claras para usuários
Códigos HTTP apropriados
Validação tanto no cliente quanto no servidor
Este projeto demonstra uma implementação completa de autenticação e upload de arquivos, com foco em segurança e experiência do usuário.

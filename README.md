📱 IonicNews
Aplicativo de notícias desenvolvido com o framework Ionic e TypeScript. Este projeto serve como exemplo de consumo de APIs de notícias em dispositivos móveis.

🚀 Tecnologias Utilizadas
Ionic Framework: Framework para desenvolvimento de aplicativos móveis híbridos.

TypeScript: Superset do JavaScript que adiciona tipagem estática.

Capacitor: Plataforma nativa para aplicativos móveis.

Angular: Framework para construção de interfaces de usuário.

📦 Pré-requisitos
Antes de rodar o projeto, certifique-se de ter as seguintes ferramentas instaladas:

Node.js (versão recomendada: LTS)

Ionic CLI

Git

📥 Como Rodar o Projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/DantonFSS/IonicNews.git
cd IonicNews
Instale as dependências:

bash
Copiar
Editar
npm install
Adicione a plataforma desejada (Android ou iOS):

bash
Copiar
Editar
ionic capacitor add android
ionic capacitor add ios
Construa o projeto:

bash
Copiar
Editar
ionic build
Sincronize com o Capacitor:

bash
Copiar
Editar
ionic capacitor sync
Abra o projeto na IDE nativa:

Para Android:

bash
Copiar
Editar
ionic capacitor open android
Para iOS:

bash
Copiar
Editar
ionic capacitor open ios
🧪 Testes
Para rodar os testes unitários:

bash
Copiar
Editar
ionic serve
Isso abrirá o aplicativo no navegador para testes interativos.

📝 Contribuindo
Contribuições são bem-vindas! Para contribuir:

Faça um fork do repositório.

Crie uma branch para sua feature (git checkout -b feature/nome-da-feature).

Faça commit das suas alterações (git commit -am 'Adiciona nova feature').

Envie para o seu fork (git push origin feature/nome-da-feature).

Abra um Pull Request.

📄 Licença
Este projeto está licenciado sob a licença CC0-1.0.

# Spotify Clone

Este é um projeto de clone do Spotify desenvolvido com HTML, CSS e JavaScript. O projeto inclui uma API fake implementada com json-server para fornecer dados simulados. Para utilizar o site, certifique-se de que a API esteja rodando.

## Como Rodar a API Fake (json-server)

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em seu sistema.

2. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/spotify-clone.git
   ```

3. Navegue até o diretório do projeto:

   ```bash
   cd spotify-clone
   ```

4. Instale as dependências:

   ```bash
   npm install
   ```

5. Inicie o json-server para simular a API:

   ```bash
   json-server --watch api-artists/artists.json --port 3000
   ```

   A API fake estará disponível em [http://localhost:3000](http://localhost:3000).

## Como Rodar o Site

1. Abra o arquivo `index.html` no seu navegador web.

2. Explore as funcionalidades do site, como reprodução de músicas, navegação de playlists, etc.

Lembre-se de que este projeto é apenas educativo e foi desenvolvido para fins de aprendizado. Os dados fornecidos pela API fake são simulados e não representam dados reais do Spotify.
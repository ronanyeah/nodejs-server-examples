# Node.js Server Glitches

Three [Glitches](https://glitch.com) demonstrating different approaches to writing a Node.js server with the bare minimum of package dependencies. This is intended to demonstrate:
- Static file serving
- Text response
- JSON response
- Cookie login/logout
- Non-200 status code response

Notes:
- All projects on Glitch can be 'remixed', i.e. forked, and live edited.
- Do not use the cookie code in production as they are all unsigned and are not marked as HttpOnly, so can be easily edited by the client.

[Node.js Vanilla](https://nodejs.org/en/)
- [Code](https://glitch.com/edit/#!/fac-nodejs-server)
- [Live Site](https://fac-nodejs-server.glitch.me/)

[Express](http://expressjs.com/)
- [Code](https://glitch.com/edit/#!/fac-express-server)
- [Live Site](https://fac-express-server.glitch.me/)

[Hapi](https://hapijs.com/)
- [Code](https://glitch.com/edit/#!/fac-hapi-server)
- [Live Site](https://fac-hapi-server.glitch.me/)

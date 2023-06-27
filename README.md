# Service bot

The project has two services: Admin service on PHP and Bot service on GO

### The Admin service

It is a web page that receives text input and sends it to Bot service. If it succeeds then the text is stored in a database.

### The Bot service

It is a telegram bot that receives text from Admin service and sends it to users. All the user information is also stored in a database.

Library usage:
//create Bosh configuration
BOSHConfiguration config = new BOSHConfiguration(false, "127.0.0.1", 7070, "/http-bind/", "your.domain.com", "xmpp:127.0.0.1:5222");
//create a connection
BOSHConnection connection = new BOSHConnection(config);
connection.connect();
connection.login(userName, password, resource);

That's all. Have fun!
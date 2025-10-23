Run this -> " java -jar Server.jar " <- command to start the server,
make sure to have Java installed Globally in your Computer,
Your welcome :)
to create new rule -> netsh advfirewall firewall add rule name=[RULE NAME] dir=in action=allow protocol=TCP localport= [PORT NUMBER]
to update the rule -> netsh advfirewall firewall set rule name=[RULE NAME] new enable=[yes/no]

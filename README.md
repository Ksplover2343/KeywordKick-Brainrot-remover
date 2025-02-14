Ever wanted a Velocity plugin where you can kick players if their kick message from the backend server has a specific word? Well now you can do that!

Commands:
/keywordkick - Reloads config.yml

Configuration:
The configuration can be found at plugins/keywordkick/config.yml

Permissions:
Any player with the keywordkick.bypass permission cam bypass being kicked from the proxy completely! Additionally, if a player has the keywordkick.reload permission, they can reload the configuration.

Demo:
[20:39:20 INFO]: [connected player] Longwise (/[REDACTED]:35642) has connected
[20:39:20 INFO] [clientcatcher]: Longwise has joined with client fabric
[20:39:20 INFO]: [server connection] Longwise -> survival has connected
[20:39:27 INFO]: [connected player] Longwise (/[REDACTED]:35642): kicked from server survival: You didn't read all the rules!
[20:39:27 INFO]: [server connection] Longwise -> survival has disconnected
[20:39:27 INFO] [keywordkick]: Player Longwise was kicked from the proxy due to keyword match: rules
[20:39:27 INFO]: [connected player] Longwise (/[REDACTED]:35642) has disconnected: You didn't read all the rules!
[20:40:28 INFO]: [connected player] Longwise (/[REDACTED]:52008) has connected
[20:40:28 INFO] [clientcatcher]: Longwise has joined with client fabric
[20:40:28 INFO]: [server connection] Longwise -> survival has connected
[20:40:58 INFO] [velocity_chat]: [command][survival]<Longwise> /rulebook reload
[20:41:13 INFO] [velocity_chat]: [command][survival]<Longwise> /rulebook update Longwise
[20:41:13 INFO]: [connected player] Longwise (/[REDACTED]:52008): kicked from server survival: Rules updated, please reconnect!
[20:41:13 INFO] [keywordkick]: Player Longwise was kicked from the proxy due to keyword match: rules
[20:41:13 INFO]: [server connection] Longwise -> survival has disconnected
[20:41:13 INFO]: [connected player] Longwise (/[REDACTED]:52008) has disconnected: Rules updated, please reconne

# try identity server

src/IdentityServerがOpenIDConnectのprovider  
src/ApiがリソースAPI  
src/ClientがIdentityServerから認可tokenをもらいに言って  
もらったtokenを用いてリソースApiを叩きに行くクライアント  

# FabAssistant

Pannello di controllo del Fablab che permetta di "spegenere e accendere luci", visualizzare dati di sensori, etc... 
Si tratterà di un'installazione customizzata di Home Assistant con piccoli progetti sviluppati ad hoc per i singoli sensori e dati che si vogliono visualizzare.

I singoli sensori invieranno dati su appositi canali MQTT.
Il progetto sarà modulare e liberamente espandibile.

Deve essere utilizzabile senza troppo sforzo quando si accende la corrente, deve consentire di visualizzare  informazioni come:

1. Temperatura
2. Consumi 
3. Stampanti attive
4. Soci presenti nel Fablab

Nella sua prima versione sarà un semplice pannellino touch con un raspberry pi e home assistant, che dialoga con una serie di sensori funzionanti a batteria.

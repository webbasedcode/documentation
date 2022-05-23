Om met de Docker api veilig te verbinden, is normaal iets van authenticatie nodig, normaal worden hier TLS keys voor gebruikt, alleen deze blijken vrij lastig in te stellen op Docker desktop.
Normaal zou je hiervoor deze guide gebruiken: https://docs.docker.com/engine/security/protect-access/ alleen Docker daemon word dus al automatisch opgestart via Docker desktop en hier de tls keys zetten blijkt heel lastig. 
Hier zijn alle opties die ik heb geprobeerd: 

Tutorial van Microsoft hoe je de Dockerengine op Windows instelt: 
https://docs.microsoft.com/en-us/virtualization/windowscontainers/manage-docker/configure-docker-daemon
Deze lijkt gericht te zijn op een installatie zonder Docker desktop, mogelijk op een server. Op mijn huidige installatie deed het aanpassen van C:\ProgramData\Docker\config\daemon.json niks

Toevoegen van tlskeys in Dockerengine config:
Dit werkt niet/doet niks of crashed de Docker engine tot je het weghaalt, hier staat bovendien ook een issue voor open op Docker desktop's Github issues(https://github.com/docker/for-win/issues/7939)

Aanpassen van daemon.json in programfiles:
Doet ook niks

Los opstarten van Dockerd(Docker daemon) in de installatiemap van Docker desktop:
Dit laat mij connectie maken met de Docker api, waarvan het meeste werkt. Helaas is hetgeen dat bij mij niet werkt dan weer het starten/draaien van containers wat het meest belangrijkst is. Hierbij krijg ik de error terug van Docker “error failure in a Windows system call: The virtual machine or container with the specified identifier is not running.” Tot mijn verbazing heeft iemand anders deze issue niet en draait het bij hem wel prima, maar wat hij heeft gedaan/waarom het werkt weten we niet. Ik heb best wat onderzoek naar dit probleem gedaan op het internet en heb er niet echt iets over kunnen vinden... Bovendien lijkt deze methode mij ook vrij onbetrouwbaar en kan het later tot meer problemen lijden bij het draaien van code. Ook heb ik hierover Docker desktop  support een mailtje gestuurd, maar die weigeren je te helpen of je moet Docker premium hebben. 

Los Docker met WSL 2 voor Windows gebruiken:
Hier ben ik een paar uur mee bezig geweest maar kwam erachter dat dit vrij complex is. Het installeren van een compleet losse Linux os voor development naast mijn Windows os zou veel sneller zijn dan dit afmaken en het goed instellen. Helemaal met erin begrepen dat we later bij het draaien van code in de containers nog meer tijd zullen nodig hebben. 

Uiteindelijke oplossing:
Losse Linux install(Pop os?) naast Windows installeren 

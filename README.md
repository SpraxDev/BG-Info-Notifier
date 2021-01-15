# BG-Info-Notifier [![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/Sprax2013/BG-Info-Notifier.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Sprax2013/BG-Info-Notifier/context:javascript) [![Total alerts](https://img.shields.io/lgtm/alerts/g/Sprax2013/BG-Info-Notifier.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Sprax2013/BG-Info-Notifier/alerts/)

## ToDo
* A page like https://support.google.com/webmasters/answer/182072 but on https://bg-info.sprax2013.de/bot
* Task-Queue die jede Minute geprüft wird und due-dates enthält. Task aus der Vergangenheit werden normal nachträglich ausgeführt. So soll Rate-Limiting und network problems "umgangen" behandelt werden
* Defekte WebHooks müssen als deaktiviert markiert werden (defekt nur wenn Discord selber sagt ist deleted oder so)
* Add Telegram bots
* Add sending mails
* log **all** sent emails locally (for 7 days)
* [X] Setup CI
* Add Admin-ControlPanel
* Create plugin for Typo3 to use instead of Notifier or to contact the Notifier to get data more accurate
* Provide config to configure mails per minute etc.
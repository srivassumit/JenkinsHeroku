# Only listen on http; disable ajp and https
web: java -Djenkins.install.runSetupWizard=false -jar jenkins.war --httpPort=$PORT --ajp13Port=-1 --httpsPort=-1
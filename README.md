# test65
test65
[gerrit]
	basePath = git
	canonicalWebUrl = http://localhost:8086/
	serverId = e84b9c3f-f428-4d6f-8348-25f260e177a3
[container]
	javaOptions = "-Dflogger.backend_factory=com.google.common.flogger.backend.log4j.Log4jBackendFactory#getInstance"
	javaOptions = "-Dflogger.logging_context=com.google.gerrit.server.logging.LoggingContext#getInstance"
	user = root
	javaHome = /usr/lib/jvm/java-11-openjdk-amd64
[index]
	type = lucene
[auth]
	type = DEVELOPMENT_BECOME_ANY_ACCOUNT
[receive]
	enableSignedPush = false
[sendemail]
	smtpServer = localhost
[sshd]
	listenAddress = *:29418
[httpd]
	listenUrl = http://*:8086/
[cache]
	directory = cache

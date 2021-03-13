# distribution
create database with name miniapi
download the jar and change config application properties at below



DB Connection
#please change with ip and user credential from your environment database
jdbc.driver=org.postgresql.Driver
jdbc.url=jdbc:postgresql://localhost:5432/miniapi
jdbc.user=dbroot
jdbc.pass=admin
jdbc.auto=update
jdbc.dialect=org.hibernate.dialect.PostgreSQLDialect


Log ( please uncomment if you want output the log file)
#log config
#log4j2.contextSelector=org.apache.logging.log4j.core.async.AsyncLoggerContextSelector
#logging.level.=INFO
#logging.level.root=INFO
#logging.level.com.ivan=INFO
#logging.level.org.springframework.boot=INFO
#logging.file=logs/app.log
#logging.config=config/configLog.xml
#logging.pattern.file=%d{yyyy-MM-dd HH:mm:ss} [%t] %-5level %logger{36} - %msg%n

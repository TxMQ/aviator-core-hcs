Aviator Consensus Plug-In for Hedera Consensus Services (HCS)
=============================================================

This repository contains a Hedera Consensus Services consensus plug-in implementation for Aviator/Aviator Core Framework.  For more information on Aviator Core Framework and consensus plugins, please visit https://github.com/TxMQ/aviator-core

The best way to utilize this library in your Aviator application is to include it as a maven dependency using the following repository and coordinates in your Maven POM:
```xml
<repositories>
	<repository>
		<id>aviator-core</id>
		<name>TxMQ Aviator Core Public Repository</name>
		<url>https://nexus.txmq.com:8080/repository/aviator-core/</url>
	</repository>		
  </repositories>

  <dependencyManagement>
  	<dependencies>
		<dependency>
			<groupId>com.txmq.aviator</groupId>
			<artifactId>aviator-core-bom</artifactId>
			<version>1.2.0</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
  	</dependencies>
  </dependencyManagement>
  <dependencies>
	<dependency>
		<groupId>com.txmq.aviator</groupId>
		<artifactId>AviatorCoreHCS</artifactId>
	</dependency>
  </dependencies>
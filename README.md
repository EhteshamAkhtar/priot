The Private Internet of Things Manifesto
=====

We believe the Internet of Things is a very promising idea, but we notice it brings very serious privacy concerns. A lot of sensitive data from various sensors around us is going to be gathered and processed in centralized data stores run by big corporations and governments. We think it does not need to be so. We are proposing the Private Internet of Things (PrIoT) paradigm, where private data is stored in decentralized private clouds, fully controlled by users, interoperable with other private clouds and in federation with them, using open standards.

![Centralized vs decentralized](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/Decentralization_diagram.svg/300px-Decentralization_diagram.svg.png)

Similar to [federated social networks](https://www.eff.org/deeplinks/2011/03/introduction-distributed-social-network), the PrIoT model gives control over sensitive data back to users. They keep their data and decide which part of them will be exchanged using one of the emerging open standard protocols:
- [Advanced Message Queuing Protocol (AMQP)](http://amqp.org/) by OASIS,
- [Constrained Application Protocol (CoAP)](http://coap.technology/) by IETF,
- [Message Queue Telemetry Transport (MQTT)](http://mqtt.org/) by OASIS,
- [eXtensible Messaging and Presence Protocol (XMPP)](http://xmpp.org/) by XSF,
- [ZeroMQ Message Transport Protocol (ZMTP)](http://zmtp.org/) by iMatix.

  This could be achieved by deploying a local PrIoT cloud based on open source projects like:
 - [AllJoyn](http://www.alljoyn.org/) by AllSeen Alliance,
 - [Contiki](http://www.contiki-os.org/) (based on CoAP) by Adam Dunkels et al,
 - [Edgenet](http://theedg.es/) by Pieter Hintjens,
 - [Freedomotic](http://freedomotic.com/) (based on AMQP),
 - [IoTivity](https://www.iotivity.org/) (based on CoAP) by OIC,
 - [Kaa](http://www.kaaproject.org/overview/) (based on MQTT/HTTP) by CyberVision,
 - [Open IoT Stack for Java](http://iot.eclipse.org/java/) (based on MQTT) by Eclipse Foundation,
 - [OpenIoT](http://www.openiot.eu/) by DERI,
 - [Nimbits](http://www.nimbits.com/) (based on HTTP/XMPP),
 - [Node-RED](http://nodered.org/) (based on MQTT) by IBM,
 - [Phant](http://phant.io/) (based on HTTP) by SparkFun,
 - [RabbitMQ](https://www.rabbitmq.com/) (based on AMQP) by Pivotal,
 - [RIOT OS](http://www.riot-os.org/) (based on CoAP),
 - [SiteWhere](http://www.sitewhere.org/) (based on MQTT/HTTP),
 - [Spark](http://spark.github.io/) (based on CoAP) by Spark Labs,
 - [ThingSpeak](https://thingspeak.com/) (based on HTTP),
 - [WSO2](http://wso2.com/) (based on MQTT),
 - [Zetta](http://www.zettajs.org/) (based on WebSocket).

If you agree with us, please star and share this project. Contributions are welcome.

&copy; 2014 Jerzy Głowacki et al. Licensed under CC BY-SA 4.0.

[Image](http://commons.wikimedia.org/wiki/File:Decentralization.jpg#mediaviewer/File:Decentralization.jpg) by Adam Aladdin, licensed by CC BY-SA 3.0. 

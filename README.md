# Project Title
Loyalty-CargaMasivaUsuarios

## Description 
this project allows a massive load of users

### Prerequisites 

```
Java 7 or higher
Maven
```
### Installing 

```
step 1.- copy project in a local address of your computer
step 2.- open folder Loyalty-CargaMasivaUsuarios in the command console
step 3.- execute the command mvn camel: run
```

## Running the tests

```
Step 1.- Create csv file with the following structure:
email,	firstname,	lastname,	gender,	socialLogin,	socialNetwork,	socialId,	password,	source
step 2.- place file in the local path C: \ input \ file
if the procedure was correct the file will be moved to the local address C: \ input \ file \ done
```
## Known bugs
```
*Existing customer
  example 
  com.sun.xml.internal.ws.fault.ServerSOAPFaultException: Client received SOAP Fault from server: Customer already exists Please see the  server log to find more detail regarding exact cause of the failure.
	at com.sun.xml.internal.ws.fault.SOAP11Fault.getProtocolException(SOAP11Fault.java:178)
	at com.sun.xml.internal.ws.fault.SOAPFaultBuilder.createException(SOAPFaultBuilder.java:116)
	at com.sun.xml.internal.ws.client.sei.StubHandler.readResponse(StubHandler.java:238)
	at com.sun.xml.internal.ws.db.DatabindingImpl.deserializeResponse(DatabindingImpl.java:189)
	at com.sun.xml.internal.ws.db.DatabindingImpl.deserializeResponse(DatabindingImpl.java:276)
	at com.sun.xml.internal.ws.client.sei.SyncMethodHandler.invoke(SyncMethodHandler.java:104)
	at com.sun.xml.internal.ws.client.sei.SyncMethodHandler.invoke(SyncMethodHandler.java:77)
	at com.sun.xml.internal.ws.client.sei.SEIStub.invoke(SEIStub.java:147)
  
```

## Deployment
```
execute mvn clean install command after executing command mvn camel: run
```
## Built With

* [Maven](https://maven.apache.org/) - Dependency Management


## Version
```
1.0.0-SNAPSHOT
```
## Authors
```
Name: Alfredo Hernandez
Email: ahernandez@nyva.mx
Name: Obed Sanchez@nyva.mx
Email: osanchez@nyva.mx
```
* [Nyva Consulting SA. de CV.](http://www.nyva.mx/)



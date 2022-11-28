# Beach and Weather
## *A Mobile Crowdsensing Platform to Report Beach Conditions*

B&W a novel participatory MCS tool where contributors are able to report the current state of the beach where they are currently located in.  At the same time, other users can get access to the current state of multiple beaches based on the collaborative data send by their counterparts.

## Components
- A client module, running as a mobile application that allows users to submitt the current state of a beach and
- A back-end server that collects and aggregates all the reports from the contributors. It also deals with the requests from the consumers who want to know the current state of a particular beach.

The orchestration between the client and the server is done by means of a web service based on the Simple Object Access Protocol (SOAP). The source code of the mobile application is in the [src/client](https://github.com/jpenaab/tp/tree/main/src/client)folder and the code of the server in within the [src/server](https://github.com/jpenaab/tp/tree/main/src/server) folder.

## Libraries and Dependencies
- Android 6.0 (Marshmallow, API 23) 
- Picasso 2.7 
- JCoord 1.0 
- KSoap2
- PostgreSQL 
- Oracle Glassfish

## Developer tools 
The tools that we have used to develop B&W have been,
- Android Studio 3.4
- Apache Netbeans 8.0.2

## Scientific Paper
A scientific paper describing in detail this platform has been submitted to the [SoftwareX](https://www.sciencedirect.com/journal/softwarex) journal.

## License
GNU General Public License v3.0

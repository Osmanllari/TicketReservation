# Tickets Reservation

# Guide to Running
1) Setup the workspace in eclipse
2) Run the BulletinBoardServer.java in eclipse (still required for the JDBC driver to work)
3) If it is not setup by default, right-click on the project: Properties > Java Build Path > Add External JARs > select "lib/sqlite-jdbc-3.40.0.0.jar" > Apply & Close
4)  Running BulletinBoardServer.java again should work now
5) Open a terminal and navigate the "../src" then run BulletinBoardClient.java
6) They should now be properly setup

This practical group-work assessment is about Network Programming using the sockets interface.
Explanation: The client/server application is a bulletin board system for the online reservation of tickets for a show. The server-side 
the bulletin board, and is responsible for handing a database with ticket reservations. The client side is used by agents to reserve tickets for their customers.

Includes: 
  * Error Checking
  * Protocol Design (TCP)
  * Implementation Language and Platform (DBMS - SQLite)
  * Source Code Documentation (Comments)

# spring-jdbc-client

modeled from:
https://spring.io/guides/gs/relational-data-access/

This JDBC Spring app
<ul>
  <li>loads JDBC DLL (configurable, I'm sure)
  <li>creates a hs database (in memory)
  <li>selects specific records from the db and prints to console.
  <li>closes connection, cleans up and exits
</ul>

## to run:
<ul>
  <li>mvn package (to create the spring-jdbc-client.jar)
  <li>java -jar target/spring-jdbc-client.jar
  <li>Slightly buried in the console, you'll see
    <ul>
      <li>Customer[id=3, firstName='Josh', lastName='Bloch']
      <li>Customer[id=4, firstName='Josh', lastName='Long']
    </ul>
</ul>

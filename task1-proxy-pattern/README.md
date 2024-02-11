# task1 Proxy design pattern

### Written code overview

**ConnectionPool** (com.mjc.stage2.impl) pool which contains all created real connections.
**RealConnection** (com.mjc.stage2.impl) connection which implements interface Connection (com.mjc.stage2) and used in
the connection pool.

## Task - Implement proxy pattern for connection.

1. Implement interface Connection  in the ProxyConnection class (com.mjc.stage2.impl)
2. Close method should return connection to the ConnectionPool 
3. Write reallyClose() method in the ProxyConnection class which close real connection.



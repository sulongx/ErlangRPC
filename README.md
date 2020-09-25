# ErlangRPC
Erlang RPC application based on TCP/IP protocol.


# Start application

## 1.build this code

**command:** `erlc -0 ./bin ./src/*.erl`

## 2.run shell

**command:** `erl -pa ./ebin`

## 3.run application

**command:** `application:start(tcp_rpc).`

# Test by Telnet

```
telnet localhost 1055
Trying 127.0.0.1...
Connected to localhost.localdomain.
Escape character is '^]'.

io:format("connection success!~n").
ok
init:stop().
ok
Connection closed by foreign host.
```

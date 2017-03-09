# TcpServer

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `tcp_server` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:tcp_server, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/tcp_server](https://hexdocs.pm/tcp_server).

```
iex -S mix

TcpServer.Server.listen(8082)
```

At same time
```
telnet localhost 8082
Elixir Sips!
```

This blocks the server for any connected client until they close the connection
[Better Solution](https://parroty00.wordpress.com/2013/07/28/elixir-tcp-server-example/)

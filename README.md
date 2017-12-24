# Metex

Simple weather application from the The Little Elixir OTP Guidebook.

Part of my Elixir study.

Example usage:

```
iex -S mix
iex(5)> cities = ["Chicago", "Toronto", "Vancouver"]
["Chicago", "Toronto", "Vancouver"]
iex(6)> Metex.temperatures_of(cities)
:ok
Chicago: -6.5°C, Toronto: -5.0°C, Vancouver: 0.1°C
iex(7)> flush
:ok
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `metex` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:metex, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/metex](https://hexdocs.pm/metex).

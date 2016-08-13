# Barlix

![BARLIX](https://raw.githubusercontent.com/ananthakumaran/barlix/master/media/logo.png "BARLIX")

[![Build Status](https://secure.travis-ci.org/ananthakumaran/barlix.png)](http://travis-ci.org/ananthakumaran/barlix)

Barcode generator for Elixir

## Installation

```elixir
def deps do
  [{:barlix, "~> 0.1.0"}]
end

def application do
  [applications: [:barlix]]
end
```

## Example

```elixir
Barlix.Code39.encode!("BARLIX")
|> Barlix.PNG.print(file: "/tmp/barcode.png")
```

see [documenation](https://hexdocs.pm/barlix) for more information.

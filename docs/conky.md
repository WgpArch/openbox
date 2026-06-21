# Conky Setup

This configuration features a beautiful **dual conky setup** that displays system statistics on both the left and right sides of your screen.

## Left Panel: Auzia-Conky

The left panel uses the stunning **auzia-conky** theme, which is a Lua-based conky configuration featuring dynamic gauges and a modern aesthetic.

### Important Requirement

To get auzia-conky working properly, you **must** have `conky-lua-nv` installed from the AUR. The standard `conky` package from the official repositories does not support the required Lua NV bindings.

Install it with:

```bash
trizen -S conky-lua-nv

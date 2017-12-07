# Name

lua-resty-snowflack - lua Twitter-Snowflake implement for the ngx_lua
# Status

This library is considered production ready.
# Description

This Lua library is a Twitter-Snowflake implement for the ngx_lua nginx module:
# Synopsis

```
local snowflake = require "resty.snowflake"

local machine_id = 100

local id_str, timestamp, mid, inc = snowflake.generate_id(machine_id)
local timestamp, mid, inc snowflake.decode_id(id_str)
```
# Requires

1. Lua Bit Operations Module: [http://bitop.luajit.org/](http://bitop.luajit.org/ "http://bitop.luajit.org/")
# TODO

# See Also


# BadBlinka
PoC for HID attacks in CircuitPython. Because.

## Files

* **code_template.py:** a temnplate, used to build code.py which is the actual code running on your CircuitPython board
* **main.go:** compiles Duckyscript to CircuitPython build it with `go get -u ./...` and `go build` (maybe I'll add some binaries, but you should install go anyway)

 ## Usage

`BadCircuitPython -p "DUCKYSCRIPT-FILES"  [-t TEMPLATE]`

The duckyScripts get embedded as functions `payload_0()` to `payload_n()`
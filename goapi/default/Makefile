wrap.go : ../goapi_wrap.tcl Makefile
	tclsh ../goapi_wrap.tcl < "`go env GOROOT`/api/go1.txt" > wrap.go reflect bytes strings strconv fmt bufio os net/http regexp  encoding/base64 io/ioutil math math/big time
	go build
clean:
	-rm wrap.go

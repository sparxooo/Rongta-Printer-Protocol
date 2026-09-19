# Google Chrome extension
The google chrome extension contains, amongst some minified JS code, a compiled wasm binary.

## Output of strings
Running strings on this wasm binary reveals some interesting tidbits (including function exports from the wasm, but this stood out):

{"superCode":%d,"subCode":%d,"jsonData":%s,"isError":%s}
super: 0x%02X sub: 0x%02X

Searching the other js files for manufacturers names also reveals:

static get PrinterType(){return{AILI_XIONG:26,DELI:27,RongTa:28,XIAOMI:163,RUIDA:30,SXTYWL:31}}
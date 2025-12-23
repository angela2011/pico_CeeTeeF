# Brief Description:
- Open the pcap file on wireshark an you could follow tcp streams of each packet manually but it is very tedious.
- Some part of the message seems to be in base64 encoded format but upon using a b64 decoder we don't obtain anything useful.
- By using strings and then grepping for pico it gives us the flag:picoCTF{P64P_4N4L7S1S_SU55355FUL_0f2d7dc9}
- exact command: strings trace.pcap | grep pico

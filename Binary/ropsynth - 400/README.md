# ropsynth

**Points : 400**
**Solved : 34**

## Description

	ropsynth.pwn.seccon.jp:10000
Read "secret" and output the content such as the following code.

	==
	fd = open("secret", 0, 0);
	len = read(fd, buf, 256);
	write(1, buf, len);
	==
[dist.tgz](dist.tgz)
## Write-up


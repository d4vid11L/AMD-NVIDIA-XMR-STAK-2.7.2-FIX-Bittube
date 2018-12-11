# AMD-NVIDIA-XMR-STAK-2.7.2-FIX-Bittube

This release fixes the bittube2 POW function which was broken in 2.7.1

Config files from 2.6.X+ are compatible and 2.5.X or older are NOT compatible to this release.
If you remove the old amd.txt file you will get a new version with new tuning parameter.

Changelog:
remove APP SDK with OCL SDK light #2129
OpenCl: fix bittube2 #2128

Necessary prerequisites for Windows
If the application does not start properly, please make sure that Visual Studio libraries are installed.
You can download them from https://go.microsoft.com/fwlink/?LinkId=746572

Anti-virus detection
All miners are detected as viruses. Please add the binary as an exception.







Pre-compiled Binaries and Checksums
Please use the Developer PGP Key's to verify the integrity of the precompiled binaries.


The pre-compiled Windows binaries uses OpenSource Software hwloc, OpenSSl and microhttpd: https://github.com/fireice-uk/xmr-stak-dep/releases/tag/v3
The pre-compiled Linux binaries uses OpenSource Software


hwloc https://github.com/open-mpi/hwloc/archive/hwloc-2.0.2.tar.gz
OpenSSL https://www.openssl.org/source/openssl-1.1.1.tar.gz
microhttpd https://ftp.gnu.org/gnu/libmicrohttpd/libmicrohttpd-0.9.60.tar.gz
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256


XMR-Stak 2.7.2 Build Checksums


compiled by: psychocrypt


# released compressed binaries


$ sha1sum 
a54f81d533853e14d7e4f5625e4248c555d94706  xmr-stak-linux-2.7.2-cpu_cuda-nvidia.tar.xz
0d174e90a3f9dda32b00112d1411cdf70614a84c  xmr-stak-linux-2.7.2-cpu_opencl-amd.tar.xz
fb372f462010aac112002321ddb71e4a9ef85f8f  xmr-stak-linux-2.7.2-cpu.tar.xz
4082669415d0ddafde4c35c1502643157c6899fb  xmr-stak-win64-2.7.2.7z
8eac3bb593730b4b3fd48521d0912526f762cc6a  xmr-stak-win64-2.7.2.zip


$ sha3sum 
edf56ccb6afefd9079f228b5e23454671c5ec1a592d4120dfc4afa09  xmr-stak-linux-2.7.2-cpu_cuda-nvidia.tar.xz
188c024c29435994a470a4f8b9b42638c75bcd9ef2f15775e2da321f  xmr-stak-linux-2.7.2-cpu_opencl-amd.tar.xz
4d2344d8aeb208573237eb1e2ac3dae9d903c8e98a648120f400f577  xmr-stak-linux-2.7.2-cpu.tar.xz
1c2ef7f7a2219322c344747430a53bfad310b609c30f7fc4c7eb835c  xmr-stak-win64-2.7.2.7z
e19322fac66b6ee5e297e77fc75fa4289289ee288fb27fc45c2cce25  xmr-stak-win64-2.7.2.zip


$ date
Mon Dec 10 21:10:19 CET 2018
-----BEGIN PGP SIGNATURE-----
Version: GnuPG v2


iQEcBAEBCAAGBQJcDshkAAoJEAUWOMCIZelDDisH/3XcIpu7XT3s/H1mibXaYdG8
qi9m2cTfe2obpQQwuuuwLw/AwlEaNvNSFJRGOECAtAZ6T1hE5LO6Bc1OZonqA13R
btoIZ6WAmRvtkd/mTRJq4O59F7NU0innMsOVGzYx4lifEYc6IJrercsgazEEQnko
MDOA3eJt99QFwUqvZpuHml29J7R6c5zKNCO82uASstxusqiC2RUcQSi4w1gk47q9
dLwne8g31JINuWDbxZom73GL82aj0xGtWGpME7t6HKTx0i2YuwyBds+impbEhc2U
2Um8g0ZUU9c2AVhUSQCZy9bQ9yQ2Yjj5JIjkQSc4h26O8767xWa9JbUliLRxYjQ=
=0c+l

-----END PGP SIGNATURE-----

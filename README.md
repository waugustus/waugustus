<h1><p align="center">About</p></h1>

### About me
- Software security enthusiast, including [vulnerability discovery](https://github.com/waugustus/poc) and [cause analysis](https://github.com/waugustus/crash_analysis)
- Ph.D. student at the Institute of Information Engineering, Chinese Academy of Sciences
- Graduated from Huazhong University of Science and Technology

### Vulnerabilities

| CVE | Package | Version | Program | Summary | Analysis |
| --- | --- | --- | --- | --- | --- |
| [CVE-2018-20189](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-20189) | graphicsmagick | 89e43 | gm | Assertion Failure in WriteOnePNGImage |  |
| [CVE-2019-7581](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-7581) | libming | 50098 | listswf | Memory Allocation Failure in parseSWF_ACTIONRECORD |  |
| [CVE-2019-7582](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-7582) | libming | 50098 | listswf | Memory Allocation Failure in readBytes|  |
| [CVE-2019-7663](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-7663) | libtiff | 56a19 | tiffcp | SEGV in cpSeparateBufToContigBuf |  |
| [CVE-2022-22844](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-22844) | libtiff | cd57b | tiffset | Global Buffer Overflow in \_TIFFmemcpy | [Link](https://github.com/waugustus/crash_analysis/blob/main/analysis/CVE-2022-22844.md) |
|[CVE-2022-0865](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0865)|libtiff|573e0|tiffcp|Assertion Failure in TIFFReadAndRealloc||
|[CVE-2022-0907](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0907)|libtiff|5e180|tiffcrop|SEGV in _TIFFmemset||
|[CVE-2022-0909](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0909)|libtiff|5e180|tiffcrop|FPE in computeOutputPixelOffsets||
|[CVE-2022-0924](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0924)|libtiff|fb61a|tiffcp|Heap Buffer Overflow in cpContigBufToSeparateBuf||
|[CVE-2022-1056](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1056)|libtiff|5e180|tiffcrop|Heap Buffer Overflow in _TIFFmemcpy||
|[CVE-2022-1622](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1622)|libtiff|b51bb|tiffcp|SEGV in LZWDecode||
|[CVE-2022-1623](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1623)|libtiff|b51bb|tiffcp|SEGV in LZWDecode||
|[CVE-2022-2056](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2056)|libtiff|9752d|tiffcrop|FPE in computeOutputPixelOffsets||
|[CVE-2022-2057](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2057)|libtiff|19db1|tiffcrop|FPE in computeOutputPixelOffsets||
|[CVE-2022-2058](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2058)|libtiff|19db1|tiffcrop|FPE in computeOutputPixelOffsets||
|[CVE-2022-2953](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2953)|libtiff|b51bb|tiffcrop|Heap Buffer Overflow in extractImageSection||
|[CVE-2022-3597](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3597)|libtiff|b51bb|tiffcrop|Heap Buffer Overflow in _TIFFmemcpy||
|[CVE-2022-3598](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3598)|libtiff|8e9ce|tiffcrop|Heap Buffer Overflow in extractContigSamplesShifted24bits||
|[CVE-2022-3599](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3599)|libtiff|5e180|tiffcrop|Heap Buffer Overflow in writeSingleSection||
|[CVE-2022-3626](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3626)|libtiff|19db1|tiffcrop|Heap Buffer Overflow in _TIFFmemset||
|[CVE-2022-3627](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3627)|libtiff|b51bb|tiffcrop|Heap Buffer Overflow in _TIFFmemcpy||
|[CVE-2022-4450](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-4450)|openssl|a63fa|openssl-asn1parse|Double Free in CRYPTO_free||
|[CVE-2022-4645](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-4645)|libtiff|fb61a|tiffcp|Heap buffer overflow in tiffcp||
|[CVE-2022-29977](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-29977)|libsixel|6a5be|img2sixel|Assertion failure in stbi__jpeg_huff_decode||
|[CVE-2022-29978](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-29978)|libsixel|6a5be|img2sixel|FPE in sixel_encoder_do_resize||
|[CVE-2023-0795](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0795)|libtiff|1bdbd|tiffcrop|SEGV in extractContigSamplesShifted16bits||
|[CVE-2023-0796](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0796)|libtiff|1bdbd|tiffcrop|SEGV in extractContigSamplesShifted24bits||
|[CVE-2023-0797](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0797)|libtiff|1bdbd|tiffcrop|SEGV in _TIFFmemcpy||
|[CVE-2023-0798](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0798)|libtiff|1bdbd|tiffcrop|SEGV in extractContigSamplesShifted8bits||
|[CVE-2023-0799](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0799)|libtiff|1bdbd|tiffcrop|Heap Use After Free in extractContigSamplesShifted32bits||
|[CVE-2023-0800](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0800)|libtiff|1bdbd|tiffcrop|Heap Buffer Overflow in extractContigSamplesShifted16bits||
|[CVE-2023-0801](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0801)|libtiff|1bdbd|tiffcrop|Heap Buffer Overflow in _TIFFmemcpy||
|[CVE-2023-0802](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0802)|libtiff|1bdbd|tiffcrop|Heap Buffer Overflow in extractContigSamplesShifted32bits||
|[CVE-2023-0803](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0803)|libtiff|1bdbd|tiffcrop|Heap Buffer Overflow in extractContigSamplesShifted16bits||
|[CVE-2023-0804](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-0804)|libtiff|1bdbd|tiffcrop|Heap Buffer Overflow in extractContigSamplesShifted24bits||

[![4ugstus's GitHub stats](https://github-readme-stats.vercel.app/api?username=waugustus&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

<!--
**waugustus/waugustus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

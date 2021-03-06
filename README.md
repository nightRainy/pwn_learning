# pwn_learning&&FUZZ

>This project is used to collect learning materials!And I will synchronous update it on my blogs!

***

## tools be used in the pwn
 
*  [IDA pro反编译神器 推荐书籍：《IDA PRO 权威指南》](https://www.hex-rays.com/products/ida/) 
* [gdb : Linux/Unix下的动态调试利器 
](https://www.gnu.org/software/gdb/)	
	 
	推荐插件：
		1. [pead](https://github.com/longld/peda) ;   2. [gef](https://github.com/hugsy/gef)
* [pwntools:一个强大的pwn辅助库](http://docs.pwntools.com/en/stable/)
* [ibc_database:收录了很多的libc库](https://github.com/niklasb/libc-database)
* [one_gadget:用以寻找调用系统函数的gadget并输出满足条件](htts://github.com/david942j/one_gadget)
* [libcSearch : 用以搜索libc的版本](https://github.com/lieanu/LibcSearcher)
* [ROPgadget : 用于在程序中寻找我们所需要的东西](https://github.com/JonathanSalwan/ROPgadget)
* [angr:具有动静态分析的二进制分析工具](https://github.com/angr/angr.git)
* [ollyDbg : 逆向破解利器](http://www.ollydbg.de/version2.html)
* [radare2: 强大的逆向工程和二进制分析框架](https://github.com/radare/radare2.git)

***
## NEWS
*  [Thehackernews]( https://thehackernews.com/)
* [Freebuf](https://www.freebuf.com/)
* [安全客](https://www.anquanke.com/)
* [指尖安全](https://www.secfree.com/)
***

## BBS

* [Offensive Community](http://offensivecommunity.net/)
* [Cracking](https://cracking.org/forums/cracking-tools.16/)

***

## Online course

* [二进制入门](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)
* [ 逆向工程](https://www.youtube.com/results?sp=EgIQAw%253D%253D&search_query=reverse+engineering)
* [Modern Binary Exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/)
* [inux (x86) Exploit Development Series](https://sploitfun.wordpress.com/2015/06/26/linux-x86-exploit-development-tutorial-series/)
* [liveoverflow: Binary Hacking Course](http://liveoverflow.com/binary_hacking/index.html)
* [Lots of Tutorials](https://www.fuzzysecurity.com/tutorials.html)
***

## Learning materials
* [ctf-wiki](https://ctf-wiki.github.io)
* [堆溢出攻击原理](https://blog.csdn.net/aemperor/article/details/47310593)
* [溢出之retlibc2详解](https://www.freebuf.com/articles/rookie/182894.html)
* [ctf all in one](https://github.com/firmianay/CTF-All-In-One)
* [pwn & exploit](https://github.com/jmpews/pwn2exploit)
****

## stackoverflow
* [手把手教你栈溢出从入门到放弃（上）](http://bobao.360.cn/learning/detail/3717.html)
* [手把手教你栈溢出从入门到放弃（下）](http://bobao.360.cn/learning/detail/3718.html)
* [Swing: 基础栈溢出复习 之基础](http://bestwing.me/2017/03/18/stack-overflow-one/)
* [pwn入门之栈溢出练习](https://bbs.ichunqiu.com/thread-45542-1-1.html)
* [Hcamael: PWN学习总结之基础栈溢出](http://0x48.pw/2016/11/03/0x26/)
* [Hcamael: PWN学习总结之基础栈溢出2](http://0x48.pw/2016/11/21/0x27/)

	### ROP
* .[一步一步学ROP之linux_x86篇](http://drops.xmd5.com/static/drops/tips-6597.html)
*  [一步一步学ROP之gadgets和2free篇](http://cb.drops.wiki/drops/binary-10638.html)
* .[一步一步学ROP之Android ARM 32位篇](http://cb.drops.wiki/drops/papers-11390.html)
* .[Sigreturn Oriented Programming (SROP) Attack攻击原理](http://www.freebuf.com/articles/network/87447.html)
* .[Swing: 基础栈溢出复习 三 之 SROP](http://bestwing.me/2017/03/20/stack-overflow-three-SROP/)
* [如何在32位系统中使用ROP+Return-to-dl来绕过ASLR+DEP](http://www.freebuf.com/articles/system/149214.html)
* [通过ELF动态装载构造ROP链 （ Return-to-dl-resolve）](http://www.evil0x.com/posts/19226.html)
***

## 堆漏洞
* [Heap Exploitation](https://heap-exploitation.dhavalkapil.com/introduction.html)
* [how2heap](https://github.com/shellphish/)
* [Heap overflow using unlink](https://sploitfun.wordpress.com/2015/02/26/heap-overflow-using-unlink/?spm=a313e.7916648.0.0.x4nzYZ)
* [堆溢出的unlink利用方法](https://www.tuicool.com/articles/E3Ezu2u)
* [Dance In Heap](http://www.freebuf.com/articles/system/151372.html)
* [堆利用简介](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/glibc-heap/introduction/)
***

## 格式化字符串漏洞
* [原理简介](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/fmtstr/fmtstr_intro/)
* [二进制漏洞之——邪恶的printf](http://cb.drops.wiki/drops/binary-6259.html)
* [格式化字符串漏洞利用小结](http://bobao.360.cn/learning/detail/3654.html)
* [Linux下的格式化字符串漏洞利用姿势](http://www.cnblogs.com/Ox9A82/p/5429099.html)
***

## IO_FILE利用
* [FILE 文件结构介绍](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/io_file/introduction/)
* [伪造 vtable 劫持程序流程](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/io_file/fake-vtable-exploit/)
* [FSOP](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/io_file/fsop/)
* [新版本 libc 下 IO_FILE 的利用](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/io_file/exploit-in-libc2.24/)
***

## 条件竞争 
*[条件竞争介绍](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/race-condition/introduction/)
***

## 整数溢出 
* [整数溢出原理介绍](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/integeroverflow/intof/)
***

## 沙箱逃逸 
* [Python 沙箱逃逸](https://ctf-wiki.github.io/ctf-wiki/pwn/linux/sandbox/python-sandbox-escape/)
***

## TIPS
* [借助DynELF实现无libc的漏洞利用小结](http://bobao.360.cn/learning/detail/3298.html?utm_source=tuicool&utm_medium=referral)
* [Finding Function's Load Address](http://uaf.io/exploitation/misc/2016/04/02/Finding-Functions.html)
* [pwn tips](http://skysider.com/?p=223)
* [CTF-pwn-tips](https://github.com/Naetw/CTF-pwn-tips)
* [pwn 学习总结](http://www.angelwhu.com/blog/?p=460)
* [CTF中做Linux下漏洞利用的一些心得](http://www.cnblogs.com/Ox9A82/p/5559167.html)
* [linux常见漏洞利用技术实践](http://drops.xmd5.com/static/drops/binary-6521.html)

***

# FUZZ

## 文章

* [从零开始学Fuzzing系列：浏览器挖掘框架Morph诞生记](https://www.freebuf.com/sectool/89001.html)
* [浅析Peach Fuzz](http://blog.nsfocus.net/peach-fuzz/)
* [From fuzzing to 0-day](https://blog.techorganic.com/2014/05/14/from-fuzzing-to-0-day/)
* [Fuzzing: Brute Force Vulnerability Discovery](http://www.fuzzing.org/)
* [Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/)
* [有效的文件格式Fuzzing](http://j00ru.vexillium.org/slides/2016/blackhat.pdf)
* [过去一年的Windows内核字体fuzzing第一部分成果](https://googleprojectzero.blogspot.in/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html)
* [过去一年的Windows内核字体fuzzing第二部分技术](https://googleprojectzero.blogspot.in/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html)
* [fuzzing项目中有趣的bug和资源](https://blog.fuzzing-project.org/)
* [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/)
* [用AFL和libFuzzer轻松介绍C++代码fuzzing ](http://jefftrull.github.io/c++/clang/llvm/fuzzing/sanitizer/2015/11/27/fuzzing-with-sanitizers.html)
* [15分钟fuzzing介绍 ](https://www.mwrinfosecurity.com/our-thinking/15-minute-guide-to-fuzzing/)
 
 ***
## 书籍
* [《模糊测试-强制性安全漏洞发掘》](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119)
***
## 课程
* [Fuzzing 101 ](https://vimeo.com/5236104)
* [YouTube](https://www.youtube.com/)
***
## 工具
* [AFL Fuzzer](http://lcamtuf.coredump.cx/afl/)
* [libFuzzer Fuzzer](https://llvm.org/docs/LibFuzzer.html)
* [Spike Fuzzer](https://resources.infosecinstitute.com/intro-to-fuzzing/#gref)
* [EasyFuzzer](http://www.asm64.com/)

***
















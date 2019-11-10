---
layout: default
---

# RISC-V资源列表

## 处理器实现

+ BOOM: Christopher Celio的RV64乱序处理器实现。Chisel, BSD Licensed。
  [[GitHub](https://github.com/ucb-bar/riscv-boom)]
  [[Doc](https://ccelio.github.io/riscv-boom-doc/)]

+ BottleRocket: RV32IMC微处理器。Chisel， Apache Licensed。
  [[GitHub](https://github.com/google/bottlerocket)]

+ bwitherspoon: RV32微处理器。SystemVerilog, ISC Licensed。
  [[GitHub](https://github.com/bwitherspoon/core)]

+ Clarvi: 剑桥大学教学用RISC-V处理器。SystemVerilog, BSD Licensed。
  [[GitHub](https://github.com/ucam-comparch/clarvi)]

+ F32: 针对FPGA的RV32微处理器，VHDL，BSD Licensed。
  [[GitHub](https://github.com/f32c/f32c)]

+ GRVI: Gray Research LLC. 针对FPGA优化的RV32微处理器，commercial licensed。
  [[Web](http://fpga.org/grvi-phalanx/)]

+ Hummingbird E200. 二级流水线，目标替代Cortex-M0/8051, Verilog, Apache 2.0 licensed。
  [[GitHub](https://github.com/SI-RISCV/e200_opensource)]

+ invicta: 一级流水线的RV32微处理器。Verilog，BSD Licensed。
  [[GitHub](https://github.com/qmn/riscv-invicta)]

+ Kamikaze: RV32微处理器。Verilog，MIT Liencensed。
  [[GitHub](https://github.com/rgwan/kamikaze)]

+ KCP53000: Samuel A. Falvo II的RV64处理器实现。Verilog, MPL Licensed。
  [[GitHub](https://github.com/KestrelComputer/polaris)]

+ nanorv32: 2机流水线的RV32实现。Verilog, GPLv2 Licensed。
  [[GitHub](https://github.com/rbarzic/nanorv32)]

+ OpenV: 支持RV32的开源微处理器，Verilog，MIT Licensed，OnChipUIS，来源于哥伦比亚的Universidad Industrial de Santander。
  [[GitHub](https://github.com/onchipuis/mriscv)]

+ ORCA: 支持RV32的开源微处理器，VHDL，BSD Licensed，VectorBlox。
  [[Github](https://github.com/VectorBlox/orca)]

+ PicoRV32: Clifford Wolf设计的(针对FPGA)RV32微处理器，Verilog，ISC Licensed。
  [[GitHub](https://github.com/cliffordwolf/picorv32)]

+ Potato: 针对FPGA的RV32微处理器。VHDL，BSD Licensed。
  [[GitHub](https://github.com/skordal/potato)]

+ RI5CY：支持RV32的开源微处理器
  - PULPino: SystemVerilog，Solderpad Licensed, 来源于苏黎世理工和博洛尼亚大学的PULP项目。
    [[GitHub](https://github.com/pulp-platform/pulpino)]
    [[Web](http://www.pulp-platform.org/)]

+ RIDERCORE: RISC-V乱序处理器设计。Verilog, BSD Licensed。
  [[GitHub](https://github.com/ridecore/ridecore)]

+ River: GNSS Senor Ltd.基于Rocket架构开发的RV64处理器。VHDL, BSD Licensed。
  [[GitHub](https://github.com/sergeykhbr/riscv_vhdl)]

+ Rocket: 支持RV64/32的开源处理器
  - Rocket-Chip: Chisel，BSD Licensed, Free chips project, UC Berkeley分离的开源工程。
    [[GitHub](https://github.com/freechipsproject/rocket-chip)]
  - Freedom: Chisel，Apache Licensed, SiFive, UC Berkeley分离的初创企业。
    [[GitHub](https://github.com/sifive/freedom)]
    [[Web](https://www.sifive.com/products/freedom/)]
  - lowRISC：Chisel+SystemVerilog，Solderpad Licensed, 从剑桥大学发起的非盈利组织。
    [[GitHub](https://github.com/lowrisc/lowrisc-chip)]
    [[Web](http://www.lowrisc.org)]
  - RoCC: the Rocket customized coprocessor interface 和Rocket处理器紧密互联的的协处理器接口。
    [[BSG](https://bitbucket.org/taylor-bsg/bsg_riscv)]

+ RV12: RoaLogic的RV32微处理器。Verilog, RoaLogic non-commercial Licensed。
  [[GitHub](https://github.com/RoaLogic/RV12)]

+ SCR1: Syntacore的RV32开源微处理器。SystemVerilog，Solerpad Licensed。
  [[GitHub](https://github.com/syntacore/scr1)]

+ SHAKTI：印度IIT-Madras的RISC-V处理器系列，Bluespec, BSD Licensed。
  [[Bitbucket](https://bitbucket.org/casl/shakti_public)]

+ Sodor: 教学用的RISC-V处理器。Chisel, BSD Licensed。
  [[GitHub](https://github.com/ucb-bar/riscv-sodor)]

+ uRV: 针对FPGA的RV32微处理器。Verilog，LGPLv3 Licensed.
  [[ohwr](http://www.ohwr.org/projects/urv-core)]

+ VexRiscv: 用SpinalHDL编写的针对FPGA的RV32微处理器。SpinalHDL, MIT Licensed。
  [[GitHub](https://github.com/SpinalHDL/VexRiscv)]

+ YARVI: Tommy Thorn设计的RV32I微处理器，Verilog，GPL2v Licensed。
  [[GitHub](https://github.com/tommythorn/yarvi)]

## 其他硬件模块

+ RISCV-FPU：王逵的FPU设计。
  [[GitHub](https://github.com/cnrv/RISCV-FPU)]



  
## 操作系统

+ Linux
  - [RISCVEMU](https://bellard.org/riscvemu/): Fabrice Bellard维护的RISC-V Linux emulator。
  - [JSLinux](https://bellard.org/jslinux/): Fabrice Bellard维护的可在浏览器里运行的RISC-V操作系统。

+ Linux distribution
  - [Debian](https://wiki.debian.org/RISC-V#What_is_a_Debian_port.3F):Debian RISC-V port
  - [Fedora](https://fedoraproject.org/wiki/Architectures/RISC-V/Bootstrapping):Fedora RISC-V port
  - [Fedora:bootstrap](https://github.com/rwmjones/fedora-riscv-bootstrap):Fedora RISC-V complation scripts

## 开发工具

+ GNU工具链
  - RISC-V GNU GCC [riscv-gnu-toolchain](https://github.com/riscv/riscv-gnu-toolchain)
  - Andes LLVM port [riscv-llvm-toolchain](https://github.com/andestech/riscv-llvm-toolchain)
  - lowRISC LLVM upstream patches [riscv-llvm](https://github.com/lowRISC/riscv-llvm)
  - lowRISC LLVM integration [riscv-llvm-integration](https://github.com/lowRISC/riscv-llvm-integration)
  - Palmer Dabbelt的[RISC-V GCC参数解释](https://www.sifive.com/blog/2017/08/14/all-aboard-part-1-compiler-args/)
  - Palmer Dabbelt的[FAQ about RISC-V Software](http://www.dabbelt.com/~palmer/riscv-faq.html)。

+ RISC-V C library
  - [glibc](https://github.com/riscv/riscv-glibc)
  - [newlib](https://github.com/riscv/riscv-newlib)
  - musl:[link1](https://github.com/rv8-io/musl-riscv-toolchain) & [link2](https://github.com/lluixhi/musl-riscv)

+ 运行和仿真
  - [rv8](https://rv8.io/): x86-64上的RISC-V二进制仿真器，支持即时编译优化。
  - [FireSim](https://fires.im/): 一个由加州伯克利开发的利用FPGA加速的cycle-accurate硬件仿真Amazon F1云平台。
  - [MIDAS](https://github.com/ucb-bar/midas-release): 利用FPGA加速的cycle-accurate硬件仿真器，FireSim的后台。

+ 在线调试
  - [embecosm/riscv-gdbserver](https://github.com/embecosm/riscv-gdbserver): 由[Embecosm](http://www.embecosm.com/)维护的用于连接GDB的宿主机library，现在还只能用于调试Embecosm的picorv32 port。
  
+ 各种语言支持：
  - [Rust toolchain by RISC-V LLVM](https://github.com/dvc94ch/riscv-rust-toolchain)
  - [Go on risc-v](https://github.com/riscv/riscv-go)

## 形式化验证

+ 指令集的形式化模型
  - Prashant Mundkur (SRI) 的[L3模型](https://github.com/pmundkur/l3riscv)
  - Clifford Wolf 的[Verilog模型](https://github.com/cliffordwolf/riscv-formal)和[文档](http://www.clifford.at/papers/2017/riscv-formal/slides.pdf)
  - Rishiyur Nikhil (Bluespec, Inc.)的[BSV模型](https://github.com/rsnikhil/RISCV_ISA_Formal_Spec_in_BSV)
  - Peter Sewell (Cambridge)的[SAIL模型](https://bitbucket.org/Peter_Sewell/sail/src/07fad742df72ff6e7bfb948c1c353a2cf12f5e28/risc-v/riscv.sail?fileviewer=file-view-default)



## 文档

+ 标准文档
  - RISC-V User Spec V 2.20
    [[PDF](https://content.riscv.org/wp-content/uploads/2017/05/riscv-spec-v2.2.pdf)]
    [[GitHub](https://github.com/riscv/riscv-isa-manual)]
  - RISC-V Privileged Spec V 1.10
    [[PDF](https://content.riscv.org/wp-content/uploads/2017/05/riscv-privileged-v1.10.pdf)]
    [[GitHub](https://github.com/riscv/riscv-isa-manual)]

+ 近似标准的文档
  - RISC-V 工具链资料搜集页面
    [[GitHub](https://github.com/riscv/riscv-toolchain-conventions)]
  - RISC-V ELF psABI Document
    [[GitHub](https://github.com/riscv/riscv-elf-psabi-doc)]
  - RISC-V assembly manual
    [[GitHub](https://github.com/riscv/riscv-asm-manual)]
  - RV8 的 ISA 总结
    [[GitHub](https://github.com/rv8-io/rv8/tree/master/meta)]
  - RISC-V 微处理器平台描述
    [[GitHub](https://github.com/emb-riscv/specs-markdown)]
    [[Web](https://emb-riscv.github.io/)]
  - Device tree文档
    [[GitHub](https://github.com/riscv/riscv-device-tree-doc)]
  - Unix-class Platform文档
    [[GitHub](https://github.com/riscv/riscv-platform-specs)]

+ Spike
  - [Tutuorial on Spike Internal](https://github.com/poweihuang17/Documentation_Spike)

+ Chisel
  - [FAQ](https://github.com/freechipsproject/chisel3/wiki/Frequently-Asked-Questions)
  - [User Guide](https://github.com/freechipsproject/chisel3/wiki/Short-Users-Guide-to-Chisel)
  - [ScalaDoc](https://chisel.eecs.berkeley.edu/api/)
  - [Chisel Learning Journey](https://github.com/librecores/riscv-sodor/wiki/Chisel-Learning-Journey)

+ Rocket
  - [SiFive platforms](https://www.sifive.com/documentation/)
  - [lowRISC SoCs](http://www.lowrisc.org/docs/)
  - [TileLink](https://www.sifive.com/documentation/tilelink/tilelink-spec/)
  - [Rocket-chip阅读笔记](https://github.com/cnrv/rocket-chip-read)


+ 教学课程
  - CMU 447 [Introduction to Computer Architecture](https://users.ece.cmu.edu/~jhoe/doku/doku.php?id=18-447_introduction_to_computer_architecture)
  - Cornell ECE 4750 [Computer Architecture](http://www.csl.cornell.edu/courses/ece4750/2016f/handouts.html)
  - MIT 6.175 [Constructive Computer Architecture](http://csg.csail.mit.edu/6.175/)
  - 丹麦技术大学(DTU) [Computer Architecture and Engineering course](https://github.com/schoeberl/cae-lab)
  - Berkeley CS61C [Great Ideas in machine structure](http://inst.eecs.berkeley.edu/~cs61c/fa17/)
  - Berkeley EECS151 [Introduction to Digital Design and Integrated Circuits](http://inst.eecs.berkeley.edu/~eecs151/sp18/)
  - [Ripes:教学用的图形化处理器流水线](https://github.com/mortbopet/Ripes)
  
+ 书籍
  - David Patterson John Hennessy著：[Computer Organization and Design RISC-V Edition](https://www.elsevier.com/books/computer-organization-and-design-risc-v-edition/patterson/978-0-12-812275-4)

+ Blog
  - Nitish Srivastava: [Adding custom instruction to RISCV ISA and running it on gem5 and spike](https://nitish2112.github.io/post/adding-instruction-riscv/)

## 其他

+ [CNRV中国镜像](https://github.com/cnrv/clone-helpers/blob/master/README.md): 提供大量RISC-V相关工程的国内下载镜像。
+ [RISC-V wiki](https://github.com/riscv/riscv-wiki/wiki): 由Arun维护的近官方RISC-V维科页面。
+ [What Every Programmer Should Know About Floating-Point Arithmetic](http://floating-point-gui.de/)
+ ["RISC-V" from Wikipedia](https://en.wikipedia.org/wiki/RISC-V)

------------------------

**如果本页中的连接失效，请联系CNRV更新，或直接向网页源码[发送PR](https://github.com/cnrv/home/pulls)修正。**

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/cn/80x15.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/">知识共享署名-非商业性使用-相同方式共享 3.0 中国大陆许可协议</a>进行许可。

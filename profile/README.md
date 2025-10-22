## AI Foundry: own your own AI from silicon to open models.

[![](https://dcbadge.limes.pink/api/server/WNKvkefkUs?logoColor=f9a03f)](https://discord.gg/WNKvkefkUs) [![Follow us on HF](https://huggingface.co/datasets/huggingface/badges/resolve/main/follow-us-on-hf-lg.svg)](https://huggingface.co/aifoundry-org)

Hi there 👋 -- we are building a collection of shareable building blocks (from silicon to open models) empowering humanity to own its own AI. We bring together open source hackers in the fields of computer architecture, ASIC design, advanced systems, and neural network compilers who are bold enough to think that you don't have to work for a mega corporation to build your own computers for AI. Our mission is to bring the spirit of [Homebrew Computer Club](https://en.wikipedia.org/wiki/Homebrew_Computer_Club) back into vogue. The easiest place to find us is on our [Discord](https://discord.com/invite/WNKvkefkUs) or at [FOSDEM](https://fosdem.org/2025/schedule/track/ai/).

We believe AGI can only be achieved through [cat super intelligence](https://en.wikipedia.org/wiki/Accelerando#Characters) and we grew up playing the [worst Atari game ever created](https://en.wikipedia.org/wiki/E.T._the_Extra-Terrestrial_(video_game)).

We don't attempt to re-invent the wheel and try to work directly with as many upstream communities as possible. We are eternaly grateful for [ggml/llama.cpp](https://ggml.ai/), [tinygrad](https://tinygrad.org/), [gcc](https://github.com/riscv-collab/riscv-gnu-toolchain), [llvm](https://llvm.org/) and [RISC-V](https://riscv.org/) (just to name a few) and we're not shy to use those building blocks in our end-to-end designs.

When we can't find appropriate building blocks in the open -- we're not shy to build them ourselves from scratch. That's why we're going all the way to chip design level and creating world's first fully open source, many core hardware architecture scalable from a few dozen processing units to 4096. We also have opinions about software side of AI inference servers and are trying to change the state of the art there as well.

Oh, and mark our words: [Transputers](https://tu-dresden.de/ing/informatik/ti/vlsi/ressourcen/dateien/dateien_studium/dateien_lehstuhlseminar/vortraege_lehrstuhlseminar/folder-2013-04-11-7748162390/20130612_Transputer-Architecture_Handout_UM.pdf?lang=en) are due for a huge comeback in the AI-centric world.

![](https://raw.githubusercontent.com/aifoundry-org/.github/refs/heads/main/transputer.gif)

## ET and reference hardware designs
- [ET Design Overview](https://github.com/aifoundry-org/et-man)
- [ET SOC1 Datasheet](https://github.com/aifoundry-org/et-man)
- [ET SOC1 PCIe Board schematics](https://github.com/aifoundry-org/et-man)
- [ET Programmer's Reference Manual](https://github.com/aifoundry-org/et-man)

### RISC-V enablement
- [ET RISC-V GNU Toolchain](https://github.com/aifoundry-org/riscv-gnu-toolchain)
- [ET ISA extensions patches for binutils](https://github.com/aifoundry-org/binutils-gdb)

### System support
- [ET Sowftware Emulator](https://github.com/aifoundry-org/et-platform/tree/master/sw-sysemu#sw-sysemu)
- [ET SOC1 PCI card Linux driver](https://github.com/aifoundry-org/et-platform/tree/master/et-driver)
- [ET SOC1 PCI card control plane](https://github.com/aifoundry-org/et-platform/tree/master/device-management-application#et-top-application)

## Inference frameworks supporting ET
- [ggml/llama.cpp](https://github.com/aifoundry-org/llama.cpp/tree/et)
- [tinygrad](https://github.com/aifoundry-org/tinygrad/tree/et)
- [benchmarks](https://github.com/aifoundry-org/turtlenekko)

## Inference engines and CLIs
- [nekko](https://github.com/nekkoai/cli)
- [cluster storage manager](https://github.com/aifoundry-org/storage-manager)
- [Prompt Testing](https://github.com/aifoundry-org/llamagator)

## Research
- [Quantization Aware Training](https://arxiv.org/abs/2508.14004)
- [MHAQ](https://github.com/aifoundry-org/MHAQ)
- [tinyMHAQ](https://github.com/aifoundry-org/tinyMHAQ)


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

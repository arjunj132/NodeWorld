# FastVM docs
FastVM is a local virtual machine manager based on [JSLinux](https://bellard.org/jslinux/) by Fabrice Bellard.

Clone this repository and use `cd FastVM` to open the directory.

Run:

```
npm i
npm start
```

And then use the tabs on the left to navigate through the VMs. Each VM has a specific information page:

```
System info:
OS: Operating System
Copyright: (c) jsLinux
Information: cfg file
VM: link to vm
```

You usually want to access the VM, so you use the `VM` link.

## Don't have time to install the VM? Just open the link!

Open a OS without installing FastVM!

<div id="alpine" class="tabcontent"> <pre>
System info:
OS: Alpine Linux 3.12.0	(Console)
Copyright: (c) jsLinux
Information: <a href='https://bellard.org/jslinux/alpine-x86.cfg'>alpine-x86.cfg</a>
VM: <a href='https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192'>https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192</a>
</pre> </div><div id="windows" class="tabcontent"> <pre>
System info:
OS: Windows 2000 (Graphical)
Copyright: (c) jsLinux
Information: <a href='https://bellard.org/jslinux/win2k.cfg'>win2k.cfg</a>
VM: <a href='https://bellard.org/jslinux/vm.html?url=win2k.cfg&mem=192&graphic=1&w=1024&h=768'>https://bellard.org/jslinux/vm.html?url=win2k.cfg&mem=192&graphic=1&w=1024&h=768</a>
</pre> </div><div id="freedos" class="tabcontent"> <pre>
System info:
OS: FreeDOS (VGA Text)
Copyright: (c) jsLinux
Information: <a href='https://bellard.org/jslinux/freedos.cfg'>freedos.cfg</a>
VM: <a href='https://bellard.org/jslinux/vm.html?url=freedos.cfg&mem=64&graphic=1&w=720&h=400'>https://bellard.org/jslinux/vm.html?url=freedos.cfg&mem=64&graphic=1&w=720&h=400</a>
</pre> </div><div id="buildroot" class="tabcontent"> <pre>
System info:
OS: Buildroot Linux (Console)
Copyright: (c) jsLinux
Information: <a href='https://bellard.org/jslinux/buildroot-riscv64.cfg'>buildroot-riscv64.cfg</a>
VM: <a href='https://bellard.org/jslinux/vm.html?cpu=riscv64&url=buildroot-riscv64.cfg&mem=256'>https://bellard.org/jslinux/vm.html?cpu=riscv64&url=buildroot-riscv64.cfg&mem=256</a>
</pre> </div><div id="fedora" class="tabcontent"> <pre>
System info:
OS: Fedora 33 (Console)
Copyright: (c) jsLinux
Information: <a href='https://bellard.org/jslinux/fedora33-riscv.cfg'>fedora33-riscv.cfg</a>
VM: <a href='https://bellard.org/jslinux/vm.html?cpu=riscv64&url=fedora33-riscv.cfg&mem=2566'>https://bellard.org/jslinux/vm.html?cpu=riscv64&url=fedora33-riscv.cfg&mem=256</a>
</pre> </div>

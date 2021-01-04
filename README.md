# KVM-Hidden

This is a collection of patch files - for KVM, QEMU, and OVMF - which when applied together should result in a virtual machine without awareness of its hypervisor. An example Libvirt XML file is provided showing various CPU timers and flags that should be disabled so that the KVM rdtsc timer patch is taken up.

This patch is for VMX - the Intel implementation. For an SVM implementation of the kernel patch, see BetterTiming below.

**I take no responsibility for any damage that occurs to your machine or data as a result of using this software.**

---

# Thanks

Thank you to Samuel Tulach who provided a similar KVM patch for AMD processors here:
[BetterTiming](https://github.com/SamuelTulach/BetterTiming)


[    0.000000] microcode: microcode updated early to revision 0x22, date = 2017-01-27
[    0.000000] Linux version 4.9.0-5-amd64 (debian-kernel@lists.debian.org) (gcc version 6.3.0 20170516 (Debian 6.3.0-18) ) #1 SMP Debian 4.9.65-3+deb9u2 (2018-01-04)
[    0.000000] Command line: BOOT_IMAGE=/boot/vmlinuz-4.9.0-5-amd64 root=UUID=23e09ed1-79c4-4f7f-9091-eb45343533be ro quiet
[    0.000000] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
[    0.000000] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
[    0.000000] x86/fpu: Enabled xstate features 0x7, context size is 832 bytes, using 'standard' format.
[    0.000000] x86/fpu: Using 'eager' FPU context switches.
[    0.000000] e820: BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x0000000000057fff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000058000-0x0000000000058fff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000059000-0x000000000009efff] usable
[    0.000000] BIOS-e820: [mem 0x000000000009f000-0x000000000009ffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x00000000ba77cfff] usable
[    0.000000] BIOS-e820: [mem 0x00000000ba77d000-0x00000000ba783fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x00000000ba784000-0x00000000babb9fff] usable
[    0.000000] BIOS-e820: [mem 0x00000000babba000-0x00000000bb175fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000bb176000-0x00000000cab77fff] usable
[    0.000000] BIOS-e820: [mem 0x00000000cab78000-0x00000000cac10fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000cac11000-0x00000000cac39fff] ACPI data
[    0.000000] BIOS-e820: [mem 0x00000000cac3a000-0x00000000cb5bdfff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x00000000cb5be000-0x00000000cbf6ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000cbf70000-0x00000000cbffefff] type 20
[    0.000000] BIOS-e820: [mem 0x00000000cbfff000-0x00000000cbffffff] usable
[    0.000000] BIOS-e820: [mem 0x00000000cd000000-0x00000000cf1fffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000f8000000-0x00000000fbffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fec00000-0x00000000fec00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed00000-0x00000000fed03fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed1c000-0x00000000fed1ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fee00000-0x00000000fee00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000ff000000-0x00000000ffffffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x000000022fdfffff] usable
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] efi: EFI v2.31 by American Megatrends
[    0.000000] efi:  ESRT=0xcbf6e918  ACPI 2.0=0xcac1a000  ACPI=0xcac1a000  SMBIOS=0xf04c0  MPS=0xfd800 
[    0.000000] SMBIOS 2.8 present.
[    0.000000] DMI: Dell Inc. Inspiron 7447/0AM750, BIOS A07 11/09/2015
[    0.000000] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.000000] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.000000] e820: last_pfn = 0x22fe00 max_arch_pfn = 0x400000000
[    0.000000] MTRR default type: uncachable
[    0.000000] MTRR fixed ranges enabled:
[    0.000000]   00000-9FFFF write-back
[    0.000000]   A0000-BFFFF uncachable
[    0.000000]   C0000-CFFFF write-protect
[    0.000000]   D0000-DFFFF uncachable
[    0.000000]   E0000-FFFFF write-protect
[    0.000000] MTRR variable ranges enabled:
[    0.000000]   0 base 0000000000 mask 7E00000000 write-back
[    0.000000]   1 base 0200000000 mask 7FE0000000 write-back
[    0.000000]   2 base 0220000000 mask 7FF0000000 write-back
[    0.000000]   3 base 00E0000000 mask 7FE0000000 uncachable
[    0.000000]   4 base 00D0000000 mask 7FF0000000 uncachable
[    0.000000]   5 base 00CE000000 mask 7FFE000000 uncachable
[    0.000000]   6 base 00CD000000 mask 7FFF000000 uncachable
[    0.000000]   7 base 022FE00000 mask 7FFFE00000 uncachable
[    0.000000]   8 disabled
[    0.000000]   9 disabled
[    0.000000] x86/PAT: Configuration [0-7]: WB  WC  UC- UC  WB  WC  UC- WT  
[    0.000000] e820: update [mem 0xcd000000-0xffffffff] usable ==> reserved
[    0.000000] e820: last_pfn = 0xcc000 max_arch_pfn = 0x400000000
[    0.000000] found SMP MP-table at [mem 0x000fdaf0-0x000fdaff] mapped at [ffff8fe6800fdaf0]
[    0.000000] esrt: Reserving ESRT space from 0x00000000cbf6e918 to 0x00000000cbf6e950.
[    0.000000] Base memory trampoline at [ffff8fe680097000] 97000 size 24576
[    0.000000] Using GB pages for direct mapping
[    0.000000] BRK [0x220b37000, 0x220b37fff] PGTABLE
[    0.000000] BRK [0x220b38000, 0x220b38fff] PGTABLE
[    0.000000] BRK [0x220b39000, 0x220b39fff] PGTABLE
[    0.000000] BRK [0x220b3a000, 0x220b3afff] PGTABLE
[    0.000000] BRK [0x220b3b000, 0x220b3bfff] PGTABLE
[    0.000000] BRK [0x220b3c000, 0x220b3cfff] PGTABLE
[    0.000000] BRK [0x220b3d000, 0x220b3dfff] PGTABLE
[    0.000000] BRK [0x220b3e000, 0x220b3efff] PGTABLE
[    0.000000] BRK [0x220b3f000, 0x220b3ffff] PGTABLE
[    0.000000] BRK [0x220b40000, 0x220b40fff] PGTABLE
[    0.000000] BRK [0x220b41000, 0x220b41fff] PGTABLE
[    0.000000] BRK [0x220b42000, 0x220b42fff] PGTABLE
[    0.000000] RAMDISK: [mem 0x35cfd000-0x36e75fff]
[    0.000000] ACPI: Early table checksum verification disabled
[    0.000000] ACPI: RSDP 0x00000000CAC1A000 000024 (v02 DELL  )
[    0.000000] ACPI: XSDT 0x00000000CAC1A0A0 0000C4 (v01 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: FACP 0x00000000CAC263D0 00010C (v05 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: DSDT 0x00000000CAC1A1F8 00C1D5 (v02 DELL   QA09     00000034 INTL 20120711)
[    0.000000] ACPI: FACS 0x00000000CB5B9080 000040
[    0.000000] ACPI: APIC 0x00000000CAC264E0 000092 (v03 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: FPDT 0x00000000CAC26578 000044 (v01 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: ASF! 0x00000000CAC265C0 0000A5 (v32 INTEL   HCG     00000001 TFSM 000F4240)
[    0.000000] ACPI: SSDT 0x00000000CAC26668 000228 (v01 INTEL  sensrhub 00000000 INTL 20120711)
[    0.000000] ACPI: SSDT 0x00000000CAC26890 00019D (v01 Intel  zpodd    00001000 INTL 20120711)
[    0.000000] ACPI: SLIC 0x00000000CAC26A30 000176 (v01 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: SSDT 0x00000000CAC26BA8 000539 (v01 PmRef  Cpu0Ist  00003000 INTL 20120711)
[    0.000000] ACPI: SSDT 0x00000000CAC270E8 000AD8 (v01 PmRef  CpuPm    00003000 INTL 20120711)
[    0.000000] ACPI: SSDT 0x00000000CAC27BC0 000436 (v01 CtdpB  CtdpB    00001000 INTL 20120711)
[    0.000000] ACPI: MCFG 0x00000000CAC27FF8 00003C (v01 DELL   QA09     01072009 MSFT 00000097)
[    0.000000] ACPI: SSDT 0x00000000CAC28038 00B164 (v01 DptfTa DptfTabl 00001000 INTL 20120711)
[    0.000000] ACPI: HPET 0x00000000CAC331A0 000038 (v01 DELL   QA09     01072009 AMI. 00000005)
[    0.000000] ACPI: SSDT 0x00000000CAC331D8 000315 (v01 SataRe SataTabl 00001000 INTL 20120711)
[    0.000000] ACPI: SSDT 0x00000000CAC334F0 00355F (v01 SaSsdt SaSsdt   00003000 INTL 20091112)
[    0.000000] ACPI: SSDT 0x00000000CAC36A50 001590 (v01 SgRef  SgPeg    00001000 INTL 20120711)
[    0.000000] ACPI: MSDM 0x00000000CAC37FE0 000055 (v03 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: BGRT 0x00000000CAC38038 000038 (v00 DELL   QA09     01072009 AMI  00010013)
[    0.000000] ACPI: DMAR 0x00000000CAC38070 0000B8 (v01 INTEL  HSW      00000001 INTL 00000001)
[    0.000000] ACPI: SSDT 0x00000000CAC38128 00195C (v01 OptRef OptTabl  00001000 INTL 20120711)
[    0.000000] ACPI: Local APIC address 0xfee00000
[    0.000000] No NUMA configuration found
[    0.000000] Faking a node at [mem 0x0000000000000000-0x000000022fdfffff]
[    0.000000] NODE_DATA(0) allocated [mem 0x22fdfb000-0x22fdfffff]
[    0.000000] Zone ranges:
[    0.000000]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.000000]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.000000]   Normal   [mem 0x0000000100000000-0x000000022fdfffff]
[    0.000000]   Device   empty
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x0000000000001000-0x0000000000057fff]
[    0.000000]   node   0: [mem 0x0000000000059000-0x000000000009efff]
[    0.000000]   node   0: [mem 0x0000000000100000-0x00000000ba77cfff]
[    0.000000]   node   0: [mem 0x00000000ba784000-0x00000000babb9fff]
[    0.000000]   node   0: [mem 0x00000000bb176000-0x00000000cab77fff]
[    0.000000]   node   0: [mem 0x00000000cbfff000-0x00000000cbffffff]
[    0.000000]   node   0: [mem 0x0000000100000000-0x000000022fdfffff]
[    0.000000] Initmem setup node 0 [mem 0x0000000000001000-0x000000022fdfffff]
[    0.000000] On node 0 totalpages: 2073427
[    0.000000]   DMA zone: 64 pages used for memmap
[    0.000000]   DMA zone: 26 pages reserved
[    0.000000]   DMA zone: 3997 pages, LIFO batch:0
[    0.000000]   DMA32 zone: 12887 pages used for memmap
[    0.000000]   DMA32 zone: 824758 pages, LIFO batch:31
[    0.000000]   Normal zone: 19448 pages used for memmap
[    0.000000]   Normal zone: 1244672 pages, LIFO batch:31
[    0.000000] Reserving Intel graphics memory at 0x00000000cd200000-0x00000000cf1fffff
[    0.000000] ACPI: PM-Timer IO Port: 0x1808
[    0.000000] ACPI: Local APIC address 0xfee00000
[    0.000000] ACPI: LAPIC_NMI (acpi_id[0xff] high edge lint[0x1])
[    0.000000] IOAPIC[0]: apic_id 8, version 32, address 0xfec00000, GSI 0-23
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    0.000000] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    0.000000] ACPI: IRQ0 used by override.
[    0.000000] ACPI: IRQ9 used by override.
[    0.000000] Using ACPI (MADT) for SMP configuration information
[    0.000000] ACPI: HPET id: 0x8086a701 base: 0xfed00000
[    0.000000] smpboot: Allowing 8 CPUs, 0 hotplug CPUs
[    0.000000] PM: Registered nosave memory: [mem 0x00000000-0x00000fff]
[    0.000000] PM: Registered nosave memory: [mem 0x00058000-0x00058fff]
[    0.000000] PM: Registered nosave memory: [mem 0x0009f000-0x0009ffff]
[    0.000000] PM: Registered nosave memory: [mem 0x000a0000-0x000fffff]
[    0.000000] PM: Registered nosave memory: [mem 0xba77d000-0xba783fff]
[    0.000000] PM: Registered nosave memory: [mem 0xbabba000-0xbb175fff]
[    0.000000] PM: Registered nosave memory: [mem 0xcab78000-0xcac10fff]
[    0.000000] PM: Registered nosave memory: [mem 0xcac11000-0xcac39fff]
[    0.000000] PM: Registered nosave memory: [mem 0xcac3a000-0xcb5bdfff]
[    0.000000] PM: Registered nosave memory: [mem 0xcb5be000-0xcbf6ffff]
[    0.000000] PM: Registered nosave memory: [mem 0xcbf70000-0xcbffefff]
[    0.000000] PM: Registered nosave memory: [mem 0xcc000000-0xccffffff]
[    0.000000] PM: Registered nosave memory: [mem 0xcd000000-0xcf1fffff]
[    0.000000] PM: Registered nosave memory: [mem 0xcf200000-0xf7ffffff]
[    0.000000] PM: Registered nosave memory: [mem 0xf8000000-0xfbffffff]
[    0.000000] PM: Registered nosave memory: [mem 0xfc000000-0xfebfffff]
[    0.000000] PM: Registered nosave memory: [mem 0xfec00000-0xfec00fff]
[    0.000000] PM: Registered nosave memory: [mem 0xfec01000-0xfecfffff]
[    0.000000] PM: Registered nosave memory: [mem 0xfed00000-0xfed03fff]
[    0.000000] PM: Registered nosave memory: [mem 0xfed04000-0xfed1bfff]
[    0.000000] PM: Registered nosave memory: [mem 0xfed1c000-0xfed1ffff]
[    0.000000] PM: Registered nosave memory: [mem 0xfed20000-0xfedfffff]
[    0.000000] PM: Registered nosave memory: [mem 0xfee00000-0xfee00fff]
[    0.000000] PM: Registered nosave memory: [mem 0xfee01000-0xfeffffff]
[    0.000000] PM: Registered nosave memory: [mem 0xff000000-0xffffffff]
[    0.000000] e820: [mem 0xcf200000-0xf7ffffff] available for PCI devices
[    0.000000] Booting paravirtualized kernel on bare hardware
[    0.000000] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645519600211568 ns
[    0.000000] setup_percpu: NR_CPUS:512 nr_cpumask_bits:512 nr_cpu_ids:8 nr_node_ids:1
[    0.000000] percpu: Embedded 35 pages/cpu @ffff8fe8afa00000 s105304 r8192 d29864 u262144
[    0.000000] pcpu-alloc: s105304 r8192 d29864 u262144 alloc=1*2097152
[    0.000000] pcpu-alloc: [0] 0 1 2 3 4 5 6 7 
[    0.000000] Built 1 zonelists in Node order, mobility grouping on.  Total pages: 2041002
[    0.000000] Policy zone: Normal
[    0.000000] Kernel command line: BOOT_IMAGE=/boot/vmlinuz-4.9.0-5-amd64 root=UUID=23e09ed1-79c4-4f7f-9091-eb45343533be ro quiet
[    0.000000] PID hash table entries: 4096 (order: 3, 32768 bytes)
[    0.000000] Calgary: detecting Calgary via BIOS EBDA area
[    0.000000] Calgary: Unable to locate Rio Grande table in EBDA - bailing!
[    0.000000] Memory: 7865752K/8293708K available (6196K kernel code, 1159K rwdata, 2848K rodata, 1408K init, 688K bss, 427956K reserved, 0K cma-reserved)
[    0.000000] Kernel/User page tables isolation: enabled
[    0.000000] Hierarchical RCU implementation.
[    0.000000] 	Build-time adjustment of leaf fanout to 64.
[    0.000000] 	RCU restricting CPUs from NR_CPUS=512 to nr_cpu_ids=8.
[    0.000000] RCU: Adjusting geometry for rcu_fanout_leaf=64, nr_cpu_ids=8
[    0.000000] NR_IRQS:33024 nr_irqs:488 16
[    0.000000] Console: colour dummy device 80x25
[    0.000000] console [tty0] enabled
[    0.000000] clocksource: hpet: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 133484882848 ns
[    0.000000] hpet clockevent registered
[    0.000000] tsc: Fast TSC calibration using PIT
[    0.000000] tsc: Detected 2494.407 MHz processor
[    0.000018] Calibrating delay loop (skipped), value calculated using timer frequency.. 4988.81 BogoMIPS (lpj=9977628)
[    0.000019] pid_max: default: 32768 minimum: 301
[    0.000033] ACPI: Core revision 20160831
[    0.010399] ACPI: 11 ACPI AML tables successfully acquired and loaded
[    0.010813] Security Framework initialized
[    0.010814] Yama: disabled by default; enable with sysctl kernel.yama.*
[    0.010818] AppArmor: AppArmor disabled by boot time parameter
[    0.011099] Dentry cache hash table entries: 1048576 (order: 11, 8388608 bytes)
[    0.012158] Inode-cache hash table entries: 524288 (order: 10, 4194304 bytes)
[    0.012633] Mount-cache hash table entries: 16384 (order: 5, 131072 bytes)
[    0.012638] Mountpoint-cache hash table entries: 16384 (order: 5, 131072 bytes)
[    0.012839] CPU: Physical Processor ID: 0
[    0.012839] CPU: Processor Core ID: 0
[    0.012842] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
[    0.012843] ENERGY_PERF_BIAS: View and update with x86_energy_perf_policy(8)
[    0.012845] mce: CPU supports 9 MCE banks
[    0.012852] CPU0: Thermal monitoring enabled (TM1)
[    0.012863] process: using mwait in idle threads
[    0.012865] Last level iTLB entries: 4KB 1024, 2MB 1024, 4MB 1024
[    0.012866] Last level dTLB entries: 4KB 1024, 2MB 1024, 4MB 1024, 1GB 4
[    0.013109] Freeing SMP alternatives memory: 24K
[    0.038899] ftrace: allocating 25212 entries in 99 pages
[    0.045840] smpboot: Max logical packages: 2
[    0.045844] DMAR: Host address width 39
[    0.045845] DMAR: DRHD base: 0x000000fed90000 flags: 0x0
[    0.045850] DMAR: dmar0: reg_base_addr fed90000 ver 1:0 cap c0000020660462 ecap f0101a
[    0.045851] DMAR: DRHD base: 0x000000fed91000 flags: 0x1
[    0.045854] DMAR: dmar1: reg_base_addr fed91000 ver 1:0 cap d2008020660462 ecap f010da
[    0.045854] DMAR: RMRR base: 0x000000cbe91000 end: 0x000000cbe9ffff
[    0.045855] DMAR: RMRR base: 0x000000cd000000 end: 0x000000cf1fffff
[    0.045856] DMAR-IR: IOAPIC id 8 under DRHD base  0xfed91000 IOMMU 1
[    0.045857] DMAR-IR: HPET id 0 under DRHD base 0xfed91000
[    0.045857] DMAR-IR: Queued invalidation will be enabled to support x2apic and Intr-remapping.
[    0.046087] DMAR-IR: Enabled IRQ remapping in x2apic mode
[    0.046087] x2apic enabled
[    0.046091] Switched APIC routing to cluster x2apic.
[    0.046511] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
[    0.086198] TSC deadline timer enabled
[    0.086200] smpboot: CPU0: Intel(R) Core(TM) i7-4710HQ CPU @ 2.50GHz (family: 0x6, model: 0x3c, stepping: 0x3)
[    0.086203] Performance Events: PEBS fmt2+, Haswell events, 16-deep LBR, full-width counters, Intel PMU driver.
[    0.086240] ... version:                3
[    0.086240] ... bit width:              48
[    0.086240] ... generic registers:      4
[    0.086241] ... value mask:             0000ffffffffffff
[    0.086241] ... max period:             00007fffffffffff
[    0.086241] ... fixed-purpose events:   3
[    0.086242] ... event mask:             000000070000000f
[    0.086703] NMI watchdog: enabled on all CPUs, permanently consumes one hw-PMU counter.
[    0.086781] x86: Booting SMP configuration:
[    0.086781] .... node  #0, CPUs:      #1 #2 #3 #4 #5 #6 #7
[    0.106053] x86: Booted up 1 node, 8 CPUs
[    0.106055] smpboot: Total of 8 processors activated (39910.51 BogoMIPS)
[    0.111609] devtmpfs: initialized
[    0.111655] x86/mm: Memory block size: 128MB
[    0.113240] PM: Registering ACPI NVS region [mem 0xba77d000-0xba783fff] (28672 bytes)
[    0.113241] PM: Registering ACPI NVS region [mem 0xcac3a000-0xcb5bdfff] (9977856 bytes)
[    0.113460] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
[    0.113470] futex hash table entries: 2048 (order: 5, 131072 bytes)
[    0.113511] pinctrl core: initialized pinctrl subsystem
[    0.113591] NET: Registered protocol family 16
[    0.127371] cpuidle: using governor ladder
[    0.143380] cpuidle: using governor menu
[    0.143400] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
[    0.143401] ACPI: bus type PCI registered
[    0.143402] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    0.143467] PCI: MMCONFIG for domain 0000 [bus 00-3f] at [mem 0xf8000000-0xfbffffff] (base 0xf8000000)
[    0.143469] PCI: MMCONFIG at [mem 0xf8000000-0xfbffffff] reserved in E820
[    0.143471] pmd_set_huge: Cannot satisfy [mem 0xf8000000-0xf8200000] with a huge-page mapping due to MTRR override.
[    0.143533] PCI: Using configuration type 1 for base access
[    0.143579] core: PMU erratum BJ122, BV98, HSD29 worked around, HT is on
[    0.159482] HugeTLB registered 1 GB page size, pre-allocated 0 pages
[    0.159483] HugeTLB registered 2 MB page size, pre-allocated 0 pages
[    0.159699] ACPI: Added _OSI(Module Device)
[    0.159700] ACPI: Added _OSI(Processor Device)
[    0.159701] ACPI: Added _OSI(3.0 _SCP Extensions)
[    0.159702] ACPI: Added _OSI(Processor Aggregator Device)
[    0.159902] ACPI: Executed 2 blocks of module-level executable AML code
[    0.167384] ACPI: [Firmware Bug]: BIOS _OSI(Linux) query ignored
[    0.168500] ACPI: Dynamic OEM Table Load:
[    0.168506] ACPI: SSDT 0xFFFF8FE8A58C5800 0003D3 (v01 PmRef  Cpu0Cst  00003001 INTL 20120711)
[    0.168879] ACPI: Dynamic OEM Table Load:
[    0.168884] ACPI: SSDT 0xFFFF8FE8A5A05800 0005AA (v01 PmRef  ApIst    00003000 INTL 20120711)
[    0.169301] ACPI: Dynamic OEM Table Load:
[    0.169305] ACPI: SSDT 0xFFFF8FE8A5A5F200 000119 (v01 PmRef  ApCst    00003000 INTL 20120711)
[    0.170834] ACPI : EC: EC started
[    0.170835] ACPI : EC: interrupt blocked
[    0.172175] ACPI: \_SB_.PCI0.LPCB.EC__: Used as first EC
[    0.172176] ACPI: \_SB_.PCI0.LPCB.EC__: GPE=0x17, EC_CMD/EC_SC=0x66, EC_DATA=0x62
[    0.172177] ACPI: \_SB_.PCI0.LPCB.EC__: Used as boot DSDT EC to handle transactions
[    0.172177] ACPI: Interpreter enabled
[    0.172199] ACPI: (supports S0 S3 S4 S5)
[    0.172200] ACPI: Using IOAPIC for interrupt routing
[    0.172219] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    0.176339] ACPI: Power Resource [PG00] (on)
[    0.196571] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-3e])
[    0.196575] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI]
[    0.196770] acpi PNP0A08:00: _OSC: platform does not support [PCIeHotplug PME]
[    0.196878] acpi PNP0A08:00: _OSC: OS now controls [AER PCIeCapability]
[    0.196879] acpi PNP0A08:00: FADT indicates ASPM is unsupported, using BIOS configuration
[    0.197202] PCI host bridge to bus 0000:00
[    0.197204] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    0.197205] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
[    0.197206] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
[    0.197207] pci_bus 0000:00: root bus resource [mem 0x000d0000-0x000d3fff window]
[    0.197207] pci_bus 0000:00: root bus resource [mem 0x000d4000-0x000d7fff window]
[    0.197208] pci_bus 0000:00: root bus resource [mem 0x000d8000-0x000dbfff window]
[    0.197209] pci_bus 0000:00: root bus resource [mem 0x000dc000-0x000dffff window]
[    0.197210] pci_bus 0000:00: root bus resource [mem 0xcf200000-0xfeafffff window]
[    0.197211] pci_bus 0000:00: root bus resource [bus 00-3e]
[    0.197216] pci 0000:00:00.0: [8086:0c04] type 00 class 0x060000
[    0.197289] pci 0000:00:01.0: [8086:0c01] type 01 class 0x060400
[    0.197317] pci 0000:00:01.0: PME# supported from D0 D3hot D3cold
[    0.197389] pci 0000:00:01.0: System wakeup disabled by ACPI
[    0.197413] pci 0000:00:01.1: [8086:0c05] type 01 class 0x060400
[    0.197437] pci 0000:00:01.1: PME# supported from D0 D3hot D3cold
[    0.197491] pci 0000:00:01.1: System wakeup disabled by ACPI
[    0.197518] pci 0000:00:02.0: [8086:0416] type 00 class 0x030000
[    0.197525] pci 0000:00:02.0: reg 0x10: [mem 0xf7400000-0xf77fffff 64bit]
[    0.197529] pci 0000:00:02.0: reg 0x18: [mem 0xd0000000-0xdfffffff 64bit pref]
[    0.197531] pci 0000:00:02.0: reg 0x20: [io  0xf000-0xf03f]
[    0.197589] pci 0000:00:03.0: [8086:0c0c] type 00 class 0x040300
[    0.197593] pci 0000:00:03.0: reg 0x10: [mem 0xf7a1c000-0xf7a1ffff 64bit]
[    0.197652] pci 0000:00:04.0: [8086:0c03] type 00 class 0x118000
[    0.197658] pci 0000:00:04.0: reg 0x10: [mem 0xf7a10000-0xf7a17fff 64bit]
[    0.197734] pci 0000:00:14.0: [8086:8c31] type 00 class 0x0c0330
[    0.197749] pci 0000:00:14.0: reg 0x10: [mem 0xf7a00000-0xf7a0ffff 64bit]
[    0.197800] pci 0000:00:14.0: PME# supported from D3hot D3cold
[    0.197828] pci 0000:00:14.0: System wakeup disabled by ACPI
[    0.197855] pci 0000:00:16.0: [8086:8c3a] type 00 class 0x078000
[    0.197870] pci 0000:00:16.0: reg 0x10: [mem 0xf7a26000-0xf7a2600f 64bit]
[    0.197923] pci 0000:00:16.0: PME# supported from D0 D3hot D3cold
[    0.197982] pci 0000:00:1a.0: [8086:8c2d] type 00 class 0x0c0320
[    0.197996] pci 0000:00:1a.0: reg 0x10: [mem 0xf7a24000-0xf7a243ff]
[    0.198069] pci 0000:00:1a.0: PME# supported from D0 D3hot D3cold
[    0.198105] pci 0000:00:1a.0: System wakeup disabled by ACPI
[    0.198134] pci 0000:00:1b.0: [8086:8c20] type 00 class 0x040300
[    0.198146] pci 0000:00:1b.0: reg 0x10: [mem 0xf7a18000-0xf7a1bfff 64bit]
[    0.198196] pci 0000:00:1b.0: PME# supported from D0 D3hot D3cold
[    0.198227] pci 0000:00:1b.0: System wakeup disabled by ACPI
[    0.198254] pci 0000:00:1c.0: [8086:8c10] type 01 class 0x060400
[    0.198308] pci 0000:00:1c.0: PME# supported from D0 D3hot D3cold
[    0.198361] pci 0000:00:1c.0: System wakeup disabled by ACPI
[    0.198388] pci 0000:00:1c.2: [8086:8c14] type 01 class 0x060400
[    0.198443] pci 0000:00:1c.2: PME# supported from D0 D3hot D3cold
[    0.198496] pci 0000:00:1c.2: System wakeup disabled by ACPI
[    0.198523] pci 0000:00:1c.3: [8086:8c16] type 01 class 0x060400
[    0.198577] pci 0000:00:1c.3: PME# supported from D0 D3hot D3cold
[    0.198629] pci 0000:00:1c.3: System wakeup disabled by ACPI
[    0.198660] pci 0000:00:1d.0: [8086:8c26] type 00 class 0x0c0320
[    0.198675] pci 0000:00:1d.0: reg 0x10: [mem 0xf7a23000-0xf7a233ff]
[    0.198747] pci 0000:00:1d.0: PME# supported from D0 D3hot D3cold
[    0.198784] pci 0000:00:1d.0: System wakeup disabled by ACPI
[    0.198812] pci 0000:00:1f.0: [8086:8c4b] type 00 class 0x060100
[    0.198948] pci 0000:00:1f.2: [8086:8c03] type 00 class 0x010601
[    0.198959] pci 0000:00:1f.2: reg 0x10: [io  0xf0b0-0xf0b7]
[    0.198965] pci 0000:00:1f.2: reg 0x14: [io  0xf0a0-0xf0a3]
[    0.198971] pci 0000:00:1f.2: reg 0x18: [io  0xf090-0xf097]
[    0.198977] pci 0000:00:1f.2: reg 0x1c: [io  0xf080-0xf083]
[    0.198983] pci 0000:00:1f.2: reg 0x20: [io  0xf060-0xf07f]
[    0.198989] pci 0000:00:1f.2: reg 0x24: [mem 0xf7a22000-0xf7a227ff]
[    0.199019] pci 0000:00:1f.2: PME# supported from D3hot
[    0.199068] pci 0000:00:1f.3: [8086:8c22] type 00 class 0x0c0500
[    0.199080] pci 0000:00:1f.3: reg 0x10: [mem 0xf7a21000-0xf7a210ff 64bit]
[    0.199096] pci 0000:00:1f.3: reg 0x20: [io  0xf040-0xf05f]
[    0.199162] pci 0000:00:1f.6: [8086:8c24] type 00 class 0x118000
[    0.199176] pci 0000:00:1f.6: reg 0x10: [mem 0xf7a20000-0xf7a20fff 64bit]
[    0.199287] pci 0000:00:01.0: PCI bridge to [bus 02-03]
[    0.199333] pci 0000:0a:00.0: [10de:1391] type 00 class 0x030200
[    0.199349] pci 0000:0a:00.0: reg 0x10: [mem 0xf6000000-0xf6ffffff]
[    0.199365] pci 0000:0a:00.0: reg 0x14: [mem 0xe0000000-0xefffffff 64bit pref]
[    0.199380] pci 0000:0a:00.0: reg 0x1c: [mem 0xf0000000-0xf1ffffff 64bit pref]
[    0.199390] pci 0000:0a:00.0: reg 0x24: [io  0xe000-0xe07f]
[    0.199400] pci 0000:0a:00.0: reg 0x30: [mem 0xf7000000-0xf707ffff pref]
[    0.199510] pci 0000:0a:00.0: System wakeup disabled by ACPI
[    0.211429] pci 0000:00:01.1: PCI bridge to [bus 0a]
[    0.211431] pci 0000:00:01.1:   bridge window [io  0xe000-0xefff]
[    0.211433] pci 0000:00:01.1:   bridge window [mem 0xf6000000-0xf70fffff]
[    0.211435] pci 0000:00:01.1:   bridge window [mem 0xe0000000-0xf1ffffff 64bit pref]
[    0.211498] acpiphp: Slot [1] registered
[    0.211503] pci 0000:00:1c.0: PCI bridge to [bus 04-05]
[    0.211574] pci 0000:06:00.0: [10ec:8168] type 00 class 0x020000
[    0.211593] pci 0000:06:00.0: reg 0x10: [io  0xd000-0xd0ff]
[    0.211620] pci 0000:06:00.0: reg 0x18: [mem 0xf7904000-0xf7904fff 64bit]
[    0.211638] pci 0000:06:00.0: reg 0x20: [mem 0xf7900000-0xf7903fff 64bit]
[    0.211733] pci 0000:06:00.0: supports D1 D2
[    0.211734] pci 0000:06:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[    0.211784] pci 0000:06:00.0: System wakeup disabled by ACPI
[    0.223436] pci 0000:00:1c.2: PCI bridge to [bus 06]
[    0.223439] pci 0000:00:1c.2:   bridge window [io  0xd000-0xdfff]
[    0.223442] pci 0000:00:1c.2:   bridge window [mem 0xf7900000-0xf79fffff]
[    0.223557] pci 0000:07:00.0: [8086:08b3] type 00 class 0x028000
[    0.223613] pci 0000:07:00.0: reg 0x10: [mem 0xf7800000-0xf7801fff 64bit]
[    0.223820] pci 0000:07:00.0: PME# supported from D0 D3hot D3cold
[    0.223896] pci 0000:07:00.0: System wakeup disabled by ACPI
[    0.235458] pci 0000:00:1c.3: PCI bridge to [bus 07-09]
[    0.235463] pci 0000:00:1c.3:   bridge window [mem 0xf7800000-0xf78fffff]
[    0.236277] ACPI: PCI Interrupt Link [LNKA] (IRQs 3 4 5 6 10 *11 12 14 15)
[    0.236320] ACPI: PCI Interrupt Link [LNKB] (IRQs 3 4 5 6 *10 11 12 14 15)
[    0.236363] ACPI: PCI Interrupt Link [LNKC] (IRQs 3 *4 5 6 10 11 12 14 15)
[    0.236405] ACPI: PCI Interrupt Link [LNKD] (IRQs 3 4 *5 6 10 11 12 14 15)
[    0.236448] ACPI: PCI Interrupt Link [LNKE] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
[    0.236489] ACPI: PCI Interrupt Link [LNKF] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
[    0.236531] ACPI: PCI Interrupt Link [LNKG] (IRQs *3 4 5 6 10 11 12 14 15)
[    0.236572] ACPI: PCI Interrupt Link [LNKH] (IRQs 3 4 5 6 10 *11 12 14 15)
[    0.236837] ACPI: Enabled 4 GPEs in block 00 to 3F
[    0.236901] ACPI : EC: interrupt unblocked
[    0.236906] ACPI : EC: event unblocked
[    0.236911] ACPI: \_SB_.PCI0.LPCB.EC__: GPE=0x17, EC_CMD/EC_SC=0x66, EC_DATA=0x62
[    0.236912] ACPI: \_SB_.PCI0.LPCB.EC__: Used as boot DSDT EC to handle transactions and events
[    0.237064] vgaarb: setting as boot device: PCI:0000:00:02.0
[    0.237065] vgaarb: device added: PCI:0000:00:02.0,decodes=io+mem,owns=io+mem,locks=none
[    0.237067] vgaarb: loaded
[    0.237068] vgaarb: bridge control possible 0000:00:02.0
[    0.237090] Registered efivars operations
[    0.244403] PCI: Using ACPI for IRQ routing
[    0.245707] PCI: pci_cache_line_size set to 64 bytes
[    0.245770] e820: reserve RAM buffer [mem 0x00058000-0x0005ffff]
[    0.245770] e820: reserve RAM buffer [mem 0x0009f000-0x0009ffff]
[    0.245771] e820: reserve RAM buffer [mem 0xba77d000-0xbbffffff]
[    0.245771] e820: reserve RAM buffer [mem 0xbabba000-0xbbffffff]
[    0.245772] e820: reserve RAM buffer [mem 0xcab78000-0xcbffffff]
[    0.245773] e820: reserve RAM buffer [mem 0x22fe00000-0x22fffffff]
[    0.245870] hpet0: at MMIO 0xfed00000, IRQs 2, 8, 0, 0, 0, 0, 0, 0
[    0.245873] hpet0: 8 comparators, 64-bit 14.318180 MHz counter
[    0.247895] clocksource: Switched to clocksource hpet
[    0.252449] VFS: Disk quotas dquot_6.6.0
[    0.252465] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[    0.252520] pnp: PnP ACPI init
[    0.252580] system 00:00: [mem 0xfed40000-0xfed44fff] has been reserved
[    0.252582] system 00:00: Plug and Play ACPI device, IDs PNP0c01 (active)
[    0.252738] system 00:01: [io  0x0680-0x069f] has been reserved
[    0.252739] system 00:01: [io  0xffff] has been reserved
[    0.252740] system 00:01: [io  0xffff] has been reserved
[    0.252741] system 00:01: [io  0xffff] has been reserved
[    0.252742] system 00:01: [io  0x1c00-0x1cfe] has been reserved
[    0.252743] system 00:01: [io  0x1d00-0x1dfe] has been reserved
[    0.252743] system 00:01: [io  0x1e00-0x1efe] has been reserved
[    0.252744] system 00:01: [io  0x1f00-0x1ffe] has been reserved
[    0.252745] system 00:01: [io  0x1800-0x18fe] has been reserved
[    0.252746] system 00:01: [io  0x164e-0x164f] has been reserved
[    0.252747] system 00:01: Plug and Play ACPI device, IDs PNP0c02 (active)
[    0.252762] pnp 00:02: Plug and Play ACPI device, IDs PNP0b00 (active)
[    0.252796] system 00:03: [io  0x1854-0x1857] has been reserved
[    0.252797] system 00:03: Plug and Play ACPI device, IDs INT3f0d PNP0c02 (active)
[    0.252829] system 00:04: [io  0x04d0-0x04d1] has been reserved
[    0.252830] system 00:04: Plug and Play ACPI device, IDs PNP0c02 (active)
[    0.252848] pnp 00:05: Plug and Play ACPI device, IDs PNP0303 (active)
[    0.252868] pnp 00:06: Plug and Play ACPI device, IDs DLL0680 PNP0f13 (active)
[    0.253127] system 00:07: [mem 0xfed1c000-0xfed1ffff] has been reserved
[    0.253128] system 00:07: [mem 0xfed10000-0xfed17fff] has been reserved
[    0.253129] system 00:07: [mem 0xfed18000-0xfed18fff] has been reserved
[    0.253130] system 00:07: [mem 0xfed19000-0xfed19fff] has been reserved
[    0.253131] system 00:07: [mem 0xf8000000-0xfbffffff] has been reserved
[    0.253132] system 00:07: [mem 0xfed20000-0xfed3ffff] has been reserved
[    0.253133] system 00:07: [mem 0xfed90000-0xfed93fff] could not be reserved
[    0.253133] system 00:07: [mem 0xfed45000-0xfed8ffff] has been reserved
[    0.253134] system 00:07: [mem 0xff000000-0xffffffff] has been reserved
[    0.253135] system 00:07: [mem 0xfee00000-0xfeefffff] could not be reserved
[    0.253136] system 00:07: [mem 0xf7fdf000-0xf7fdffff] has been reserved
[    0.253137] system 00:07: [mem 0xf7fe0000-0xf7feffff] has been reserved
[    0.253138] system 00:07: Plug and Play ACPI device, IDs PNP0c02 (active)
[    0.253364] pnp: PnP ACPI: found 8 devices
[    0.259073] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[    0.259098] pci 0000:00:01.0: PCI bridge to [bus 02-03]
[    0.259103] pci 0000:00:01.1: PCI bridge to [bus 0a]
[    0.259104] pci 0000:00:01.1:   bridge window [io  0xe000-0xefff]
[    0.259105] pci 0000:00:01.1:   bridge window [mem 0xf6000000-0xf70fffff]
[    0.259107] pci 0000:00:01.1:   bridge window [mem 0xe0000000-0xf1ffffff 64bit pref]
[    0.259109] pci 0000:00:1c.0: PCI bridge to [bus 04-05]
[    0.259117] pci 0000:00:1c.2: PCI bridge to [bus 06]
[    0.259120] pci 0000:00:1c.2:   bridge window [io  0xd000-0xdfff]
[    0.259123] pci 0000:00:1c.2:   bridge window [mem 0xf7900000-0xf79fffff]
[    0.259129] pci 0000:00:1c.3: PCI bridge to [bus 07-09]
[    0.259133] pci 0000:00:1c.3:   bridge window [mem 0xf7800000-0xf78fffff]
[    0.259139] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[    0.259140] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
[    0.259141] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000bffff window]
[    0.259141] pci_bus 0000:00: resource 7 [mem 0x000d0000-0x000d3fff window]
[    0.259142] pci_bus 0000:00: resource 8 [mem 0x000d4000-0x000d7fff window]
[    0.259142] pci_bus 0000:00: resource 9 [mem 0x000d8000-0x000dbfff window]
[    0.259143] pci_bus 0000:00: resource 10 [mem 0x000dc000-0x000dffff window]
[    0.259144] pci_bus 0000:00: resource 11 [mem 0xcf200000-0xfeafffff window]
[    0.259144] pci_bus 0000:0a: resource 0 [io  0xe000-0xefff]
[    0.259145] pci_bus 0000:0a: resource 1 [mem 0xf6000000-0xf70fffff]
[    0.259146] pci_bus 0000:0a: resource 2 [mem 0xe0000000-0xf1ffffff 64bit pref]
[    0.259146] pci_bus 0000:06: resource 0 [io  0xd000-0xdfff]
[    0.259147] pci_bus 0000:06: resource 1 [mem 0xf7900000-0xf79fffff]
[    0.259148] pci_bus 0000:07: resource 1 [mem 0xf7800000-0xf78fffff]
[    0.259246] NET: Registered protocol family 2
[    0.259372] TCP established hash table entries: 65536 (order: 7, 524288 bytes)
[    0.259450] TCP bind hash table entries: 65536 (order: 8, 1048576 bytes)
[    0.259559] TCP: Hash tables configured (established 65536 bind 65536)
[    0.259572] UDP hash table entries: 4096 (order: 5, 131072 bytes)
[    0.259590] UDP-Lite hash table entries: 4096 (order: 5, 131072 bytes)
[    0.259638] NET: Registered protocol family 1
[    0.259648] pci 0000:00:02.0: Video device with shadowed ROM at [mem 0x000c0000-0x000dffff]
[    0.308018] PCI: CLS 64 bytes, default 64
[    0.308055] Unpacking initramfs...
[    0.526179] Freeing initrd memory: 17892K
[    0.526245] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[    0.526247] software IO TLB [mem 0xb677d000-0xba77d000] (64MB) mapped at [ffff8fe73677d000-ffff8fe73a77cfff]
[    0.526530] audit: initializing netlink subsys (disabled)
[    0.526542] audit: type=2000 audit(1516138536.496:1): initialized
[    0.526827] workingset: timestamp_bits=40 max_order=21 bucket_order=0
[    0.526881] zbud: loaded
[    0.527361] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 250)
[    0.527385] io scheduler noop registered
[    0.527386] io scheduler deadline registered
[    0.527395] io scheduler cfq registered (default)
[    0.527905] pci_hotplug: PCI Hot Plug PCI Core version: 0.5
[    0.527908] pciehp: PCI Express Hot Plug Controller Driver version: 0.4
[    0.527918] efifb: probing for efifb
[    0.527944] efifb: framebuffer at 0xd0000000, using 8128k, total 8128k
[    0.527945] efifb: mode is 1920x1080x32, linelength=7680, pages=1
[    0.527945] efifb: scrolling: redraw
[    0.527946] efifb: Truecolor: size=8:8:8:8, shift=24:16:8:0
[    0.530993] Console: switching to colour frame buffer device 240x67
[    0.533789] fb0: EFI VGA frame buffer device
[    0.533793] intel_idle: MWAIT substates: 0x42120
[    0.533794] intel_idle: v0.4.1 model 0x3C
[    0.534001] intel_idle: lapic_timer_reliable_states 0xffffffff
[    0.534144] GHES: HEST is not enabled!
[    0.534180] Serial: 8250/16550 driver, 4 ports, IRQ sharing enabled
[    0.534482] Linux agpgart interface v0.103
[    0.534532] AMD IOMMUv2 driver by Joerg Roedel <jroedel@suse.de>
[    0.534532] AMD IOMMUv2 functionality not available on this system
[    0.534946] i8042: PNP: PS/2 Controller [PNP0303:PS2K,PNP0f13:PS2M] at 0x60,0x64 irq 1,12
[    0.537197] serio: i8042 KBD port at 0x60,0x64 irq 1
[    0.537200] serio: i8042 AUX port at 0x60,0x64 irq 12
[    0.537278] mousedev: PS/2 mouse device common for all mice
[    0.537306] rtc_cmos 00:02: RTC can wake from S4
[    0.537413] rtc_cmos 00:02: rtc core: registered rtc_cmos as rtc0
[    0.537438] rtc_cmos 00:02: alarms up to one month, y3k, 242 bytes nvram, hpet irqs
[    0.537444] intel_pstate: Intel P-state driver initializing
[    0.537806] ledtrig-cpu: registered to indicate activity on CPUs
[    0.538844] NET: Registered protocol family 10
[    0.539372] mip6: Mobile IPv6
[    0.539376] NET: Registered protocol family 17
[    0.539381] mpls_gso: MPLS GSO support
[    0.540067] microcode: sig=0x306c3, pf=0x20, revision=0x22
[    0.540419] microcode: Microcode Update Driver: v2.01 <tigran@aivazian.fsnet.co.uk>, Peter Oruba
[    0.540771] registered taskstats version 1
[    0.540813] zswap: loaded using pool lzo/zbud
[    0.541162] ima: No TPM chip found, activating TPM-bypass!
[    0.542620] rtc_cmos 00:02: setting system clock to 2018-01-16 21:35:37 UTC (1516138537)
[    0.542676] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input0
[    0.542887] PM: Hibernation image not present or could not be loaded.
[    0.545841] Freeing unused kernel memory: 1408K
[    0.545843] Write protecting the kernel read-only data: 12288k
[    0.547051] Freeing unused kernel memory: 1980K
[    0.554578] Freeing unused kernel memory: 1248K
[    0.566670] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    0.580078] random: systemd-udevd: uninitialized urandom read (16 bytes read)
[    0.580130] random: systemd-udevd: uninitialized urandom read (16 bytes read)
[    0.580136] random: systemd-udevd: uninitialized urandom read (16 bytes read)
[    0.580687] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.580708] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.581477] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.581510] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.581518] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.581687] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.581720] random: udevadm: uninitialized urandom read (16 bytes read)
[    0.599543] thermal LNXTHERM:00: registered as thermal_zone0
[    0.599544] ACPI: Thermal Zone [TZ00] (28 C)
[    0.599707] thermal LNXTHERM:01: registered as thermal_zone1
[    0.599707] ACPI: Thermal Zone [TZ01] (30 C)
[    0.601013] r8169 Gigabit Ethernet driver 2.3LK-NAPI loaded
[    0.601019] r8169 0000:06:00.0: can't disable ASPM; OS doesn't have ASPM control
[    0.601305] ACPI: bus type USB registered
[    0.601323] usbcore: registered new interface driver usbfs
[    0.601331] usbcore: registered new interface driver hub
[    0.601361] usbcore: registered new device driver usb
[    0.601706] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
[    0.602069] ehci-pci: EHCI PCI platform driver
[    0.602175] i801_smbus 0000:00:1f.3: SPD Write Disable is set
[    0.602200] i801_smbus 0000:00:1f.3: SMBus using PCI interrupt
[    0.602832] SCSI subsystem initialized
[    0.603069] ehci-pci 0000:00:1a.0: EHCI Host Controller
[    0.603075] ehci-pci 0000:00:1a.0: new USB bus registered, assigned bus number 1
[    0.603086] ehci-pci 0000:00:1a.0: debug port 2
[    0.603934] libata version 3.00 loaded.
[    0.606000] AVX2 version of gcm_enc/dec engaged.
[    0.606001] AES CTR mode by8 optimization enabled
[    0.606999] ehci-pci 0000:00:1a.0: cache line size of 64 is not supported
[    0.607022] ehci-pci 0000:00:1a.0: irq 16, io mem 0xf7a24000
[    0.612814] r8169 0000:06:00.0 eth0: RTL8168g/8111g at 0xffffb2f640c89000, e0:db:55:fb:aa:69, XID 10900880 IRQ 28
[    0.612815] r8169 0000:06:00.0 eth0: jumbo features [frames: 9200 bytes, tx checksumming: ko]
[    0.615502] r8169 0000:06:00.0 enp6s0: renamed from eth0
[    0.623900] ehci-pci 0000:00:1a.0: USB 2.0 started, EHCI 1.00
[    0.624196] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002
[    0.624208] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    0.624209] usb usb1: Product: EHCI Host Controller
[    0.624210] usb usb1: Manufacturer: Linux 4.9.0-5-amd64 ehci_hcd
[    0.624211] usb usb1: SerialNumber: 0000:00:1a.0
[    0.624449] hub 1-0:1.0: USB hub found
[    0.624476] hub 1-0:1.0: 2 ports detected
[    0.624882] ehci-pci 0000:00:1d.0: EHCI Host Controller
[    0.624887] ehci-pci 0000:00:1d.0: new USB bus registered, assigned bus number 2
[    0.624898] ehci-pci 0000:00:1d.0: debug port 2
[    0.628812] ehci-pci 0000:00:1d.0: cache line size of 64 is not supported
[    0.628823] ehci-pci 0000:00:1d.0: irq 23, io mem 0xf7a23000
[    0.643894] ehci-pci 0000:00:1d.0: USB 2.0 started, EHCI 1.00
[    0.643953] usb usb2: New USB device found, idVendor=1d6b, idProduct=0002
[    0.643954] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    0.643956] usb usb2: Product: EHCI Host Controller
[    0.643957] usb usb2: Manufacturer: Linux 4.9.0-5-amd64 ehci_hcd
[    0.643958] usb usb2: SerialNumber: 0000:00:1d.0
[    0.644167] hub 2-0:1.0: USB hub found
[    0.644171] hub 2-0:1.0: 2 ports detected
[    0.644322] ahci 0000:00:1f.2: version 3.0
[    0.644546] ahci 0000:00:1f.2: AHCI 0001.0300 32 slots 6 ports 6 Gbps 0x30 impl SATA mode
[    0.644547] ahci 0000:00:1f.2: flags: 64bit ncq led clo pio slum part ems apst 
[    0.656606] scsi host0: ahci
[    0.656749] scsi host1: ahci
[    0.656888] scsi host2: ahci
[    0.657029] scsi host3: ahci
[    0.657164] scsi host4: ahci
[    0.657282] scsi host5: ahci
[    0.657327] ata1: DUMMY
[    0.657328] ata2: DUMMY
[    0.657328] ata3: DUMMY
[    0.657329] ata4: DUMMY
[    0.657331] ata5: SATA max UDMA/133 abar m2048@0xf7a22000 port 0xf7a22300 irq 29
[    0.657332] ata6: SATA max UDMA/133 abar m2048@0xf7a22000 port 0xf7a22380 irq 29
[    0.657469] xhci_hcd 0000:00:14.0: xHCI Host Controller
[    0.657473] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 3
[    0.658547] xhci_hcd 0000:00:14.0: hcc params 0x200077c1 hci version 0x100 quirks 0x00009810
[    0.658550] xhci_hcd 0000:00:14.0: cache line size of 64 is not supported
[    0.658707] usb usb3: New USB device found, idVendor=1d6b, idProduct=0002
[    0.658708] usb usb3: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    0.658709] usb usb3: Product: xHCI Host Controller
[    0.658710] usb usb3: Manufacturer: Linux 4.9.0-5-amd64 xhci-hcd
[    0.658710] usb usb3: SerialNumber: 0000:00:14.0
[    0.658825] hub 3-0:1.0: USB hub found
[    0.658855] hub 3-0:1.0: 14 ports detected
[    0.660819] xhci_hcd 0000:00:14.0: xHCI Host Controller
[    0.660822] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 4
[    0.661201] usb usb4: New USB device found, idVendor=1d6b, idProduct=0003
[    0.661202] usb usb4: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    0.661202] usb usb4: Product: xHCI Host Controller
[    0.661214] usb usb4: Manufacturer: Linux 4.9.0-5-amd64 xhci-hcd
[    0.661215] usb usb4: SerialNumber: 0000:00:14.0
[    0.661446] hub 4-0:1.0: USB hub found
[    0.661473] hub 4-0:1.0: 6 ports detected
[    0.661884] usb: port power management may be unreliable
[    0.951913] usb 1-1: new high-speed USB device number 2 using ehci-pci
[    0.971230] ata5: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    0.971247] ata6: SATA link up 1.5 Gbps (SStatus 113 SControl 300)
[    0.971910] usb 2-1: new high-speed USB device number 2 using ehci-pci
[    0.972923] ata6.00: ATAPI: MATSHITA DVD+/-RW UJ8E2, 1.01, max UDMA/133
[    0.974434] ata6.00: configured for UDMA/133
[    0.987909] usb 3-2: new low-speed USB device number 2 using xhci_hcd
[    1.026654] ata5.00: ACPI cmd ef/10:06:00:00:00:00 (SET FEATURES) succeeded
[    1.026657] ata5.00: ACPI cmd f5/00:00:00:00:00:00 (SECURITY FREEZE LOCK) filtered out
[    1.026658] ata5.00: ACPI cmd b1/c1:00:00:00:00:00 (DEVICE CONFIGURATION OVERLAY) filtered out
[    1.071043] ata5.00: ATA-9: ST1000LM014-1EJ164, DEMF, max UDMA/133
[    1.071045] ata5.00: 1953525168 sectors, multi 16: LBA48 NCQ (depth 31/32), AA
[    1.100356] usb 1-1: New USB device found, idVendor=8087, idProduct=8008
[    1.100357] usb 1-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.100711] hub 1-1:1.0: USB hub found
[    1.100798] hub 1-1:1.0: 6 ports detected
[    1.115356] ata5.00: ACPI cmd ef/10:06:00:00:00:00 (SET FEATURES) succeeded
[    1.115358] ata5.00: ACPI cmd f5/00:00:00:00:00:00 (SECURITY FREEZE LOCK) filtered out
[    1.115359] ata5.00: ACPI cmd b1/c1:00:00:00:00:00 (DEVICE CONFIGURATION OVERLAY) filtered out
[    1.120349] usb 2-1: New USB device found, idVendor=8087, idProduct=8000
[    1.120351] usb 2-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.120683] hub 2-1:1.0: USB hub found
[    1.120773] hub 2-1:1.0: 8 ports detected
[    1.133502] usb 3-2: New USB device found, idVendor=0458, idProduct=0186
[    1.133504] usb 3-2: New USB device strings: Mfr=4, Product=40, SerialNumber=0
[    1.133505] usb 3-2: Product: Wired Mouse
[    1.133506] usb 3-2: Manufacturer: KYE SYSTEMS CORP.
[    1.135212] hidraw: raw HID events driver (C) Jiri Kosina
[    1.137411] usbhid 3-2:1.1: couldn't find an input interrupt endpoint
[    1.137447] usbcore: registered new interface driver usbhid
[    1.137447] usbhid: USB HID core driver
[    1.137932] input: KYE SYSTEMS CORP. Wired Mouse as /devices/pci0000:00/0000:00:14.0/usb3/3-2/3-2:1.0/0003:0458:0186.0001/input/input3
[    1.137997] hid-generic 0003:0458:0186.0001: input,hidraw0: USB HID v1.11 Mouse [KYE SYSTEMS CORP. Wired Mouse] on usb-0000:00:14.0-2/input0
[    1.159728] ata5.00: configured for UDMA/133
[    1.160024] scsi 4:0:0:0: Direct-Access     ATA      ST1000LM014-1EJ1 DEMF PQ: 0 ANSI: 5
[    1.201666] scsi 5:0:0:0: CD-ROM            MATSHITA DVD+-RW UJ8E2    1.01 PQ: 0 ANSI: 5
[    1.214949] sd 4:0:0:0: [sda] 1953525168 512-byte logical blocks: (1.00 TB/932 GiB)
[    1.214951] sd 4:0:0:0: [sda] 4096-byte physical blocks
[    1.215023] sd 4:0:0:0: [sda] Write Protect is off
[    1.215025] sd 4:0:0:0: [sda] Mode Sense: 00 3a 00 00
[    1.215052] sd 4:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    1.226212] sr 5:0:0:0: [sr0] scsi3-mmc drive: 24x/24x writer dvd-ram cd/rw xa/form2 cdda tray
[    1.226214] cdrom: Uniform CD-ROM driver Revision: 3.20
[    1.226355] sr 5:0:0:0: Attached scsi CD-ROM sr0
[    1.251882] usb 3-5: new high-speed USB device number 3 using xhci_hcd
[    1.277982]  sda: sda1 sda2 sda3 sda4 sda5 sda6 sda7 sda8 sda9
[    1.278971] sd 4:0:0:0: [sda] Attached SCSI disk
[    1.361252] psmouse serio1: synaptics: queried max coordinates: x [..5660], y [..4718]
[    1.391625] random: fast init done
[    1.392785] psmouse serio1: synaptics: queried min coordinates: x [1366..], y [1254..]
[    1.447905] usb 3-5: New USB device found, idVendor=1bcf, idProduct=2b8a
[    1.447907] usb 3-5: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    1.447908] usb 3-5: Product: Integrated_Webcam_HD
[    1.447909] usb 3-5: Manufacturer: CNFDH73F30401789B3F2
[    1.455240] psmouse serio1: synaptics: Touchpad model: 1, fw: 8.1, id: 0x1e2b1, caps: 0xd00223/0x840300/0x126800/0x0, board id: 2985, fw id: 1565877
[    1.494892] input: SynPS/2 Synaptics TouchPad as /devices/platform/i8042/serio1/input/input2
[    1.527854] tsc: Refined TSC clocksource calibration: 2494.225 MHz
[    1.527860] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x23f3ea95b09, max_idle_ns: 440795287034 ns
[    1.635832] usb 3-6: new full-speed USB device number 4 using xhci_hcd
[    1.776921] usb 3-6: New USB device found, idVendor=8087, idProduct=07dc
[    1.776923] usb 3-6: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    2.552031] clocksource: Switched to clocksource tsc
[    2.596150] PM: Starting manual resume from disk
[    2.596152] PM: Hibernation image partition 8:6 present
[    2.596153] PM: Looking for hibernation image.
[    2.596263] PM: Image not found (code -22)
[    2.596263] PM: Hibernation image not present or could not be loaded.
[    2.733786] EXT4-fs (sda7): mounted filesystem with ordered data mode. Opts: (null)
[    3.442998] systemd[1]: RTC configured in localtime, applying delta of 420 minutes to system time.
[    3.660972] ip_tables: (C) 2000-2006 Netfilter Core Team
[    3.850048] systemd[1]: systemd 232 running in system mode. (+PAM +AUDIT +SELINUX +IMA +APPARMOR +SMACK +SYSVINIT +UTMP +LIBCRYPTSETUP +GCRYPT +GNUTLS +ACL +XZ +LZ4 +SECCOMP +BLKID +ELFUTILS +KMOD +IDN)
[    3.850181] systemd[1]: Detected architecture x86-64.
[    3.850397] systemd[1]: Set hostname to <jrix>.
[    3.863070] random: crng init done
[    4.594005] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[    4.594142] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[    4.594178] systemd[1]: Listening on udev Kernel Socket.
[    4.594235] systemd[1]: Listening on Journal Audit Socket.
[    4.594268] systemd[1]: Listening on udev Control Socket.
[    4.594295] systemd[1]: Listening on Syslog Socket.
[    4.594409] systemd[1]: Created slice User and Session Slice.
[    5.073245] EXT4-fs (sda7): re-mounted. Opts: errors=remount-ro
[    5.133071] systemd-journald[264]: Received request to flush runtime journal from PID 1
[    5.731541] input: Power Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0C:00/input/input4
[    5.731545] ACPI: Power Button [PWRB]
[    5.731582] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input5
[    5.731583] ACPI: Sleep Button [SLPB]
[    5.779611] input: Lid Switch as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0D:00/input/input6
[    5.819536] ACPI: Lid Switch [LID0]
[    5.819592] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input7
[    5.819594] ACPI: Power Button [PWRF]
[    5.819902] input: DELL Wireless hotkeys as /devices/virtual/input/input8
[    5.820016] wmi: Mapper loaded
[    5.935901] intel_pch_thermal 0000:00:1f.6: enabling device (0000 -> 0002)
[    5.936064] intel_pch_thermal 0000:00:1f.6: Sensor can't be enabled
[    5.936159] intel_pch_thermal 0000:00:1f.6: pci device failed to probe
[    5.936770] EDAC MC: Ver: 3.0.0
[    5.987800] ACPI: AC Adapter [ADP1] (on-line)
[    5.987894] ACPI: Battery Slot [BAT0] (battery absent)
[    6.000340] sd 4:0:0:0: Attached scsi generic sg0 type 0
[    6.000361] sr 5:0:0:0: Attached scsi generic sg1 type 5
[    6.006882] input: PC Speaker as /devices/platform/pcspkr/input/input9
[    6.029432] EFI Variables Facility v0.08 2004-May-17
[    6.040839] EDAC ie31200: No ECC support
[    6.105331] [drm] Initialized
[    6.147900] pstore: using zlib compression
[    6.152471] pstore: Registered efi as persistent store backend
[    6.178033] RAPL PMU: API unit is 2^-32 Joules, 4 fixed counters, 655360 ms ovfl timer
[    6.178034] RAPL PMU: hw unit of domain pp0-core 2^-14 Joules
[    6.178034] RAPL PMU: hw unit of domain package 2^-14 Joules
[    6.178035] RAPL PMU: hw unit of domain dram 2^-14 Joules
[    6.178035] RAPL PMU: hw unit of domain pp1-gpu 2^-14 Joules
[    6.441552] shpchp: Standard Hot Plug PCI Controller Driver version: 0.4
[    6.546945] dcdbas dcdbas: Dell Systems Management Base Driver (version 5.6.0-3.2)
[    6.649325] Bluetooth: Core ver 2.22
[    6.649335] NET: Registered protocol family 31
[    6.649335] Bluetooth: HCI device and connection manager initialized
[    6.649337] Bluetooth: HCI socket layer initialized
[    6.649339] Bluetooth: L2CAP socket layer initialized
[    6.649342] Bluetooth: SCO socket layer initialized
[    6.679353] snd_hda_intel 0000:00:03.0: enabling device (0000 -> 0002)
[    6.679479] snd_hda_intel 0000:00:1b.0: enabling device (0000 -> 0002)
[    6.738476] [drm] Memory usable by graphics device = 2048M
[    6.738478] checking generic (d0000000 7f0000) vs hw (d0000000 10000000)
[    6.738479] fb: switching to inteldrmfb from EFI VGA
[    6.738505] Console: switching to colour dummy device 80x25
[    6.738569] [drm] Replacing VGA console driver
[    6.744500] [drm] Supports vblank timestamp caching Rev 2 (21.10.2013).
[    6.744501] [drm] Driver supports precise vblank timestamp query.
[    6.746755] vgaarb: device changed decodes: PCI:0000:00:02.0,olddecodes=io+mem,decodes=io+mem:owns=io+mem
[    6.764114] media: Linux media interface: v0.10
[    6.773126] [Firmware Bug]: ACPI(PEGP) defines _DOD but not _DOS
[    6.774688] ACPI: Video Device [PEGP] (multi-head: yes  rom: yes  post: no)
[    6.774692] ACPI Error: [\_SB_.PCI0.GFX0.DD02._BCL] Namespace lookup failure, AE_NOT_FOUND (20160831/psargs-359)
[    6.774698] ACPI Error: Method parse/execution failed [\_SB.PCI0.PEG0.PEGP.DD02._BCL] (Node ffff8fe8a71ffa78), AE_NOT_FOUND (20160831/psparse-543)
[    6.774841] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/device:44/LNXVIDEO:00/input/input10
[    6.776702] ACPI: Video Device [GFX0] (multi-head: yes  rom: no  post: no)
[    6.776816] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/LNXVIDEO:01/input/input11
[    6.776898] snd_hda_intel 0000:00:03.0: bound 0000:00:02.0 (ops i915_audio_component_bind_ops [i915])
[    6.776902] [drm] Initialized i915 1.6.0 20160919 for 0000:00:02.0 on minor 0
[    6.778607] fbcon: inteldrmfb (fb0) is primary device
[    6.793493] MXM: GUID detected in BIOS
[    6.793549] ACPI Warning: \_SB.PCI0.PEG0.PEGP._DSM: Argument #4 type mismatch - Found [Buffer], ACPI requires [Package] (20160831/nsarguments-95)
[    6.793588] ACPI Warning: \_SB.PCI0.PEG0.PEGP._DSM: Argument #4 type mismatch - Found [Buffer], ACPI requires [Package] (20160831/nsarguments-95)
[    6.793763] pci 0000:0a:00.0: optimus capabilities: enabled, status dynamic power, hda bios codec supported
[    6.793765] VGA switcheroo: detected Optimus DSM method \_SB_.PCI0.PEG0.PEGP handle
[    6.793765] nouveau: detected PR support, will not use DSM
[    6.793784] nouveau 0000:0a:00.0: enabling device (0006 -> 0007)
[    6.805375] Linux video capture interface: v2.00
[    6.853139] usbcore: registered new interface driver btusb
[    6.860635] uvcvideo: Found UVC 1.00 device Integrated_Webcam_HD (1bcf:2b8a)
[    6.865406] Bluetooth: hci0: read Intel version: 370710010002030d00
[    6.869125] uvcvideo 3-5:1.0: Entity type for entity Extension 4 was not initialized!
[    6.869126] uvcvideo 3-5:1.0: Entity type for entity Extension 3 was not initialized!
[    6.869127] uvcvideo 3-5:1.0: Entity type for entity Processing 2 was not initialized!
[    6.869128] uvcvideo 3-5:1.0: Entity type for entity Camera 1 was not initialized!
[    6.869185] input: Integrated_Webcam_HD as /devices/pci0000:00/0000:00:14.0/usb3/3-5/3-5:1.0/input/input12
[    6.869223] usbcore: registered new interface driver uvcvideo
[    6.869223] USB Video Class driver (1.1.1)
[    6.897542] bluetooth hci0: firmware: direct-loading firmware intel/ibt-hw-37.7.10-fw-1.0.2.3.d.bseq
[    6.897545] Bluetooth: hci0: Intel Bluetooth firmware file: intel/ibt-hw-37.7.10-fw-1.0.2.3.d.bseq
[    6.979826] snd_hda_codec_realtek hdaudioC1D0: autoconfig for ALC3234: line_outs=2 (0x14/0x17/0x0/0x0/0x0) type:speaker
[    6.979827] snd_hda_codec_realtek hdaudioC1D0:    speaker_outs=0 (0x0/0x0/0x0/0x0/0x0)
[    6.979829] snd_hda_codec_realtek hdaudioC1D0:    hp_outs=1 (0x21/0x0/0x0/0x0/0x0)
[    6.979829] snd_hda_codec_realtek hdaudioC1D0:    mono: mono_out=0x0
[    6.979830] snd_hda_codec_realtek hdaudioC1D0:    inputs:
[    6.979831] snd_hda_codec_realtek hdaudioC1D0:      Headset Mic=0x19
[    6.979832] snd_hda_codec_realtek hdaudioC1D0:      Headphone Mic=0x1a
[    6.979833] snd_hda_codec_realtek hdaudioC1D0:      Internal Mic=0x12
[    6.982734] Intel(R) Wireless WiFi driver for Linux
[    6.982734] Copyright(c) 2003- 2015 Intel Corporation
[    6.982786] iwlwifi 0000:07:00.0: enabling device (0000 -> 0002)
[    7.021417] Bluetooth: hci0: Intel Bluetooth firmware patch completed and activated
[    7.139248] dell_wmi: Detected Dell WMI interface version 0
[    7.139282] input: Dell WMI hotkeys as /devices/virtual/input/input14
[    7.191985] iTCO_vendor_support: vendor-support=0
[    7.192519] iTCO_wdt: Intel TCO WatchDog Timer Driver v1.11
[    7.192561] iTCO_wdt: Found a Lynx Point TCO device (Version=2, TCOBASE=0x1860)
[    7.192665] iTCO_wdt: initialized. heartbeat=30 sec (nowayout=0)
[    7.242314] iwlwifi 0000:07:00.0: firmware: direct-loading firmware iwlwifi-3160-17.ucode
[    7.242529] iwlwifi 0000:07:00.0: loaded firmware version 17.352738.0 op_mode iwlmvm
[    7.265639] iwlwifi 0000:07:00.0: Detected Intel(R) Dual Band Wireless AC 3160, REV=0x164
[    7.267422] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[    7.267695] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[    7.411246] ieee80211 phy0: Selected rate control algorithm 'iwl-mvm-rs'
[    7.515073] input: HDA Digital PCBeep as /devices/pci0000:00/0000:00:1b.0/sound/card1/input13
[    7.515738] input: HDA Intel PCH Headphone Mic as /devices/pci0000:00/0000:00:1b.0/sound/card1/input15
[    7.859529] intel_rapl: Found RAPL domain package
[    7.859531] intel_rapl: Found RAPL domain core
[    7.859534] intel_rapl: Found RAPL domain uncore
[    7.859536] intel_rapl: Found RAPL domain dram
[    7.907550] Console: switching to colour frame buffer device 240x67
[    7.927291] i915 0000:00:02.0: fb0: inteldrmfb frame buffer device
[    7.927468] nouveau 0000:0a:00.0: NVIDIA GM107 (117110a2)
[    7.946651] nouveau 0000:0a:00.0: bios: version 82.07.29.00.49
[    8.030595] nouveau 0000:0a:00.0: fb: 4096 MiB DDR3
[    8.030650] nouveau 0000:0a:00.0: priv: HUB0: 10ecc0 ffffffff (1e40822c)
[    8.103131] input: HDA Intel HDMI HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:03.0/sound/card0/input16
[    8.103180] input: HDA Intel HDMI HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:03.0/sound/card0/input17
[    8.103221] input: HDA Intel HDMI HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:03.0/sound/card0/input18
[    8.456447] iwlwifi 0000:07:00.0 wlp7s0: renamed from wlan0
[    9.314304] Adding 2097148k swap on /dev/sda6.  Priority:-1 extents:1 across:2097148k FS
[    9.331296] vga_switcheroo: enabled
[    9.331488] [TTM] Zone  kernel: Available graphics memory: 4042116 kiB
[    9.331489] [TTM] Zone   dma32: Available graphics memory: 2097152 kiB
[    9.331489] [TTM] Initializing pool allocator
[    9.331494] [TTM] Initializing DMA pool allocator
[    9.331519] nouveau 0000:0a:00.0: DRM: VRAM: 4096 MiB
[    9.331520] nouveau 0000:0a:00.0: DRM: GART: 1048576 MiB
[    9.331523] nouveau 0000:0a:00.0: DRM: Pointer to TMDS table invalid
[    9.331543] nouveau 0000:0a:00.0: DRM: DCB version 4.0
[    9.331545] nouveau 0000:0a:00.0: DRM: Pointer to flat panel table invalid
[    9.458811] nouveau 0000:0a:00.0: DRM: MM: using COPY for buffer copies
[    9.458816] [drm] Initialized nouveau 1.3.1 20120801 for 0000:0a:00.0 on minor 1
[   10.853197] EXT4-fs (sda8): mounted filesystem with ordered data mode. Opts: (null)
[   11.469749] EXT4-fs (sda9): mounted filesystem with ordered data mode. Opts: (null)
[   14.634147] Bluetooth: BNEP (Ethernet Emulation) ver 1.3
[   14.634148] Bluetooth: BNEP filters: protocol multicast
[   14.634151] Bluetooth: BNEP socket layer initialized
[   14.838887] nouveau 0000:0a:00.0: DRM: evicting buffers...
[   14.838902] nouveau 0000:0a:00.0: DRM: waiting for kernel channels to go idle...
[   14.838917] nouveau 0000:0a:00.0: DRM: suspending client object trees...
[   14.841581] nouveau 0000:0a:00.0: DRM: suspending kernel object tree...
[   16.138300] IPv6: ADDRCONF(NETDEV_UP): enp6s0: link is not ready
[   16.177701] r8169 0000:06:00.0: firmware: direct-loading firmware rtl_nic/rtl8168g-3.fw
[   16.192953] r8169 0000:06:00.0 enp6s0: link down
[   16.193016] IPv6: ADDRCONF(NETDEV_UP): enp6s0: link is not ready
[   16.235362] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   16.237485] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.237755] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.358157] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.358422] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.372619] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   16.380997] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.381263] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.503818] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.504097] iwlwifi 0000:07:00.0: L1 Enabled - LTR Enabled
[   16.518436] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   17.140858] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   17.815033] nouveau 0000:0a:00.0: DRM: resuming kernel object tree...
[   17.928758] nouveau 0000:0a:00.0: priv: HUB0: 10ecc0 ffffffff (1a40822c)
[   17.949010] nouveau 0000:0a:00.0: DRM: resuming client object trees...
[   29.941832] nouveau 0000:0a:00.0: DRM: evicting buffers...
[   30.010068] nouveau 0000:0a:00.0: DRM: waiting for kernel channels to go idle...
[   30.010086] nouveau 0000:0a:00.0: DRM: suspending client object trees...
[   30.012791] nouveau 0000:0a:00.0: DRM: suspending kernel object tree...
[   40.085461] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   40.088415] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   40.091984] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   43.057067] nouveau 0000:0a:00.0: DRM: resuming kernel object tree...
[   43.198505] nouveau 0000:0a:00.0: priv: HUB0: 10ecc0 ffffffff (1a40822c)
[   43.218970] nouveau 0000:0a:00.0: DRM: resuming client object trees...
[   58.658402] Bluetooth: RFCOMM TTY layer initialized
[   58.658407] Bluetooth: RFCOMM socket layer initialized
[   58.658413] Bluetooth: RFCOMM ver 1.11
[   68.850934] nouveau 0000:0a:00.0: DRM: evicting buffers...
[   68.850936] nouveau 0000:0a:00.0: DRM: waiting for kernel channels to go idle...
[   68.850958] nouveau 0000:0a:00.0: DRM: suspending client object trees...
[   68.853732] nouveau 0000:0a:00.0: DRM: suspending kernel object tree...
[   70.232789] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   70.325655] wlp7s0: authenticate with 9c:6f:52:f8:55:4e
[   70.328744] wlp7s0: send auth to 9c:6f:52:f8:55:4e (try 1/3)
[   70.332773] wlp7s0: authenticated
[   70.334809] wlp7s0: associate with 9c:6f:52:f8:55:4e (try 1/3)
[   70.338592] wlp7s0: RX AssocResp from 9c:6f:52:f8:55:4e (capab=0x411 status=0 aid=2)
[   70.341947] wlp7s0: associated
[   70.341992] IPv6: ADDRCONF(NETDEV_CHANGE): wlp7s0: link becomes ready
[   84.653038] wlp7s0: deauthenticating from 9c:6f:52:f8:55:4e by local choice (Reason: 3=DEAUTH_LEAVING)
[   84.663356] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   84.671103] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[   88.080938] wlp7s0: authenticate with f4:28:53:c0:7c:24
[   88.083276] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[   88.085164] wlp7s0: authenticated
[   88.697383] iwlwifi 0000:07:00.0: No association and the time event is over already...
[   88.697396] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[   93.087976] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[   96.596014] wlp7s0: authenticate with f4:28:53:c0:7c:24
[   96.598310] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[   96.600072] wlp7s0: authenticated
[   97.212402] iwlwifi 0000:07:00.0: No association and the time event is over already...
[   97.212428] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  101.600570] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  105.508765] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  105.511088] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  105.512853] wlp7s0: authenticated
[  106.125181] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  106.125206] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  109.128138] nouveau 0000:0a:00.0: DRM: resuming kernel object tree...
[  109.272432] nouveau 0000:0a:00.0: priv: HUB0: 10ecc0 ffffffff (1a40822c)
[  109.292894] nouveau 0000:0a:00.0: DRM: resuming client object trees...
[  110.022066] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  110.117806] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  110.121386] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  113.536268] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  113.625373] wlp7s0: authenticate with 9c:6f:52:f8:55:4e
[  113.627604] wlp7s0: send auth to 9c:6f:52:f8:55:4e (try 1/3)
[  113.629360] wlp7s0: authenticated
[  113.631662] wlp7s0: associate with 9c:6f:52:f8:55:4e (try 1/3)
[  113.637859] wlp7s0: RX AssocResp from 9c:6f:52:f8:55:4e (capab=0x411 status=0 aid=2)
[  113.643794] wlp7s0: associated
[  113.643851] IPv6: ADDRCONF(NETDEV_CHANGE): wlp7s0: link becomes ready
[  114.199838] wlp7s0: deauthenticating from 9c:6f:52:f8:55:4e by local choice (Reason: 3=DEAUTH_LEAVING)
[  114.207798] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  114.214003] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  114.931552] nouveau 0000:0a:00.0: DRM: evicting buffers...
[  114.931556] nouveau 0000:0a:00.0: DRM: waiting for kernel channels to go idle...
[  114.931580] nouveau 0000:0a:00.0: DRM: suspending client object trees...
[  114.934428] nouveau 0000:0a:00.0: DRM: suspending kernel object tree...
[  117.622465] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  117.624718] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  117.628807] wlp7s0: authenticated
[  118.238797] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  118.238815] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  122.629457] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  126.137448] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  126.139830] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  126.141596] wlp7s0: authenticated
[  126.753913] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  126.753948] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  131.141044] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  135.050354] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  135.052709] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  135.054442] wlp7s0: authenticated
[  135.666792] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  135.666817] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  139.019307] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  139.022390] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  139.026306] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  142.463513] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  142.543638] wlp7s0: authenticate with 9c:6f:52:f8:55:4e
[  142.545976] wlp7s0: send auth to 9c:6f:52:f8:55:4e (try 1/3)
[  142.547775] wlp7s0: authenticated
[  142.549540] wlp7s0: associate with 9c:6f:52:f8:55:4e (try 1/3)
[  142.553315] wlp7s0: RX AssocResp from 9c:6f:52:f8:55:4e (capab=0x411 status=0 aid=2)
[  142.556585] wlp7s0: associated
[  142.556631] IPv6: ADDRCONF(NETDEV_CHANGE): wlp7s0: link becomes ready
[  146.229437] nouveau 0000:0a:00.0: DRM: resuming kernel object tree...
[  146.379989] nouveau 0000:0a:00.0: priv: HUB0: 10ecc0 ffffffff (1a40822c)
[  146.400471] nouveau 0000:0a:00.0: DRM: resuming client object trees...
[  149.115107] wlp7s0: deauthenticating from 9c:6f:52:f8:55:4e by local choice (Reason: 3=DEAUTH_LEAVING)
[  149.125208] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  149.136566] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  152.044834] nouveau 0000:0a:00.0: DRM: evicting buffers...
[  152.044836] nouveau 0000:0a:00.0: DRM: waiting for kernel channels to go idle...
[  152.044858] nouveau 0000:0a:00.0: DRM: suspending client object trees...
[  152.047543] nouveau 0000:0a:00.0: DRM: suspending kernel object tree...
[  152.556346] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  152.558660] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  152.560439] wlp7s0: authenticated
[  153.172745] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  153.172754] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  157.558692] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  161.066606] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  161.069129] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  161.070954] wlp7s0: authenticated
[  161.683146] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  161.683169] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  166.069197] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  169.977402] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  169.979719] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  169.981538] wlp7s0: authenticated
[  170.593822] iwlwifi 0000:07:00.0: No association and the time event is over already...
[  170.593845] wlp7s0: Connection to AP f4:28:53:c0:7c:24 lost
[  174.016345] wlp7s0: aborting authentication with f4:28:53:c0:7c:24 by local choice (Reason: 3=DEAUTH_LEAVING)
[  174.019516] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  174.023616] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  177.190811] IPv6: ADDRCONF(NETDEV_UP): wlp7s0: link is not ready
[  180.648878] wlp7s0: authenticate with f4:28:53:c0:7c:24
[  180.651264] wlp7s0: send auth to f4:28:53:c0:7c:24 (try 1/3)
[  180.653087] wlp7s0: authenticated
[  180.654346] wlp7s0: associate with f4:28:53:c0:7c:24 (try 1/3)
[  180.658400] wlp7s0: RX AssocResp from f4:28:53:c0:7c:24 (capab=0x411 status=0 aid=2)
[  180.665376] wlp7s0: associated
[  180.665403] IPv6: ADDRCONF(NETDEV_CHANGE): wlp7s0: link becomes ready

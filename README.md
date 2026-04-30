Build & Run

    # Linux / macOS
    gcc -std=c11 -O2 simulated_os.c -o simos && ./simos

    # Windows (MSVC)
    cl /O2 simulated_os.c /Fe:simos.exe && simos.exe


Key commands to try


    help        → full command list
    gui         → launch 2D ASCII desktop
    ps / top    → process monitor
    spawn web 32 1  → create a process
    meminfo     → visual memory map
    dmesg       → kernel log
    ls /etc     → browse the virtual filesystem
    cat /etc/simos.conf
    hexdump /etc/passwd
    irq 14      → trigger a page fault
    stress 10   → spawn 10 processes
    crash       → blue screen of death
    reboot      → full kernel reinit

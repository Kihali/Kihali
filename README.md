@@ -0,0 +1,15 @@
{
    "configurations": [
    {
        "name": "connect to qemu gdb",
        "type": "gdb",
        "request": "attach",        // Attach to remote
        "target": "localhost:1234", // Address of remote
        "executable": "${workspaceRoot}/SalieriOS.elf",    // Path to file who contain symbols
        "gdbpath": "gdb",           // Path to gdb
        "cwd": "${workspaceRoot}",

        "remote": true
    }
    ]
} 

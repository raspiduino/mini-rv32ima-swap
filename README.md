# mini-rv32ima, but using swap

This modified version of mini-rv32ima shows how this emulator can use swap instead of RAM array, so you might be able to port it to RAM limited devices.

Usage: Replace dump.bin with dump.org.bin (the original RAM) everytime you restart the emulator
Then run `./mini-rv32ima -l -f dump.bin`

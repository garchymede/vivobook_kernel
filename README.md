# Cooking a kernel for the Asus vivobook e200ha 

1. Get the latest kernel sources from here http://kernel.org/ and decompress it. 

2. Inside the new kernel directory, replace the sound directory with the compressed one from this repository or directly from https://git.kernel.org/pub/scm/linux/kernel/git/tiwai/sound.git/commit/

3. Run the following command : <b>make clean && make mrproper </b>

4. Copy the config file from this repository

5. If you want to modify some options, run <b>make xconfig</b>

6. Then compile your new kernel with this command : <b>make</b>

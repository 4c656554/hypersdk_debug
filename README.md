# hypersdk_debug
A repo to help debug a hypersdk file transfer issue (https://github.com/datproject/sdk/issues/79)

# Instructions

1.  Open file A on a browser. It should create a hyperdrive and save files with increasing sizes to the drive. 
2.  Copy the key of the new hyperdrive
3.  Open file B on another browser. Keep the first browser open.
4.  Copy the key into the input box.
5.  Click run. This should attempt to copy the files across from the hyperdrive created by A. You may need to refresh and re-run to get it to work.
6.  Observe the console errors in browser A.

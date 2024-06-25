### Why need to run source command for .bashrc alias to get applied?
`.bashrc` is read only once, when bash starts. It is just so by design (and has always been). If you make any subsequent changes to `.bashrc`, they won't be applied until `.bashrc` is re-read. By running `source .bashrc`, you make exactly this - you tell bash to re-read that file.

### What is `.bashrc` file?<sup>[[Youtube](https://www.youtube.com/watch?v=pYL0iKIyik4&ab_channel=ProgrammingKnowledge)]
The **.bashrc** file is a script file that’s executed when a user logs in. The file itself contains a series of configurations for the terminal session. This includes setting up or enabling: coloring, completion, shell history, command aliases

### Why need to run source command for .bashrc alias to get applied?
`.bashrc` is read only once, when bash starts. It is just so by design (and has always been). If you make any subsequent changes to `.bashrc`, they won't be applied until `.bashrc` is re-read. By running `source .bashrc`, you make exactly this - you tell bash to re-read that file.

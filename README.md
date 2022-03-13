# Napoleon

This is at least the 3rd run for a little servant. First approaches where with browser clients and login. The last trial was a simple TUI with decent colored output.

The background of this tool is a computer living in fictional crime stories from my youth. Gert Prokop wrote some stories about his post-american detective Timothy Truckle. His partner was a big computer, called Napoleon, living in a cabinet. Napoleon was allowed to talk in rare cases, where the output via paper strips was too slow.

My next approach for Napoleon will be an interactive shell for daily stuff. This is inspired by an article from John Arundel about scripting with Go, which was followed by buying the whole book, called "The power of Go - Tools". The backend will be coupled via ProtoBuf over NATS. Maybe there will be more than one backend. The shell works with various kind of data ...

* long-time knowledge like Wikipedia,
* short-time information like weather forcast and
* ad-hoc aquired data like the delay of a train or travel time depending on current traffic situation.

We will get some nice features like ...

* an extended configuration,
* connections to various local services like khard or taskwarrior,
* connections to remote services like google calendar,
* a local brain in case we have no web access,
* an interpreter for pseudocode in English and German and
* RiveScript for all the stuff the interpreter doesn't knows.

The current single backend lives in another repo called [Ghosts](https://github.com/cntzr/ghosts).

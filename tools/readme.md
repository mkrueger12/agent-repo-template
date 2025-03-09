## Tools

### What are the tools?

Any function that you may want your agents to use should be stored in tools. This means ANY function. You may be tempted to place some in other folders, but if you believe that at any point in the future your agent will need to use it, it should be in tools.

For example, in a current agentic dev project, I have a few static steps where a function is reading data from the current directory. My agent does not have access to this tool yet.
Clearly, at some point, I will want my agent to read data from the current directory. I stored this in tools.

### What about subdirectories?

I don't have a good answer here. For now, I try group them in logical ```.py``` files. Open a PR if you have a way to organize them better.

# Questions

- How to know when a blob was successfully downloaded?  
  > *17:45	@whyrusleeping*	pguth2: the 'ipfs pin -r <hash>' command (and corresponding API call) will not complete until the file in question has been received entirely

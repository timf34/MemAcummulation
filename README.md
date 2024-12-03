# MemAccumulation

I don't understand why/ how memory is accumulating on the server for this code. 

You pass a URL to the client, it sends to the server, which extracts the contents of the article. 

However, (see below...)

Ah... ok so wait, memory will actually decrease when you add a smaller article. But... if you were to follow these steps:

1. Add a small article 
2. Add a large article 
3. Add a small article again 

The memory does not decrease to the same level as when you first added the small article, its still larger.

I don't see the memory accummulation that it seemed like we had though!
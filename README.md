FastCache
=========

Similar to memcached, but hopefully faster and better, with multi-depth lists. So not all keys are in a single global space, but Key->Key2->Key3->value  is three separate lists. The primary purpose of this is to be ultra fast in random reads from millions of keys, but if nothing else.

This will be a nodejs-module, so that it can be used directly in any high level app, or converted to a server.

It will be a very fast 4DHashMap.

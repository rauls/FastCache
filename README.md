FastCache
=========

Similar to memcached, but hopefully faster and better, with multi-depth lists. So not all keys are in a single global space, but Key->Key2->Key3->value  is three separate lists. The primary purpose of this is to be ultra fast in random reads from millions of keys, but if nothing else, a very low overhead daemon that can run in mobile devices too. Consider this an experiment, 
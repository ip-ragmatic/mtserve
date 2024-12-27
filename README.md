# mtserve

`mtserve` is a multithreaded web-server. This is the final project from "The Book". But I want to
expand this for my own use and to learn more about how servers work and to get better at concurrency
and parallelism in Rust (slightly different things technically speaking).

## TODOS

- [ ] Remove all the `unwrap`s and implement some real error handling.
- [ ] Figure out how to dynamically size `ThreadPool` based on computer resources (or maybe based on
  something else).
- [ ] Upgrade `handle_connection` to handle requests, match statuses, and respond much more
  intelligently.
- [ ] Add some async rust in here somewhere.
- [ ] MAYBE: Turn into library crate for sake of allowing this to be used in other applications.


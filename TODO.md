## Required for 1.0

* Much improved submode guessing.  This is partially done in 0.5 by
  using 'datetime' library.


## Other ideas

* Yet more movement commands, e.g. move inside the same thread.  This
  is not so difficult to implement, but requires pondering on how to
  make the commands comfortable to use.

* Undo/redo for various filtering and explicit hiding operations.

* Context when filtering (like grep -C): optionally show N entries
  before/after each that matches filter.

* Keep a time context, so that multiple windows can be synced and traversed
  through using the same time.

  + Stretch goal would be to add/subtract timezones, so that windows not in the
    same timezone would still be able to be synced for review.

Patch of 
[jiangmiao/auto-pairs](https://github.com/jiangmiao/auto-pairs/blob/master/plugin/auto-pairs.vim)
to skip pairing `'` following `<` or `&`, which is used in rust lifetime specifiers.
This doesn't work perfectly, e.g. if there are interposing newlines or multiple
specifiers, but is better than the default behavior.

See also:
- [_The Rust Programming Language_: 
  Lifetimes](https://doc.rust-lang.org/book/lifetimes.html)
- [jiangmiao/auto-pairs: Issue 
  138](https://github.com/jiangmiao/auto-pairs/issues/138)

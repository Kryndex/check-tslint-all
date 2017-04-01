# check-tslint-all

Install globally and run `check-tslint-all` in a directory with `tslint.json` and `node_modules` to
list rules that haven't been specified in `tslint.json`.

This is useful to keep up to date with new rules that come out with tslint updates, so you can specify your
preferences in `tslint.json`.

Currently checks rules for:

* tslint
* tslint-immutable
* tslint-react
* and whatever is in rulesDirectory

**Example**

```sh
$ check-tslint-all

Unspecified rules in tslint.json
================================
align
array-type
ban
ban-types
completed-docs
curly
...
```

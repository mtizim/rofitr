# rofitr

A bash script to translate text using rofi, simplified compared
to the master branch.

## Usage

<table>
<tbody>
<tr><th colspan="2"><strong>Translation</strong></th></tr><tr><td><strong>Input</strong></td><td><strong>Description</strong></td></tr>
<tr><td><code>en:es text</code></td><td>Override default SOURCE and TARGET</td></tr>
<tr><td><code>:en text</code></td><td>Auto-detect SOURCE; translate into English</td></tr>
<tr><td><i>text</i></td><td>Translate with defaults, and show the examples</td></tr>
<tr><th colspan="2"><strong>Actions</strong></th></tr><tr><td><strong>Keyword</strong></td><td><strong>Description</strong></td></tr>
<tr><td><code>?</code></td><td>display usage</td></tr>
</tbody>
</table>

#### Command line:

- Launch rofitr:

```
$ rofitr
```

- Translate into Swedish:

```
$ rofitr :sv speed
```

## Requirements

- [rofi](https://github.com/davatorium/rofi)
- [crow-translate](https://github.com/crow-translate/crow-translate)

## Configuration

Edit the script, it's simple enough. It's not clean though, some variables probably do nothing

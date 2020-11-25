# Vue-Quill-Plain-Clipboard

## Prerequisites
[Vue-Quill-Editor](https://github.com/surmon-china/vue-quill-editor)

### Installation
``` bash
npm install vue-quill-plain-clipboard --save-dev
```

### Usage
``` javascript
import Vue from 'vue'
import Quill from 'quill'
import VueQuillEditor from 'vue-quill-editor'
import VuePlainClipboard from 'vue-quill-plain-clipboard'

Quill.register('modules/clipboard', VuePlainClipboard, true)

```

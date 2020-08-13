# qg-json-schema-editor-visual

A json-schema editor of high efficient and easy-to-use, base on React.

> 该版本是为了适配公司业务修改过的
> ![avatar](json-schema-editor-visual.jpg)

## Usage

```
npm install qg-json-schema-editor-visual
```

```js
const option = {};
import 'antd/dist/antd.css';
require('qg-json-schema-editor-visual/dist/main.css');
const schemaEditor = require('qg-json-schema-editor-visual/dist/main.js');
const SchemaEditor = schemaEditor(option);

render(<SchemaEditor />, document.getElementById('root'));
```

## Option Object

| name | desc                                 | default |
| ---- | ------------------------------------ | ------- |
| `lg` | language, support `en_US` or `zh_CN` | en_US   |

## SchemaEditor Props

| name            | type     | default | desc               |
| --------------- | -------- | ------- | ------------------ |
| `data`          | string   | null    | the data of editor |
| `onChange`      | function | null    |
| `showEditor`    | boolean  | false   |
| `logicEntities` | array    | false   | 待选择的逻辑实体   |

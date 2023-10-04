# Vue Switches

A Vue.js component for simple switches with theme support for [bulma](http://bulma.io), [bootstrap](http://getbootstrap.com/) and custom themes.

## Installation

```bash
npm install vue-switches --save
```

## Basic Usage

```javascript
import Switches from 'vue-switches';

new Vue({

    components: {
        Switches
    },

    data () {
        return {
            enabled: false
        }
    }
};
```

```html

<switches v-model="enabled"></switches>

```

## Props
<table>
    <thead>
        <tr>
            <th>Prop</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>label</td>
            <td>A static label to always display whether on or off.</td>
        </tr>
        <tr>
            <td>text-enabled</td>
            <td>The text that displays when enabled.</td>
        </tr>
        <tr>
            <td>text-disabled</td>
            <td>The text that displays when disabled.</td>
        </tr>
        <tr>
            <td>theme</td>
            <td>Which theme to use.</td>
        </tr>
        <tr>
            <td>color</td>
            <td>Which color to use. </td>
        </tr>
        <tr>
            <td>type-bold</td>
            <td>Bigger style.</td>
        </tr>
        <tr>
            <td>emit-on-mount</td>
            <td>By default, a "changed" event is emitted when the component mounts. To disable this, set this to false.</td>
        </tr>
    </tbody>

</table>

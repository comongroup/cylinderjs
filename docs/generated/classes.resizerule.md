<a name="CylinderResizeRule"></a>

## CylinderResizeRule
**Kind**: global class  

* [CylinderResizeRule](#CylinderResizeRule)
    * [new CylinderResizeRule(options)](#new_CylinderResizeRule_new)
    * [.toString()](#CylinderResizeRule+toString) ⇒ <code>String</code>


* * *

<a name="new_CylinderResizeRule_new"></a>

### new CylinderResizeRule(options)
Creates a new rule to be used with the Cylinder/Resize module.

<table>
  <thead>
    <tr>
      <th>Param</th><th>Type</th><th>Description</th>
    </tr>
  </thead>
  <tbody>
<tr>
    <td>options</td><td><code>Object</code></td><td><p>The options for this rule.</p>
</td>
    </tr><tr>
    <td>options.width_min</td><td><code>Number</code></td><td><p>The mininum width.</p>
</td>
    </tr><tr>
    <td>options.width_max</td><td><code>Number</code></td><td><p>The maximum width.</p>
</td>
    </tr><tr>
    <td>options.height_min</td><td><code>Number</code></td><td><p>The mininum height.</p>
</td>
    </tr><tr>
    <td>options.height_max</td><td><code>Number</code></td><td><p>The maximum height.</p>
</td>
    </tr><tr>
    <td>options.callback<Number,Number,CylinderResizeRule></td><td><code>function</code></td><td><p>A callback function defining the rule given a width and height. Must return a boolean.</p>
</td>
    </tr>  </tbody>
</table>

**Example**  
```js
// creates a new rule
```

* * *

<a name="CylinderResizeRule+toString"></a>

### cylinderResizeRule.toString() ⇒ <code>String</code>
Turns the rule into a string.

**Kind**: instance method of <code>[CylinderResizeRule](#CylinderResizeRule)</code>  

* * *

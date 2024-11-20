---
class:  px-4
layout: two-cols-header
---


<h1 class="text-center">Stranger Things - JavaScript Edition</h1>

<div class="px-4">


```js {monaco-run}
console.log(0 == [])
```
</div>

::left::

```js
[] == ![];
true == [];
true == ![];
false == [];
false == ![];
!!"false" == !!"true";
!!"false" === !!"true";
true == "true";
```

::right::

```js
null == 0;
null > 0;
null >= 0;
1 < 2 < 3;
3 > 2 > 1;
“10” + “2” = ?
“10” - “2” = ?
[] + [] = ?
{} + [] = ?
```


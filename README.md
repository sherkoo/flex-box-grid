# Flex Box Grid
A simple, light weight Flex Box Grid System.

Current Column Sizes:
===
```HTML
<div class="grid-1">100%</div>
<div class="grid-1-2">50%</div>
<div class="grid-1-3">33.33%</div>
<div class="grid-1-4">25%</div>
```

Instructions:
===
1. Wrap your content with a class of ```.grid-container```
2. Establish each row with a class of ```.grid-row```
3. Specify each column with a class of ```.grid-1-*```

Example:
===
```HTML
<div class="grid-container">
  <div class="grid-row">
    <div class="grid-1 grid-sm-1">
      <div class="box">Grid 1/1</div>
    </div>
  </div>
</div>
```

![](https://raw.githubusercontent.com/stephenherko/flex-box-grid/master/screenshot.png)

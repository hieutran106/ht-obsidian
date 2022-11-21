## for each with index
```html
<!-- ko foreach: {data: items, as: 'item'} -->
<div class="mb-2">
    Access idex by using $index()
</div>
<!-- /ko -->
```

## debug in template
```html
<div data-bind="text: ko.toJSON($root, null, 2)"></div>
```
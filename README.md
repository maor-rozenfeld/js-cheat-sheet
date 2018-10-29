### LINQ

| C# | JS | Example | ES6 
| --- | --- | -----  | ------
| Where | filter | people.filter(function (item) { return item.age < 30; });| people.filter( p => p.age < 30 ); |
| Select| map | people.map(function (item) { return item.name; });| people.map( p => p.name ); |
| All| every | people.every(function (item) { return  item.age < 40; });| people.every( p => p.age < 40); |
| Any| some | people.some(function (item) { return  item.age < 30; });| people.some( p => p.age < 30 ); |
| Aggregate| reduce | people.reduce(function (item1, item2) {	return  { name: '', age: item1.age + item2.age }; });| people.reduce( (a, b) => { name: '', age: a.age + b.age }); |
| OrderBy| sort | people.sort(function (a, b) { return  a.name > b.name ? 1 : 0; });| people.sort( (a, b) => a.name > b.name ? 1 : 0 ) |
| foreach| forEach | people.forEach(function(item) { console.log(item); });| people.forEach( p => console.log(p) ) |


### jQuery AJAX

```
$.ajax(
	url: '/hello',
	method: 'POST' //'GET',
	complete:
	error:
	success:
).done.fail.always;
```

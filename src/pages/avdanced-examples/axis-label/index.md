---
title: "Axis Label"
description: "Axis Label"
layout: "guide"
weight: 1
---

###### {$page.description}

<article id="1">

{call Chart.render}
	{param columns: [
		[
			'id': 'data1',
			'data': [10, 70, 30, 120, 20, 10],
			'axis': 'y'
		],
		[
			'id': 'data2',
			'data': [100, 150, 120, 90, 10, 55],
			'axis': 'y2'
		]
	] /}
	{param axisY: [
		'label': 'Y Axis Label'
	] /}
	{param axisY2: [
		'label': 'Y2 Axis Label',
		'show': true
	] /}
{/call}


```soy
{call Chart.render}
	{param columns: [
		[
			'id': 'data1',
			'data': [10, 70, 30, 120, 20, 10],
			'axis': 'y'
		],
		[
			'id': 'data2',
			'data': [100, 150, 120, 90, 10, 55],
			'axis': 'y2'
		]
	] /}
	{param axisY: [
		'label': 'Y Axis Label'
	] /}
	{param axisY2: [
		'label': 'Y2 Axis Label',
		'show': true
	] /}
{/call}
```

```jsx
<Chart
	columns={[
		{
			id: 'data1',
			data: [10, 70, 30, 120, 20, 10],
			axis: 'y'
		},
		{
			id: 'data2',
			data: [100, 150, 120, 90, 10, 55],
			axis: 'y2'
		}
	]}
	axisY={
		label: 'Y Axis Label'
	}
	axisY2={
		label: 'Y2 Axis Label',
		show: true
	}
/>
```
</article>
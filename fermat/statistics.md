---
layout: page
nav_order: 9
parent: Fermat.js
---

# Statistics

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L91">statistics.ts#L91</a></div>

## correlation <span class="signature">(aX: Array&lt;number&gt;, aY: Array&lt;number&gt;): number</span>

Calculates the correlation between the numbers in two arrays aX and aY.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `aX` | Array&lt;number&gt; |  |  |
| `aY` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L84">statistics.ts#L84</a></div>

## covariance <span class="signature">(aX: Array&lt;number&gt;, aY: Array&lt;number&gt;): number</span>

Calculates the covariance of the numbers in two arrays aX and aY.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `aX` | Array&lt;number&gt; |  |  |
| `aY` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L11">statistics.ts#L11</a></div>

## mean <span class="signature">(values: Array&lt;number&gt;): number</span>

Calculates the mean of an array of numbers.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L36">statistics.ts#L36</a></div>

## median <span class="signature">(values: Array&lt;number&gt;): number</span>

Calculates the median of an array of numbers.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L44">statistics.ts#L44</a></div>

## mode <span class="signature">(values: Array&lt;number&gt;): undefined|number</span>

Calculates the mode of an array of numbers. Returns undefined if no mode
exists, i.e. there are multiple values with the same largest count.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L20">statistics.ts#L20</a></div>

## quantile <span class="signature">(values: Array&lt;number&gt;, p: number): number</span>

Calculates the quantile of an array of numbers for the cumulative
probability p. This method excludes the median in calculation, i.e.
`quantile((1, 2, 3, 4, 5), 0.25) === 2`

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |
| `p` | number |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L78">statistics.ts#L78</a></div>

## stdDev <span class="signature">(values: Array&lt;number&gt;): number</span>

Calculates the standard deviation of an array of numbers.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |


</div>

<div class="docs-item" markdown="1">

<div><a class="source" target="_blank" href="https://github.com/mathigon/fermat.js/tree/master/src/statistics.ts#L69">statistics.ts#L69</a></div>

## variance <span class="signature">(values: Array&lt;number&gt;): undefined|number</span>

Calculates the variance of an array of numbers.

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `values` | Array&lt;number&gt; |  |  |


</div>
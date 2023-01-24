# Spacing

## Margin and Padding

We have the spacing classes using **margin** and **padding**, where the format for use is **{[property](#properties)}{[direction](#directions)}-{[size](#sizes)}** with **sizes** from `*-0` **(0rem)** to `*-7` **(4rem)**.

### Properties

<ul>
    <li><code>m*</code> for <strong>margin</strong></li>
    <li><code>p*</code> for <strong>padding</strong></li>
</ul>

### Directions

<ul>
    <li><code>*t</code> for <strong>top</strong></li>
    <li><code>*r</code> for <strong>right</strong></li>
    <li><code>*b</code> for <strong>bottom</strong></li>
    <li><code>*l</code> for <strong>left</strong></li>
    <li><code>*x</code> for <strong>left</strong> and <strong>right</strong></li>
    <li><code>*y</code> for <strong>top</strong> and <strong>bottom</strong></li>
</ul>

### Sizes

<ul>
    <li><code>*-0</code> for <code>0</code></li>
    <li><code>*-1</code> for <code>0.25rem</code></li>
    <li><code>*-2</code> for <code>0.5rem</code></li>
    <li><code>*-3</code> for <code>1rem</code></li>
    <li><code>*-4</code> for <code>1.5rem</code></li>
    <li><code>*-5</code> for <code>2rem</code></li>
    <li><code>*-6</code> for <code>3rem</code></li>
    <li><code>*-7</code> for <code>4rem</code></li>
    <li><code>*-auto</code> for <code>auto</code></li>
</ul>

### Examples

In an HTML element

```html
<p class="mt-0">Margin top (margin-top: 0)</p>
<p class="ml-2">Margin left (margin-left: 0.5rem)</p>

<p class="pt-0">Padding top (padding-top: 0)</p>
<p class="pl-2">Padding left (padding-left: 0.5rem)</p>

<p class="mx-4">Margin left and right (margin-left: 1rem; margin-right: 1rem)</p>
<p class="my-4">Margin top and bottom (margin-top: 1rem; margin-bottom: 1rem)</p>

<p class="mx-auto">Margin auto (margin-left: auto; margin-right: auto)</p>
```

How it looks inside the CSS

```css
.mt-0 {
	margin-top: 0;
}

.ml-2 {
	margin-left: 0.5rem;
}

.pr-2 {
	padding-right: 0.5rem;
}

.mx-auto {
	margin-left: auto;
	margin-right: auto;
}
```

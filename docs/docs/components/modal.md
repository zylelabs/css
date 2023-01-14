import './modal.style.scss';

# Modal

## Method 1 (Show with url)

<div class="zyle-preview">
    <a class="btn btn-primary is-light" href="#example-modal">Example Modal</a>
    <div id="example-modal" class="modal target">
        <a href="#method-1-show-with-url" class="modal-background"></a>
        <div class="card">
            <header class="card-header">
                <p class="card-header-title">Card Header</p>
            </header>
            <div class="card-body">Card Body</div>
            <footer class="card-footer">Card Footer</footer>
        </div>
    </div>
</div>

```html
<a class="btn btn-primary is-light" href="#example-modal">Example Modal</a>

<div id="example-modal" class="modal target">
	<a href="#method-1-show-with-url" class="modal-background"></a>

	<div class="card">
		<header class="card-header">
			<p class="card-header-title">Card Header</p>
		</header>

		<div class="card-body">Card Body</div>

		<footer class="card-footer">Card Footer</footer>
	</div>
</div>
```

<!-- ## Method 2 (Show with active class and javascript) -->

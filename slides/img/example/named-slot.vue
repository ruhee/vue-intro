
<div class="container">
  <header>
    <slot name="header"></slot>
  </header>
  <main>
    <slot></slot>
  </main>
  <footer>
    <slot name="footer"></slot>
  </footer>
</div>

<template slot="header">
  <h1>Title</h1>
</template>

<p>Main content</p>

<template slot="footer">
  <p>Footer content</p>
</template>


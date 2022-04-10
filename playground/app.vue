<template>
  <div>
    <div>Nuxt module playground!</div>
    <div>
      <daim-button variant="primary">Primary</daim-button>
      <daim-button variant="secondary">secondary</daim-button>
      <daim-button variant="link">link</daim-button>
      <daim-button size="sm">small</daim-button>
      <daim-button size="lg">large</daim-button>
    </div>
    <div>
      <daim-mailgo
        href="mailto:contact@example.com"
        variant="link"
        class="text-black"
      ></daim-mailgo>
      <daim-mailgo
        href="tel:+123-456-278"
        variant="link"
        class="text-black"
      ></daim-mailgo>
    </div>
  </div>
</template>

<script setup></script>

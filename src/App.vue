<template>
  <div style="min-height: 100vh; background: #F5F5F5;">
    <header class="head-navbar">
      <div class="head-nav-content">
        <div class="font-semibold">
          Unsaved product
        </div>
        <div class="spacer" />
        <div>
          <button type="submit" class="rounded-md btn-outline shadow-button py-2 px-4 text-sm font-semibold text-white shadow-sm" style="margin-right: 8px;">
            Discard
          </button>
          <button type="submit" class="rounded-md bg-primary shadow-button py-2 px-4 text-sm font-semibold text-white shadow-sm">
            Save
          </button>
        </div>
      </div>
    </header>
    <div class="container" style="margin-top: 36px;">
      <div class="grid grid-rows-3 grid-flow-col gap-4">
        <div class="row-span-3 bg-primary">01</div>
        <div class="col-span-2 bg-primary">02</div>
        <div class="row-span-2 col-span-2 bg-primary">03</div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

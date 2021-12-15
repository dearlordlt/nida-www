<template>
  <div class="main flex flex-col h-screen min-h-screen">
    <div class="">
      <Header></Header>
    </div>
    <div class="flex-1 overflow-y-auto h-max p-2">
      <slot />
    </div>
    <div class="flex-none">
      <Footer></Footer>
    </div>
  </div>
</template>
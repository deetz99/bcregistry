<template>
  <div
    class="mx-auto flex min-h-screen w-full flex-col bg-bcGovColor-gray1"
  >
    <ConnectHeader />
    <div
      class="mx-auto w-full grow"
    >
      <slot />
    </div>
    <ConnectFooter />
  </div>
</template>

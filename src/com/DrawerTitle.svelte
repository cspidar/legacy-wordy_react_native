<script>
  export let status;
  export let icon;
</script>

<div class="grid-cols-2">
  <div class="absolute left-8 top-5 text-2xl border-b-2">Wordy: movies</div>
  <button
    on:click={status}
    class="ml-2 mr-4 rotate-90 hover:rotate-180 active:scale-110 active:rotate-180 transition-all ease-in-out duration-300 absolute right-2 top-6 "
    ><svg
      xmlns="http://www.w3.org/2000/svg"
      class="inline-block h-6 w-6"
      fill="none"
      viewBox="0 0 24 24"
      stroke="currentColor"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        d={icon}
      />
    </svg></button
  >
</div>

<script>
  function handleSubmit() {
    alert("Hello world!");
  }
</script>

<form on:submit|preventDefault={handleSubmit}>
  <p class="text-gray-500 mb-1">title:</p>
  <input
    required
    class="w-full border-2 border-gray-300 focus:border-yellow-500 rounded outline-none mb-2 p-2"
    placeholder="humanities classes"
  />

  <p class="text-gray-500 mb-1">your confession:</p>
  <textarea
    required
    class="w-full h-32 border-2 border-gray-300 focus:border-yellow-500 rounded outline-none mb-2 p-2"
    placeholder="&quot;nobody ever does the readings, but there are enough men in section that we have a discussion anyway&quot;"
  />

  <p class="text-gray-400 mb-2 text-sm italic">all confessions are anonymous</p>

  <button
    class="bg-gray-200 active:bg-gray-400 hover:bg-gray-300 py-1 px-3 rounded"
    >submit</button
  >
</form>

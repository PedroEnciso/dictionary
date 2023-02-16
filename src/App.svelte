<script>
  const URL = "https://api.dictionaryapi.dev/api/v2/entries/en/";

  let name = "";

  function handleInput(e) {
    name = e.target.value;
  }

  function search() {}
</script>

<main>
  <div class="w-full px-8 pt-8 text-lg max-w-screen-lg mx-auto">
    <div class="w-full">
      <div class="w-full">
        <input
          on:keyup={handleInput}
          type="text"
          class="w-full px-6 py-4 rounded-xl bg-gray-100 focus:ring-blue-500 focus:border-blue-500" />
      </div>

      <div class="mt-8 flex justify-between items-center">
        <div class="">
          <p class="mb-3 text-3xl sm:text-5xl font-bold">keyboard</p>
          <p class="text-purple-600 font-medium text-xl">/'ki:bc:d/</p>
        </div>
        <button
          class="rounded-3xl bg-purple-200 text-purple-600 px-3 py-3 h-fit text-lg font-medium">play</button>
      </div>

      <div class="mt-8 flex items-center">
        <p class="pr-6 italic text-xl font-medium">noun</p>
        <hr class="h-[.5px] w-full bg-gray-200" />
      </div>

      <div class="mt-8">
        <p class="capitalize text-gray-400">meaning</p>
        <ul class="mt-4 list-disc pl-4 marker:purple-700 flex flex-col gap-4">
          <li class="text-purple-600">
            <p class="text-gray-800 pl-2">
              A set of keys used to operate a typewriter, computer etc.
            </p>
          </li>
          <li class="text-purple-600 pl-2">
            <p class="text-gray-800">
              A component of many instruments including the piano, organ, and
              harpsichord consisting of usually black and white keys that cause
              different tones to be produced when struck.
            </p>
          </li>
          <li class="text-purple-600 pl-2">
            <p class="text-gray-800">
              A device with keys of a musical keyboard, used to control
              electronic sound-producing devices which may be built into or
              separate from the keyboard device.
            </p>
          </li>
        </ul>
        <div class="mt-8 flex">
          <p class="pr-6 text-gray-400 capitalize">synonyms</p>
          <p class="text-purple-600 font-semibold">electronic keyboard</p>
        </div>
      </div>

      <div class="mt-8 flex items-center">
        <p class="pr-6 italic text-xl font-medium">verb</p>
        <hr class="h-[.5px] w-full bg-gray-200" />
      </div>

      <div class="mt-8">
        <p class="capitalize text-gray-400">meaning</p>
        <ul class="mt-4 list-disc pl-4 marker:purple-700 flex flex-col gap-4">
          <li class="text-purple-600">
            <p class="text-gray-800 pl-2">To type on a computer keyboard.</p>
            <p class="text-gray-400  pl-2 mt-4">
              "Keyboarding is the part of this job I hate the most."
            </p>
          </li>
        </ul>
      </div>
      <hr class="my-8 h-[.5px] bg-gray-200" />

      <div class="mb-24">
        <p class="capitalize text-gray-400">Source</p>
        <a
          href="https://en.wiktionary.org/wiki/keyboard"
          class="underline mt-4 text-gray-800">https://en.wiktionary.org/wiki/keyboard</a>
      </div>
    </div>
  </div>
</main>

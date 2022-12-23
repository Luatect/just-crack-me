<script type="ts">
  import "highlight.js/styles/github-dark.css";
  import { CodeBlock } from "@skeletonlabs/skeleton";
  import hljs from "highlight.js";
  import { storeHighlightJs } from "@skeletonlabs/skeleton";

  storeHighlightJs.set(hljs);
</script>

<div class="container h-screen mx-auto">
  <div class="h-full flex flex-col justify-center items-center">
    <div class="text-center mb-5">
      <h1 class="font-bold text-3xl">Luatect</h1>
      <p>X-Luatect-Version: trail=1.1</p>
    </div>
    <div class="max-w-4xl w-full">
      <CodeBlock language="lua" code={`
      -- Version: Trail=1.1\nloadstring("https://raw.githubusercontent.com/Luatect/static/main/trail.lua")()
      `} />
    </div>
    <footer class="mt-5">
      <p class="text-xs">&copy; 2023 Luatect</p>
    </footer>
  </div>
</div>

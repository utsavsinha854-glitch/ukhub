  <!-- 3 Real Playing Showcase Cards -->
  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">

    <!-- Card 1: Cyberpunk City -->
    <div class="glass-box rounded-xl overflow-hidden border border-white/10 flex flex-col group hover:border-glow-cyan/50 transition">
      <div class="aspect-video bg-black relative overflow-hidden">
        <canvas id="galleryCanvas1" class="w-full h-full object-cover"></canvas>
        <div class="absolute bottom-2 left-2 px-2 py-0.5 rounded bg-black/70 text-[10px] font-mono text-cyan-400 border border-white/10">
          ● PLAYING (16:9)
        </div>
      </div>
      <div class="p-4 flex-1 flex flex-col justify-between">
        <div>
          <div class="text-[11px] font-mono text-glow-cyan mb-1">Theme: Cyberpunk Tokyo</div>
          <p class="text-xs text-slate-300 font-mono">
            "Neon rain over hyper-detailed skyscraper canyon with glowing violet holo-adverts and wet asphalt."
          </p>
        </div>
        <button onclick="applyPrompt('Neon rain over hyper-detailed skyscraper canyon with glowing violet holo-adverts and wet asphalt.')" class="mt-3 w-full py-1.5 rounded bg-white/5 hover:bg-white/15 text-xs font-mono text-cyan-400 border border-white/10 transition">
          Load This Prompt ↑
        </button>
      </div>
    </div>

    <!-- Card 2: Space Nebula -->
    <div class="glass-box rounded-xl overflow-hidden border border-white/10 flex flex-col group hover:border-glow-violet/50 transition">
      <div class="aspect-video bg-black relative overflow-hidden">
        <canvas id="galleryCanvas2" class="w-full h-full object-cover"></canvas>
        <div class="absolute bottom-2 left-2 px-2 py-0.5 rounded bg-black/70 text-[10px] font-mono text-glow-violet border border-white/10">
          ● PLAYING (16:9)
        </div>
      </div>
      <div class="p-4 flex-1 flex flex-col justify-between">
        <div>
          <div class="text-[11px] font-mono text-glow-violet mb-1">Theme: Deep Space Abyss</div>
          <p class="text-xs text-slate-300 font-mono">
            "Warp flight through glowing emerald and amethyst cosmic dust filaments, distant stars drifting."
          </p>
        </div>
        <button onclick="applyPrompt('Warp flight through glowing emerald and amethyst cosmic dust filaments, distant stars drifting.')" class="mt-3 w-full py-1.5 rounded bg-white/5 hover:bg-white/15 text-xs font-mono text-cyan-400 border border-white/10 transition">
          Load This Prompt ↑
        </button>
      </div>
    </div>

    <!-- Card 3: Volcanic Cavern -->
    <div class="glass-box rounded-xl overflow-hidden border border-white/10 flex flex-col group hover:border-amber-500/50 transition">
      <div class="aspect-video bg-black relative overflow-hidden">
        <canvas id="galleryCanvas3" class="w-full h-full object-cover"></canvas>
        <div class="absolute bottom-2 left-2 px-2 py-0.5 rounded bg-black/70 text-[10px] font-mono text-amber-400 border border-white/10">
          ● PLAYING (16:9)
        </div>
      </div>
      <div class="p-4 flex-1 flex flex-col justify-between">
        <div>
          <div class="text-[11px] font-mono text-amber-400 mb-1">Theme: Molten Core</div>
          <p class="text-xs text-slate-300 font-mono">
            "Volcanic chamber with glowing magma rivers, rising smoke pillars and sparks sweeping into the camera."
          </p>
        </div>
        <button onclick="applyPrompt('Volcanic chamber with glowing magma rivers, rising smoke pillars and sparks sweeping into the camera.')" class="mt-3 w-full py-1.5 rounded bg-white/5 hover:bg-white/15 text-xs font-mono text-cyan-400 border border-white/10 transition">
          Load This Prompt ↑
        </button>
      </div>
    </div>

  </div>
</div>


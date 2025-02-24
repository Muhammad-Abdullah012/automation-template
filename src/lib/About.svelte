<script lang="ts">
  const about = {
    title: "Silate for. Ind. Ins.com. Ind Andrea and Andrea",
    content: [
      "Graduated 'Elegating industrial expert - Special.: Elettrotecnica e Automazione' at the ITIS Mario del Pozzo di Verzuolo (CN) in 2008, the following year he attended the course for Technical Designer of Automatic Plants at the Professional Training Company of Dronero (CN).",
      "In 2018 he qualified to exercise the profession, enrolling in the Register of Industrial Experts of Cuneo in 2019.",
      "After fourteen years of experience in the field of electrical design at an important local company, he decided, in January 2023, to start the activity of a freelancer by opening Studio Silato.",
    ],
  }
</script>

<section class="py-16 bg-gray-50">
  <div class="container">
    <h2 class="text-4xl text-dark mb-8 font-bold text-center">
      {about.title}
    </h2>
    <div class="max-w-3xl mx-auto leading-relaxed">
      {#each about.content as paragraph}
        <p class="mb-6 text-gray-600">{paragraph}</p>
      {/each}
    </div>
  </div>
</section>

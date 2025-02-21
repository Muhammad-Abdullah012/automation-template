<script lang="ts">
  const contact = {
    email: "andrea@studiosilato.it",
    phone: "+39 351 814 7041",
    address: "Via Saluzzo, 87",
    city: "12036 - Revello (CN)",
    country: "Italy",
  };
</script>

<div class="wave-divider-bottom"></div>
<footer class="bg-[#b59775] text-black py-16">
  <div class="container">
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-12">
      <div>
        <h3 class="text-xl mb-6">Study Silato</h3>
        <p class="text-sm mb-2">by Silato Andrea</p>
        <p class="text-sm mb-2">C.F. SLTNDR98E02D742R</p>
        <p class="text-sm mb-2">P.IVA 04034933043</p>
      </div>

      <div>
        <h3 class="text-xl mb-6">Contact us</h3>
        <p class="text-sm mb-2">{contact.email}</p>
        <p class="text-sm mb-2">{contact.phone}</p>
      </div>

      <div>
        <h3 class="text-xl mb-6">Address</h3>
        <p class="text-sm mb-2">{contact.address}</p>
        <p class="text-sm mb-2">{contact.city}</p>
        <p class="text-sm mb-2">{contact.country}</p>
      </div>

      <div>
        <h3 class="text-xl mb-6">Social</h3>
        <div class="flex gap-4">
          <a
            href="https://linkedin.com"
            target="_blank"
            rel="noopener noreferrer"
            class="transition-opacity hover:opacity-80"
          >
            <img
              src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg"
              alt="LinkedIn"
              class="w-6 h-6"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
</footer>

<style>
  .wave-divider-bottom {
    background-size: 100% 100%;
    transform: rotate(180deg);
  }
</style>

<template>
  <div class="h-56 bg-fond1footer">
    <div class="grid grid-cols-5">
      <ul class="mx-10 mt-9">
        <li><RouterLink to="/">Accueil</RouterLink></li>
        <li><RouterLink to="/contact">Contact</RouterLink></li>
        <li><RouterLink to="/apropos">À propos</RouterLink></li>
        <li><RouterLink to="/inscriptions">S'inscrire</RouterLink></li>
        <li><RouterLink to="/connexion">Se connecter</RouterLink></li>
        <li><RouterLink to="/moncompte">Mon compte</RouterLink></li>
        <li><RouterLink to="/messagerie">Messagerie</RouterLink></li>
      </ul>

      <ul class="mt-9">
        <li><RouterLink to="/apropos">Qui sommes-nous ?</RouterLink></li>
        <li><RouterLink to="/apropos">Pourquoi cette inovation ?</RouterLink></li>
        <li><RouterLink to="/apropos">Pour nos utilisateurs</RouterLink></li>
      </ul>

      <ul class="mx-12 mt-9">
        <li><RouterLink to="/contact">Contact</RouterLink></li>
        <li><RouterLink to="/contact">Nous contacter</RouterLink></li>
        <li>Portection de la vie privée</li>
        <li>Nos artistes</li>
        <li><RouterLink to="/nouveauxartistes">Ajouter un artiste</RouterLink></li>
        <li>Portection de la vie privée</li>
      </ul>

      <ul class="mx-12 mt-9">
        <li>Vente et remboursement</li>
        <li>Achat en ligne</li>
        <li>Mode de paiement</li>
      </ul>

      <div class="flex">
        <div class="mt-9 grid grid-cols-1 gap-6">
          <div class="grid-flow-row-2 grid">
            <div class="mb-3 flex h-12 gap-8">
              <img src="/images/mastercard-logo.jpg" />
              <img src="/images/paypal-logo.jpg" />
            </div>
            <div class="mb-7 flex h-12 gap-8">
              <img src="/images/visa.jpg" />
              <img src="/images/cb.jpg" />
            </div>
            <div>
              <div class="flex gap-6">
                <div>
                  <a href="https://www.facebook.com/profile.php?id=100009306961064" aria-label="Facebook">
                    <img src="/icons/facebook.svg" alt="icon facebook"
                  /></a>
                </div>
                <div>
                  <a href="https://www.linkedin.com/in/marion-gillot-8133a7224/" aria-label="Instagram">
                    <img src="/icons/instagram.svg" alt="icon instagram"
                  /></a>
                </div>
                <div>
                  <a href="https://twitter.com/1820Tc" aria-label="Twitter"> <img src="/icons/twitter.svg" alt="icon twitter" /></a>
                </div>
                <div class="w-6">
                  <a href="https://www.linkedin.com/in/marion-gillot-8133a7224/" aria-label="Linlkedin">
                    <img src="/icons/mmi.svg" alt="icon mmi"
                  /></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-7 h-12 bg-fond2footer">
      <nav class="flex">
        <div class="font-regular mx-6 flex space-x-8 p-3 text-sm">
          <h3 class="block"><a href="mentionslegales">Mentions légales</a></h3>
          <h3 class="block">Cookies</h3>
          <h3 class="block">Politique de protection des données personnelles</h3>
          <h3 class="block">Plan du site</h3>
          <h3 class="block">© Kid’sArt FRANCE 2022 Crée par Marion Gillot et Morgane Chamberlin</h3>
          <h3 class="block"><a href="guidestyle">Guide de style </a></h3>
        </div>
      </nav>
    </div>
  </div>
</template>
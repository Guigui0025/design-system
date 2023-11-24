<template>
  <div
    style="background-image: url('./img/pyramides.jpg')"
    class="h-[85vh] bg-cover bg-top"
  >
    <div class="bg-black/20 h-full flex flex-col items-center">
      <TitresH1 class="text-center text-[#E75A36] mt-12">
        Découvrez le monde
      </TitresH1>
      <p class="text-center w-1/4 mb-10 text-lg text-[#E0E0E0]">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis
        placerat rhoncus. Nulla dictum non velit ac bibendum. Sed varius, dui
        eget pharetra condimentum placerat rhoncus. Nulla dictum non velit ac
        bibendum. Sed varius, dui eget pharetra condimentum
      </p>
      <button
        class="bg-[#222c5f] py-4 px-16 rounded-full text-[#fcfcfc] transition hover:bg-white hover:text-[#222c5f]"
      >
        Réservez-ici
      </button>
    </div>
  </div>
  <Container>
    <TitresH1 class="text-center"> Nos offres </TitresH1>
    <ListsGrid>
      <li>
        <CardsIconCard to="/docs/composants">
          <template #icon>
            <i
              class="ri-list-indefinite text-green-500 group-hover:text-green-700"
            ></i>
          </template>
          Composants
        </CardsIconCard>
      </li>

      <li>
        <CardsIconCard to="/docs/layouts">
          <template #icon>
            <i
              class="ri-layout-line text-blue-500 group-hover:text-blue-700"
            ></i>
          </template>
          Layouts
        </CardsIconCard>
      </li>

      <li>
        <CardsIconCard to="/docs/icones">
          <template #icon>
            <i class="ri-heart-line text-red-500 group-hover:text-red-700"></i>
          </template>
          Icones
        </CardsIconCard>
      </li>
    </ListsGrid>
    <TextesParagraphe> Bienvenue sur le site. </TextesParagraphe>

    
  </Container>
</template>
